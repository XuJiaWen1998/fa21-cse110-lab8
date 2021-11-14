# Lab Week 8 - Unit & E2E Testing

**Jiawen Xu, Tianze Zhang**

## Intro
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why

1. Within a Github action that runs whenever code is pushed

Reason: If all the developers just run the automated test locally before pushing, there may be conflict since other people may be pushing the code at the same time. If we run them all developmment is completed, it will be hard to detect where the problem is if error or bugs are found, and it will be frustrating since it is more like restarting the whole thing.

## Part 1 - Expose: E2E Testing with Jest-Puppesteer
2) Would you use an end to end test to check if a function is returning the correct output?
   
**No, we should use unit test for specific function**

## Part 2 - Explore: Unit Testing with Jest(2 points)
3) Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.

**No, I would not use a unit test to test the 'message' feature of a messaging application, because it is too complex**

4) Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.

**Yes, I would use a unit test to test the "max message length" feature of a messaging application because this is a comparatively small feature**