
If you're not already, please go into the checkpoint_4 directory.

    Please use markdown formatting listing the command(s) you ran to accomplish this

Remove everything in the foo directory using one command

   `rm -rf foo/*`

The following questions are about the file color_preferences.txt.

How many lines are there?
    
   `This can be done using two ways`
   `1: grep -c $ ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/checkpoint_4/color_preferences.txt`
   `2: wc -l color_preferences.txt`
    
   `ANSWER : 1000`
How many teenagers are there?

   `grep -c 1[0-19] color_preferences.txt`
   `ANSWER: 157`
    
Copy the lines from color_preferences.txt to a file called teens.txt, but only include the lines where their age is 13-19.
    
   `egrep 1[0-19] color_preferences.txt > teens.txt`
        
How many teenagers like the color purple?
    
   `grep -ic purple teens.txt`
   `ANSWER: 9`
    
    
