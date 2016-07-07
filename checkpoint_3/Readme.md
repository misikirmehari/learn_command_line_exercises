
If you're not already, please go into the checkpoint_3 directory.

   `pwd`
   `/Users/misikirmehari/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/checkpoint_3`

Can you rename foo/bar/file1.txt to foo/blah.txt?

   `mv foo/bar/file1.txt  foo/blah.txt`
    
Let's make a copy of foo/blah.txt and put it in the foo/bar/baz directory.

   `cp foo/blah.txt  foo/bar/baz/`

What happens if you touch an existing file. (Hint:  The answer is not nothing...)

   `changes the time stamps on existing files and directories`
    `ls -t`
    `testfile.txt Readme.md    foo`
    `touch Readme.md`
    `ls -t`
    `Readme.md    testfile.txt foo`

Can you copy the foo/blah.txt file to slash temp?

   `cp foo/blah.txt  /temp`
   `cp: /temp: Permission denied`
   

Can you copy .bash_profile in your home directory to the current directory? (Do not use cd here...)
  
  `yes`
  `cp ~/.bash_profile ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/checkpoint_3/`

What's in foo/blah.txt?
   `cat foo/blah.txt`
   `This is line 1 . . . This is line 5000`
    
Can you show me what's in foo/blah.txt one page at a time?
   `less foo/blah.txt`
   `Then press SPACE to move through the page and press q to quit`
