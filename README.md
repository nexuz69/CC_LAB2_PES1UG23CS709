CC Lab 2 – Monolithic Architecture

This repository contains my implementation of CC Lab 2 based on Monolithic Architecture using FastAPI.

In this lab, I created a single monolithic application that includes user registration, login, event listing, my-events, and checkout. An intentional error was introduced in the checkout route to demonstrate how a failure in one part of a monolithic system can crash the entire application. The bug was then fixed to restore normal functionality.

Load testing was performed using Locust to measure the performance of the application. The checkout, events, and my-events routes were tested before and after optimization. Code-level optimizations were applied to reduce unnecessary loops and improve response time.

Screenshots SS1 to SS9 are included to show application execution, monolithic failure, bug fixing, and load testing results.

Name: Shashank Y
SRN: PES1UG23CS709
