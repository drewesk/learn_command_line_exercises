
# Chapter 9: Making Empty Files (Touch)

## Do More

### Make a directory, change to it, and then make a file in it. 
### Then change one level up and run the rmdir command in this directory. 
### You should get an error. Try to understand why you got this error.

> First I created a directory from `~/temp Drew$ mkdir touch`,
> Then `$ ls`... `{tempdir} {othertempdir} touch`,
> Then changed into it `cd touch`,
> The created a file called touch.txt using the touch command.
> `$ touch touch.txt`,
> Moved back up one level `cd ..`,
> then attempted to remove the touch directory.
> `$ rmdir touch`,
> got the error: `rmdir: touch/: Directory not empty`.
> My understanding is that you cannot remove a directory containing a file and that you need to `rm` touch.txt.
> Hopefully I will learn a better way in future lessons.

