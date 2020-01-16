# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

The word comes from Ancient Greece. 'Poly' means multi or many. To 'morph' is to change form in some way. When combined, polymorphism describes something that can have many faces or wear many hats. An object that can transform to represented what is needed at that particular time.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

When we apply polymorphism to OO design we are making our code drier and more scaleable. It helps to cut out overloading and repetitive methods and attributes. We can simplify our objects by wrapping them up in an enclosing type that creates a contract between them.

For example we might have a Person object that shares its attributes and methods with a Teacher and Student object. Both of these will share many similarities that come from the Person but they can also have their own unique attributes that they themselves can make use of.

3. What can we use to implement polymorphism in Java?

We can implement polymorphism through the use of abstract parent classes and sub classes. The parent acts as a super class for which all sub classes that we want to be a type of can inherit from. Abstract classes pass down both attributes and methods whereas interfaces can only handle methods.

We can slo use interfaces. This allows us to treat a class being of another type which allows us to group a bunch of classes together under one type. This has an advantage over the inheritance because an object can have many interfaces but only one parent class to inherit from.


4. How many 'forms' can an object take when using polymorphism?

When using inheritance an object can only take the form of the parent type and its own. With interfaces you can have as many types as you like.

5. Give an example of when you could use polymorphism.

You could use polymorphism when dealing with a person's wallet. In particular with the cards in that wallet. We have so many different kinds of cards these days. Credit cards, ID cards, Membership cards, etc. The list is endless. But some of them, can be grouped together, so we can use a abstract card class for all of our bak cards with attributes such as expiry date and card number. We can also share methods through this parent such as getters for the attribute information. Then the sub card classes can set out their unique attributes and deal with them themselves. We can also use interfaces for the cards such as 'IPay', for cards that you use to pay for, 'IPoints' for cards like loyalty cards that let you save points and 'ITap' for cards with the contactless payment methods. All of these card will share similar methods and interfaces allow us to group them together under a type.


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

In composition we are dealing with an object and what other objects help to make up that particular object. The object also becomes the owner of these objects as they are now parts of a greater, all-powerful object.

7. When would you use composition? Provide a simple example in Java.

You could be designing a hero class for a video game. This hero class could have many different sub classes such as a hunter, warrior, paladin or a mage. We want them all to have an attack, but they might all attack using different means of attack. This is where we could use an interface called IAttack to hold attack methods and maybe even calculate the damage output of the attacks. This keeps these methods separate from the individual classes so they don't get too complex.


8. What is/are the advantage(s) of using composition?

Composition allows the class to utilise behaviours from another group of classes and can even change that particular behaviour at run time.

9. When an object is destroyed, what happens to all the objects it is composed of?

When the object is destroyed all of the objects that it is made up of are also destroyed as they are part of the make up of this object.
