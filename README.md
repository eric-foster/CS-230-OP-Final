# The Gaming Room - Software Design Document (CS-230 Operating Platforms)
For this scenerio, I am operating as a Technology Consultant for Creative Technology Solutions. I have been assigned a client.

## Project Summary
The client, The Gaming Room, is a game development company who is seeking technical advice on how best to approach the development of a cross-platform version of their game that is currently accessible only on Android. The name of the game is called "Draw It or Lose It", which is loosely similar to the 1980's TV game "Win, Lose, or Draw." 

For the game, "Draw It or Lose It", to operate as intended, the application will render images from a large library of stock drawings as clues. A game consists of four rounds of play lasting one minute each. The drawings are rendered at a steady rate and are fully complete at the 30-second mark. If the team does not guess the puzzle before the time runs out, the remaining teams have an opportunity to offer one(1) guess each to solve the puzzle with a 15-second time limit.

The client has some specific software requirements that they want me to address. First, a game must have the ability to have one(1) or more teams involved, meaning we must design our code to anticipate at least one team with the possiblity of more than one team. Second, each team must have the ability to assign multiple players to that team. Third, the game and team names must be unique to allow for users to check whether a name is in use when choosing a team name, meaning we must focus on code design that checks for the uniqueness and usage of a piece of data such as a name. Finally, there must only be one instance of the game that can exist in memory at any given time, meaning we must focus on code design that checks and validates if a game instance already exists to ensure only one instance at a time.

## What did you do particularly well in developing this documentation?
For this particular document, I felt that my best aspect of this document and how I presented information within it was in the Evaluation section. I felt that I throughly explained the important key notes of each operating platform and explained the different tools utilized on those platforms well and in great detail.

## What about the process of working through a design document did you find helpful when developing the code?
The part that best helped me in the development phase of the code was the re-elaboration of the requirements and design constrainsts. Through these sections, I was able to re-evaluate the software requirements that the client was explaining, further deepening my understanding of their problems, and how to best approach a solution to those problems.

## If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
Within this particular document as it sits right now, I would personally go back and revise the requirements section. I can improve this section by further elaborating on the software requirements that the client is requesting by explaining the requests and what I might need to focus on design-wise to ensure that requirement is meant thouroghly.

## How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
As stated above, I felt that I could elaborate more on the users needs for the project at hand. With that said, I did interpret the users needs by fully understanding their problems, then evaluating and implementing a solution to each of those needs. By fully taking the time to understand a problem first and not taking shortcuts, you can set yourself up to best provide the most optimal solution(s) that fit that need.

## How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
Overall, it comes down to research and time management. By understanding the project deeply, you can make more focused analysis on research that can help in the process of designing software. By researching and understanding that research, you can further make more informed decisions on how to advice a client through a document such as this one to ensure you are recommending the best solutions that fit their needs.
