
# Chapter 8: Moving around (pushd, popd)

## Do More

### Use these commands to move around directories all over your computer.

> I created a history/list of directories I'm going into using pushd:
`pushd ~/workspace/davinci_coders_t3_2016`, 
...coders_t3_2016 Drew$ `pushd ~/documents`, 
...documents Drew$ `pushd ~/pictures`, 

> Then popd to go into last working directory/pop current directory off the stack:
...pictures Drew$ `popd`,
...documents Drew$ `popd`,
...coders_t3_2016 Drew$
    
### Remove the i/like/icecream directories and make your own, then move around in them.

> To remove i/like/icecream all at once I used the -p option:
`rmdir -p i/like/icecream` then made a made my own,
`mkdir -p the/levels/go/deeper/into/the/abyss/yo`

>`temp Drew$ pushd the/levels/go`, 
>`go Drew$ pushd deeper/into/the/abyss/yo/`,
>`yo Drew$ popd`,
>`go Drew$ popd`,
>`temp Drew$` 

> And I'm back to temp!
    
### Explain to yourself the output that pushd and popd print out to you. Notice how it works like a stack?

> I like to think of `pushd` as a lets move into the next directory but save a trail of crumbs
> to find my way back to the last one. It's like cd but with an added rewind feature.
> The output of `pushd` shows you that temporary list you can rewind through. 

> I like to think of `popd` as the rewinding command through the created crumb trail. 
> It backtracks to the last directory in the stack and pops the current one off of the list.

### You already know this, but remember that mkdir -p will make an entire path even if all the directories don't exist. 
### That's what I did very first for this exercise.

> `-p` option also works for rmdir I quickly discovered.
    
