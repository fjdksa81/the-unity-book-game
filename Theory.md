# Task 4 Theory
### Charles McDonagh  
## Part I - Identifying and Defining

## Identifying the Need

![Brainstorm](https://github.com/fjdksa81/the-unity-book-game/blob/main/Pictures/Greenneedle.png)

**Need:** To improve the number of strategic games where the death of soldiers actually matters.

**Problem Statement:** Often in strategy games, the death of a soldier or anyone is considered inconsequential, and players are often pushed towards major sacrifices to complete objectives. To better improve how players actually think about the deaths they "cause" a game needs to be developed to better place impact on the death of subordinates.

**Skill Development:** To develop the skills required to create this game, I would do minor research whenever a problem came up I was unable to deal with, otherwise I would use previous knowledge to create the game.

## Requirements Outline

**Inputs** Majority text and response E.G. Y or N responses through python's interactions.

**Processing** Take in various factors due to the choices made, roll dice, add factors onto the dice (think DnD dice system)

**Outputs** Shows the player the final roll, required roll and the written response for their actions.

**Transmission** No transmission will be required.

**Storage** Storage will be handled locally on the user's device.

## Functional Requirements

**User Interaction** Users will be able to respond to various randomly placed events during the course of the game and respond with various responses through the keyboard.

**Gameplay/Simulation Mechanics** Users will be able to respond to events given by the game, these will then influence the success of missions, global stats, etc. This will all go towards a mission at the end of a set number of events/choices/minigames, providing large boosts, advancing the story, or something else.

**Saving and Loading** Users will be able to save and load their current progress, saved on their machine with various variables.

## Non-Functional Requirements

**Scalability** If I wanted to, the inclusion of new campaigns, missions or events could be added to the game, increasing the size of the game.

**Usability** The game should be simple to understand and use, a basic UI and a simple tutorial at the start will educate users as to how to play the game and the basic mechanics.

**Performance** Due to simple considerations and basic processing, the game should lag at most 1 second in unintended loading, though for purposes of suspense the game itself will slow down.

## Consideration of Social and Ethical Issues

**Definitions**

*Equity* - Providing equal opportunity to partake through distribution of resources unequally to those disadvantaged. Levelling the playing field.

*Accessability* - The ability for something to be accessed by those with a natural or unnatural disadvantage or advantage, less of a check box and more of a scale.


**Accessability** Due to the simplistic nature of the game and the simple keyboard controls, anyone capable of navigating the computer and able to touch the keys will be able to access the game. Those with mental disabilities reducing critical thinking capability may struggle more with the strategic element of the game.

**Privacy and Data Protection** The game will not collect any user data apart from local saves that should be protected by the user's own system, and even then they won't make any use of personal information apart from chosen choices, not sensative information anyway.

**Fairness and Representation** Due to the historical setting of the game, the ability to historically accurately portray the period AND make use of a completely respresented cast. It's important to avoid negative portrayals and stereotypes in game characters.

**Mental and Emotional Wellbeing** The game will be extremely tame, and though minor mental issues concerning the subject matter and personal experiences with war etc. may occur, the graphics or lack thereof should lead to a stable mental experience.

**Cultural Sensitivity** The content of the game will be extremely culturally sensative, and little to no content will be at all of issue with any cultures. Other then reasonably tame depictions of war from the air, there should be no culturally sensative content involved.

## Part II - Researching and Planning

**Flowcharts**

![Event Flow Chart](https://github.com/fjdksa81/the-unity-book-game/blob/main/Pictures/efc.png)
![Mission Flow Chart](https://github.com/fjdksa81/the-unity-book-game/blob/main/Pictures/mfc.png)
![Save/Load Flow Chart](https://github.com/fjdksa81/the-unity-book-game/blob/main/Pictures/slfc.png)

**Pseudo Code**

```
BEGIN Event 

Show Event Flavor Text and Options
INPUT Choice

IF Choice == A
   Show text choice
   Modify Required Variables

IF Choice == B
   Show text choice
   Modify Required Variables

IF Choice == C, D, E Etc.
   Show text choice
   Modify Required Variables

END Event


BEGIN Mission

Process Base Chance
Add or Remove Extra Modifyers

IF Result > Required Result
   Show Success
   Modify Stats

If Result < Require Result
   Show failure
   Modify Stats

END Mission

BEGIN Save/Load

Show save/load screen
INPUT User Choice

IF User Choice == Save
   Show Save Slots
   INPUT Save Slot
       IF Save Slot == A,B,C,D, ETC.
         Overwrite save data

IF User Choice == Load
   Show Save Slots
   INPUT Save Slot
       IF Save Slot == A,B,C,D, ETC.
         Load Save data

END Save/Load
```

**StoryBoard - Access Should Work**

https://docs.google.com/document/d/1xMI0TuB3YCUOMnMEcSkjZbyWeGWk2G-BJfURv_Ofz6w/edit?usp=sharing 

**Gantt Chart**

![Gantt Chart](https://github.com/fjdksa81/the-unity-book-game/blob/main/Pictures/ganttchart.png)