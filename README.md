
![App Brewery Banner](Documentation/AppBreweryBanner.png)

#  Quizzler

## Our Goal

The goal of this tutorial is to take you one step further in your journey of becoming an app developer. We are going to introduce you to the holy grail of mobile design patterns: the Model View Controller (MVC) pattern. A design pattern is simply a repeatable and optimised solution to a common software problem. We’ll learn more about this when you see it used in the tutorial.

## What you will create

You will program a trivia quiz app, inspired by the awesome “Quiz Up” game. If you have another field of expertise, you’ll be glad to know that multiple choice question apps are one of the most popular types of educational apps on the App Store! 

## What you will learn

* What is a design pattern and how is it used in programming.
* How to use the Model-View-Controller or MVC pattern for app development.
* Learn about Object Oriented Programming.
* How to store data locally.
* How to incorporate third party libraries and how to display Heads Up Displays (HUDs).
* How to refactor code and stay organised.
* Learn about class initialisation. 
* How to programmatically change UI elements such as Labels and Views.
* Start thinking about data encapsulation and how to keep your data safe from corruption.


## Finished App
![Finished App](https://github.com/londonappbrewery/Images/blob/master/Quizzler.gif)




## Quiz Text Strings

        // Creating a quiz item and appending it to the list
        let item = Question(text: "Valentine\'s day is banned in Saudi Arabia.", correctAnswer: true)
        
        // Add the Question to the list of questions
        list.append(item)
        
        // skipping one step and just creating the quiz item inside the append function
        list.append(Question(text: "A slug\'s blood is green.", correctAnswer: true))
        
        list.append(Question(text: "Approximately one quarter of human bones are in the feet.", correctAnswer: true))
        
        list.append(Question(text: "The total surface area of two human lungs is approximately 70 square metres.", correctAnswer: true))
        
        list.append(Question(text: "In West Virginia, USA, if you accidentally hit an animal with your car, you are free to take it home to eat.", correctAnswer: true))
        
        list.append(Question(text: "In London, UK, if you happen to die in the House of Parliament, you are technically entitled to a state funeral, because the building is considered too sacred a place.", correctAnswer: false))
        
        list.append(Question(text: "It is illegal to pee in the Ocean in Portugal.", correctAnswer: true))
        
        list.append(Question(text: "You can lead a cow down stairs but not up stairs.", correctAnswer: false))
        
        list.append(Question(text: "Google was originally called \"Backrub\".", correctAnswer: true))
        
        list.append(Question(text: "Buzz Aldrin\'s mother\'s maiden name was \"Moon\".", correctAnswer: true))
        
        list.append(Question(text: "The loudest sound produced by any animal is 188 decibels. That animal is the African Elephant.", correctAnswer: false))
        
        list.append(Question(text: "No piece of square dry paper can be folded in half more than 7 times.", correctAnswer: false))
        
        list.append(Question(text: "Chocolate affects a dog\'s heart and nervous system; a few ounces are enough to kill a small dog.", correctAnswer: true))
        


>This is a companion project to The App Brewery's Complete App Developement Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)

![End Banner](Documentation/readme-end-banner.png)
