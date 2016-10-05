
If you're not already, please go into the checkpoint_2 directory.

> chapter_10 Drew$ `cd ../checkpoint_2`
> checkpoint_2 Drew$

Remove the foo/bar/baz directory (do not use cd here...)
    
> checkpoint_2 Drew$ `rmdir -p foo/bar/baz/`
> checkpoint_2 Drew$ `ls foo/bar/`
> `file1.txt`
        
Create an empty file named file2.txt
        
> checkpoint_2 Drew$ `touch file2.txt`
> checkpoint_2 Drew$ `ls`
> `Readme.md file2.txt foo`
            
Let's copy foo/bar/file1.txt to foo/some_other_file.txt

> checkpoint_2 Drew$ `cp foo/bar/file1.txt foo/some_other_file.txt`
> checkpoint_2 Drew$ `ls foo`
> `bar some_other_file.txt`
