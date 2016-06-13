
# Chapter 8: Moving around (pushd, popd)

## Do More

### Use these commands to move around directories all over your computer.

   `pushd ~/workspace/davinci_coders_t2_2016/`
   `~/workspace/davinci_coders_t2_2016 ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises`
   
   `popd`
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises`
### Remove the i/like/icecream directories and make your own, then move around in them.

   `rmdir -p i/like/icecream/`
   `mkdir -p sub1/sub2/sub3`
   `pushd sub1/sub2`
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/sub1/sub2 ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises`
   `popd`
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises`
   `pushd sub1/sub2/sub3`
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/sub1/sub2/sub3 ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises`
   `popd`
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises`
   `pushd sub1/`
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/sub1 ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises`
   `pushd sub2/sub3/`
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/sub1/sub2/sub3` 
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/sub1` 
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises`
   `popd`
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/sub1 ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises`
   `popd`
   `~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises`
### Explain to yourself the output that pushd and popd print out to you. Notice how it works like a stack?
   `When a directory is pushed , it prints out the directory that was pushed 
    followed by the previous directory. It puts it in a stack`
    `When a directory is popped , the directory that is ontop of the stack gets displayed`

### You already know this, but remember that mkdir -p will make an entire path even if all the directories don't exist. That's what I did very first for this exercise.

   `mkdir -p sub1/sub2/sub3`
