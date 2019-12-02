# Bonus Challenge
Create a PR with a solution to the bonus challenge by the end of the workshop to share with the group.

## Challenge description below
- Create a new app for your `Robot` assistant in the Snips console called `tellRobot`
- Create an intent for your new app called `voiceSet`
- Create a new slot called `number` with builtin slot type `snips/number`
- Have training examples set the servo to desired positions by voice commands

*Example* : Set servo to 90 degrees

- Write the code to subscribe to the `voiceSet` intent and set the servo angle accordingly

You can update your assistant with the following Sam CLI command before testing your solution.
```
sam update-assistant
```