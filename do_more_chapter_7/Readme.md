
# Chapter 7: Remove Directory (rmdir)

## Do More

### Make 20 more directories and remove them all.

   `mkdir test`
   `rmdir test`
   `mkdir test1`
   `rmdir test1`
   `mkdir test2`
   `rmdir test2`
   `mkdir test3`
   `rmdir test3`
   `mkdir test4`
   `rmdir test4`
   `mkdir test5`
   `rmdir test5`
   `mkdir test6`
   `rmdir test6`
   `mkdir test7`
   `rmdir test7`
   `mkdir test8`
   `rmdir test8`
   `mkdir test9`
   `rmdir test9`
   `mkdir test10`
   `rmdir test10`
   `mkdir test11`
   `rmdir test11`
   `mkdir test12`
   `rmdir test12`
   `mkdir test13`
   `rmdir test13`
   `mkdir test14`
   `rmdir test14`
   `mkdir test15`
   `rmdir test15`
   `mkdir test16`
   `rmdir test16`
   `mkdir test17`
   `rmdir test17`
   `mkdir test18`
   `rmdir test18`
   `mkdir test19`
   `rmdir test19`
   `mkdir test20`
   `rmdir test20`
                                                               

### Make a single path of directories that is 10 deep and remove them one at a time just like I did above.

   `mkdir -p test1/test2/test3/test4/test5/test6/test7/test8/test9/test10`
   `cd test1/test2/test3/test4/test5/test6/test7/test8/test9/`
   `rmdir test10`
   `cd ..`
   `rmdir test9/`
   `cd ..`
   `rmdir test8/`
   `cd ..`
   `rmdir test7/`
   `cd ..`
   `rmdir test6/`
   `cd ..`
   `rmdir test5/`
   `cd ..`
   `rmdir test4/`
   `cd ..`
   `rmdir test3/`
   `cd ..`
   `rmdir test2/`
   `cd ..`
   `rmdir test1/`
   
   

### If you try to remove a directory with contents you will get an error. I'll show you how to remove these in later exercises.

    Please use markdown formatting listing the command(s) you ran to accomplish this
        
