# CS 370: Current and Emerging Trends in Computer Science

This repository contains my CS 370 Project Two Jupyter Notebook and my reflection on the work completed in this course.

## Project Two: Pirate Intelligent Agent

For Project Two, I worked with a reinforcement learning environment where a pirate agent had to learn how to move through a maze and reach the treasure. A good portion of the project was already provided as starter code. `TreasureMaze.py` handled the maze itself, including the available moves, rewards and penalties, and whether the pirate won or lost. `GameExperience.py` handled storing previous experiences so they could be used again during training. The neural network and several helper functions were also already provided.

The main part I worked on was the Q-training algorithm in the Jupyter Notebook. The pirate had to learn when to explore the maze and when to use what it had already learned. Each move resulted in either a reward or penalty, and those experiences were stored and later used to continue training the model. After training, the model reached a 100% win rate and was able to successfully reach the treasure.

## Computer Science and Problem Solving

Computer scientists solve problems using technology, programming, algorithms, and logical thinking. The exact work can be very different depending on the job, but the problem-solving part is something that carries across most areas of computer science. It matters because so much of what people and businesses depend on today is built around software and technology.

My approach to computer science problems is pretty similar to how I troubleshoot issues at work in IT. I usually start by figuring out exactly what is happening and gathering as much useful information as I can. From there, I break the problem down, test possible solutions, and adjust based on the results. I do not normally expect the first idea to always be the right one. This project was similar in that way because the pirate improved by trying different actions, getting feedback, and learning from what happened.

## Ethical Responsibilities

I think computer scientists have a responsibility to consider the people who will actually be using the systems they create. A system should work reliably, protect the information it handles, and not create unnecessary risks for the user or the organization.

This is something I already deal with in IT, especially when working with systems that contain private or sensitive information. Security and privacy cannot really be an afterthought. With AI, there are also concerns about how decisions are made and whether the results are reliable or fair. Even if the end user does not understand everything happening behind the scenes, the people designing and maintaining the technology still have a responsibility to make sure it is being used in a safe and reasonable way.
