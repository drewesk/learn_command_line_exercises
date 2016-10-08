
If you're not already, please go into the checkpoint_3 directory.

> `Drew$ cd ~/w<tab>/d<tab_c<tab>/learn_<tab>/checkpoint_3`

Can you rename foo/bar/file1.txt to foo/blah.txt?

> `checkpoint_3 Drew$ mv foo/bar/file1.txt foo/blah.txt`
> `checkpoint_3 Drew$ ls foo`
> `blah.txt  bar/`
> `checkpoint_3 Drew$ ls f<tab>/b<tab>/`
> `baz/`
    
Let's make a copy of foo/blah.txt and put it in the foo/bar/baz directory.

> `checkpoint_3 Drew$ cp foo/blah.txt foo/bar/baz/`
> `checkpoint_3 Drew$ ls foo/bar/baz/`
> `blah.txt`

What happens if you touch an existing file. 

> You can't use `touch`, which is a way to create a blank file, to run on an existing file.

Can you copy the foo/blah.txt file to slash temp?

> `checkpoint_3 Drew$ cp foo/blah.txt ~/temp/` (all of my directories in commands have / at the end due to using autocomplete)
> `ls ~/temp/`
> `blah.txt ... ... ...`

Can you copy .bash_profile in your home directory to the current directory? (Do not use cd here...)

> `checkpoint_3 Drew$ chmod 755 ~/.bash_profile`
> `checkpoint_3 Drew$ cp ~/.bash_profile ../checkpoint_3/`
> `checkpoint_3 Drew$ open .bash_profile`
> Success!

What's in foo/blah.txt?

> `checkpoint_3 Drew$ cat foo/blah.txt`
> All lines each with the string "This is line" + "{line #}" with {line#}
> correlating to all of the numbers in order from 1...5000.
    
Can you show me what's in foo/blah.txt one page at a time?

> `checkpoint_3 Drew$ more foo/blah.txt`
> I used the <spacebar> to scroll down each page at a time.
> `q` to quit.
