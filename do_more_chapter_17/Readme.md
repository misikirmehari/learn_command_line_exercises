
# Chapter 17: Finding files (find)

## Do More

### Unix: Get your find index card and add this to the description side: "find STARTDIR -name WILDCARD -print". Next time you drill make sure you can say that phrase so you remember how find is formatted.

    Please use markdown formatting listing the command(s) you ran to accomplish this

### You can put any directory where the . (dot) is. Try another directory to start your search there.

   `find ~ -name "*.docx" -print|cat`
   `find ~ -name "wordpress_intro.pptx" -print|cat`
   `/Users/misikirmehari/Desktop/building_the_toolbelt_t2_2016/presentations/wordpress_intro.pptx`
   `/Users/misikirmehari/Desktop/wordpress_intro.pptx`
   `/Users/misikirmehari/workspace/davinci_coders_t2_2016/building_the_toolbelt_t2_2016/presentations/wordpress_intro.pptx`
   
   `find ~/workspace/davinci_coders_t2_2016/ -name "*.pptx" -print | less`
   

### Look for all the video files on your computer starting at the home drive and use the > to save the list to a file. Remember how you can do SOMECOMMAND > SOMEFILE.txt and it will write the output of SOMECOMMAND to the file SOMEFILE.txt?
    
   `find ~ -name "*.mp4" -print > videofiles.txt`
