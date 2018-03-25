---
title: Conversations with Computers
layout: post
author: cameron.quinn
permalink: /conversations-with-computers/
source-id: 1SMmv6RB00u-BkeLDn4vcj_PZOEO2yId2FlJ1M5HatcE
published: true
---
Conversations with Computers: Week Two of New Term

Today we were back on repl.it but this time we weren't using turtle. As opposed to last week were we were using Python(with Turtle), this week we were using Python3. This week we are setting up a program which allows us to have a "conversation" with the computer. This happens as the computer asks questions to the human and then alters it response depending on what they said. The coding I used is as follows:

print("Good Morning")

name = input("What is your name?")

print("Nice to meet you, "+name+"!")

wellness = input("How are you doing today?")

if wellness.lower() == "good":

  print("I'm glad to hear that!")

elif wellness.lower() == "terrible":

  print("I'm sorry to hear that.")

else:

  print("All right then...")

gender = input("Are you a man or a woman?")

if gender.lower() == "man":

  print("Nice to know, sir!")

elif gender.lower() == "woman":

  print("Nice to know, miss!")

else:

  print("Prefer not to say, that's fine!")

hobby = input("What are your hobbies?")

print("Sounds enjoyable!")

enjoy = input("Are you enjoying our chat so far?")

if enjoy.lower() == "yes":  print("I'm enjoying it too!")

elif enjoy.lower() == "no":

  print("I'll try to make it better then.")

else:

  print("I'll take that as a yes!")

