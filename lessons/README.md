This was a lesson to teach three things - comments, the gyro, and my blocks (functions).

Lessons steps:

1. Comment Lesson
- Load any older program written by the children
  - Ask what the program does. Most can't remember. Some remember to look at the program name, but that doesn't help much.

- Load the comments-gyro-myblocks.ev3 program
  - Ask what the program does. Now they can clearly see (due to comments) what each program does.
  - Talk about the benefit of comments:
    - Helping you remember what you were working on previously
    - Helping you understand code from others
    - Helping you explain your work (to judges)
  - Show how you can add multiple comments to sections of a program

2. Gyro lesson
- Show the right turn program
- Run it while watching the sensor in the mindstorms software
- Watch how even this slow, many times it turns by more than 90 degrees
- Explain how you can run the motors until the angle changes by more than 90 degrees (Left, Right or Either = 2)
- Play with the speed of the turn and angle
  - We found that speed = 5 and angle = 89 almost always was a 90 degree turn
- Discussed things to be careful when using gyro
  - When powering on robot, make sure it is stable (not in air) as gyro initializes during startup
  - Never hotplug (plug in gyro) without restarting robot
- Show the "reset" function in the program.
  - This program changes the mode of the sensor which resets it
  - Then it waits for .5 seconds and then waits for the angle to reset to zero
- Show how gyros can be amazing
  - https://www.youtube.com/watch?v=-xTq0XSYC9U
  
3. My blocks lesson
- Have the children write a program that does four straight turns and four turns by copying the three blocks four
  times from the right turn program. Write them all together with a start and stop.
- Now have them add a sound block that says right every time it makes a right turn
- Highlight the three blocks in right turn
- Menu Tools->My Block Builder
  - Build a block called forwardandright
  - You might need to use the wrench icon to delete previous myblocks that clash
  - Pick a custom icon
- String four of these custom blocks together from the teal block type with start and stop
- Challenge them to fix the sounds block in the no-function and function version (add another sound, change the sound)
  - Have them see how much easier this is when it is a function
- This lesson doesn't leverage parameters nor advanced match that could make turns fast and precise and configurable. That
  would be for another lesson.
  
Summary
- Use comments to help you and others.
- Use the gyro for slow, but precise turns. Remember to reset the gyro before starting.
- Use my blocks when your program has repeated actions.
