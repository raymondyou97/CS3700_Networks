# Project 2

- BGP Router
- Team Name: PythonCats
- Team Members: Raymond You, Oliver Zheng

## High-level Approach
First, we made sure we were able to connect to our neighbors and successfully send messages and receive messages back. We then checked that we were able to serialize and deserialize the JSON properly. Next, we worked on getting the simplest UPDATE message to pass. Then, we moved on to the DATA message, and finally, the DUMP message.

## Challenges Faced
It was difficult to keep track of all the data that was going on, especially all the IP addresses, where they should be sent. It was also tricky figuring out what to send through the UPDATE message as it wasn't clear what the ASPath argument that was passed through the command line was to be used for.

## Overview of Testing
Testing was primarily done through printing DEBUG statements to STDOUT. With each step along the way, we would print out some form of test message to ensure our code was doing what we wanted it to do.
