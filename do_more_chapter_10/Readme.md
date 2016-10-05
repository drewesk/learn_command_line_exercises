
# Chapter 10: Copy a file (cp)

## Do More
> ***NOTE***: The answers for this chapter should not include the use of cd (change directory).

### Use the cp -r command to copy more directories with files in them.

> temp Drew$ `mkdir something`, `cp awesome.txt something/`
> temp Drew$ `cp -r something newplace`,
> temp Drew$ `cp -r newplace newestplace`
> temp Drew$ `ls newestplace/`,
> Output: `awesome.txt`, Yay!

### Copy a file to your home directory or desktop.

> awesome.txt is a previously created file 
> temp Drew$ `cp awesome.txt ~/desktop`
> It's on my desktop, Yay!
    
### Find these files in your graphical user interface and open them in a text editor.

    I opened finder, and clicked on awesome.txt on my desktop. The file opened in the default text editor. 
    
### Notice how sometimes I put a / (slash) at the end of a directory? 
### That makes sure the file is really a directory, so if the directory doesn't exist I'll get an error.
    
