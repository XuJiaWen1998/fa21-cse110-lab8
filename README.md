# Lab Week 8 - Unit & E2E Testing

**Jiawen Xu, Tianze Zhang**

## Intro
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why

1. Within a Github action that runs whenever code is pushed

Reason: If all the developers just run the automated test locally before pushing, there may be conflict since other people may be pushing the code at the same time. If we run them all developmment is completed, it will be hard to detect where the problem is if error or bugs are found, and it will be frustrating since it is more like restarting the whole thing.

## Part 1 - Expose: E2E Testing with Jest-Puppesteer
2) Would you use an end to end test to check if a function is returning the correct output?
**No**