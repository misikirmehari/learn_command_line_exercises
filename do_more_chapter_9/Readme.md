
# Chapter 9: Making Empty Files (Touch)

## Do More

### Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.
   `mkdir temp`
   `cd temp/`
   `touch iamcool.txt`
   `cd ..`
   `rmdir temp`
   `rmdir: temp: Directory not empty`
    
   `The error was because rmdir only removes empty directories. In 
    order to delete a directory with file , one should use 
    rm -rf <directory name > and in this case temp`
    

