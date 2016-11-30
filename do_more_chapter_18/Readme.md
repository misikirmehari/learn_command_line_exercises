
# Chapter 18: Looking inside files (grep)

## Do More

### Use quotes to find "new file" and "old file" and "This is".

   `grep "new file " *.txt`
   `newtest.txt:This is a new file`
   `newtest.txt:this is a new file`
   `newtest.txt:this is a new file`
   
   `grep "old file " *.txt`
   `oldtest.txt:this is an old file`
   `oldtest.txt:this is an old file`
   `oldtest.txt:this is an old file`
   `oldtest.txt:this is an old file`
   
   `grep "This is " *.txt`
   `newtest.txt:This is a new file`

### Take the list of videos you created (or any other list) and use it to find some videos you want to find.

    `grep -i git *.mp4` : this didnot work for me tho

### Unix: You can use -i to ignore case with grep. Try grep -i new *.txt

  `grep -i new *.txt`
  `newtest.txt:This is a new file`
  `newtest.txt:this is a new file`
  `newtest.txt:this is a new file`
  `newtest.txt:this is a new file`
