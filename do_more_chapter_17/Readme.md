
# Chapter 17: Finding files (find)

## Do More

### Unix: Get your find index card and add this to the description side: "find STARTDIR -name WILDCARD -print". Next time you drill make sure you can say that phrase so you remember how find is formatted.

> Created a real flashcard.

### You can put any directory where the . (dot) is. Try another directory to start your search there.

> `find ~ -name "*ocuments" -print`
> All files containing "ocuments" in the home directory were printed to the screen.

### Look for all the video files on your computer starting at the home drive and use the > to save the list to a file. Remember how you can do SOMECOMMAND > SOMEFILE.txt and it will write the output of SOMECOMMAND to the file SOMEFILE.txt?

> `chapter_17 Drew$ find ~ -name "*.mp4" -print > ~/temp/file1.txt`
> `chapter_17 Drew$ open ~/temp`   
> All search items are in file1.txt
