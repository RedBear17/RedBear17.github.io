---
title: The Math Cheater Programm
layout: post
author: nathan.higgins
permalink: /the-math-cheater-programm/
source-id: 1yIbtMf-hE4quaemcFsf3OXV6OAZthsd96tySxRF8JuQ
published: true
---
#This is a homework cheat program

def main():

  greeting()

  while True:

	select_function()

 

def greeting():

  print ("Hello. I am a homework cheater. How can I assist you?")

 

def select_function():

  print ("These are my functions:- ")

  print ("1: rectangle perimeter")

  print ("2: rectangle area")

  print ("3: cubic volume")

  print ("4: triangle area")

  print ("5: triangle perimeter")

  print ("6: cuboid volume")

  result = input("Please select a number")

  while True:

	if result == "1":

  	a = input("What is the height?")

  	b = input("What is the length?")

  	return(rectangle_perimeter(a, b))

	

	elif result == "2":

  	c = input("What is the height?")

  	d = input("What is the length?")

  	return(rectangle_area(c, d))

	elif result == "3":

  	e = input("What is the length?")

  	f = input("What is the width?")

  	g = input("What is the height?")

  	return(cubic_volume(e, f, g))

	elif result == "4":

  	h = input("What is the vertical height?")

  	i = input("What is the base?")

  	return(triangle_area(h, i))

	

	elif result == "5":

  	j = input("What is the base?")

  	k = input("What is the length of 1 side?")

  	l = input("What is the length of the other side?")

  	return(triangle_perimeter(j, k, l))

	

	elif result == "6":

  	m = input("What is the width?")

  	n = input("What is the height?")

  	o = input("What is the length?")

  	return(cuboid_volume(m, n, o))

	

	else:

  	print("bye then")

  	break

def rectangle_perimeter(a,b):

  print(str(int(a) + int(a) + int(b) + int(b)) + " units")

  	

def rectangle_area(c,d):

  print(str(int(c) * int(d)) +  " units squared")

 

def cubic_volume(e, f, g):

  print(str(int(e) * int(f) * int(g)) + " units cubed")

 

def triangle_area(h, i):

  print(str(0.5 * int(h) * int(i)) + " units squared")

 

def triangle_perimeter(j, k, l):

  print(str(int(j) + int(k) + int(l)) + " units")

 

def cuboid_volume(m, n, o):

  print(str(int(m) * int(n) * int(o)) + " units cubed")

 

	

 

 

 

main()

  	

  	

  	

