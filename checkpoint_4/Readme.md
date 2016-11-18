
If you're not already, please go into the checkpoint_4 directory.

> `chapter_20 Drew$ cd ../checkpoint_4/`
> `checkpoint_4 Drew$`

Remove everything in the foo directory using one command

> `rm -rf foo/`
> `ls`
> `Readme.md   color_preferences.txt`, `foo` dir is long gone!

The following questions are about the file color_preferences.txt.

How many lines are there?

> `wc -l color_preferences.txt`, `-l` is the line count option for the word count command.
> `1000 color_preferences.txt` There are 1000 total lines.

How many teenagers are there?

> `grep -e 1[3-9] color_preferences.txt | wc -l` 
Piped the output of the list to the word count command with `-l`.
> `320` is the output.
    
Copy the lines from color_preferences.txt to a file called teens.txt, but only include the lines where their age is 13-19.
    
> `grep -e 1[3-9] color_preferences.txt > teens.txt`, directed the output to `teens.txt`.
> `ls`
> `Readme.md		color_preferences.txt	 teens.txt`
       
How many teenagers like the color purple?

> `grep -e purple teens.txt | wc -l`
> `14`, output of piping the grep -e search with keyword purple to the word count line option.     
