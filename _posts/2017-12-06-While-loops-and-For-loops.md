---
title: While loops and For loops
layout: post
author: nathan.higgins
permalink: /while-loops-and-for-loops/
source-id: 1VWb9I-y6xxxxDNu_cfWKWakhZ5Fp-SwvHEmOl7AVspE
published: true
---
In today's lesson, we learned how to use for loops and while loops and to know when to use them. We learned these by doing simple exercises to get us to learn how to use them and for homework, learn how to use them in our AI program.

While loops are loops used for when you need to keep something going until you want it to stop. Like a guessing game where you need to keep guessing until you get the right number.

For example, here is a while loop:

        Answer = pig

        Guess=input("What is tasty, pink and has a tail?")

        while guess != answer:

          print("That's wrong, try again")

	  guess = input("Guess the animal.")

* This will keep printing "That's wrong, try again" until the user guesses pig

For loops are used when you want the loop to stop after the loop repeating a certain amount of times. Like in a guessing game where you only get 3 guesses for guessing the number and after your 3 guesses, you can't guess anymore.

For example, here is a for loop:

    for counter in range(10):

	print(counter)

* This counts up from 0-9

To put this in our AI program, we had to persevere and think about how  to implement this new knowledge to my old one. I had to refer back to previous work on python to make my code work and to incorporate my new knowledge in my AI program.

