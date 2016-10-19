
If you're not already, please go into the checkpoint_5 directory.

> `cd ../checkpoint5/`
> `_5 Drew$`

Show me the lines in foo.txt that have "ERROR" in them.

> `_5 Drew$ grep ERROR *foo.txt > ERROR.txt`
> The list has been passed into ERROR.txt.
    
Show me the lines in foo.txt that have "Synergistic" in them.

> `grep Synergistic *foo.txt > Synergistic.txt`
> The list has been passed into Synergistic.txt.

What does the -i option to grep accomplish?

> Ignore case sensitivity or 'performs case insensitive matching' according to man page.

What option to ls tells it to output file size in human readable form?

> `ls -lah` outputs files in HR form listing the order of size kb, mb, gb list order.
> The Readme was 2.3 kilobytes at the moment of executing the command.


What does the -r and -f options to rm do exactly?

> `-r` Removes the hirearchy of files contained levels within a directory.
> `-f` Remove without confirming permission to delete.

What does the ifconfig command do?

> `ifconfig` is used to assign an address to a network interface and configure interface params.

What is your shell set to?

> `env | grep SHELL` pipe the results of all listed env variables to the grep search.
> `SHELL=/bin/bash` voila, magic!

What directory are you in (don't use pwd this time)?

> `env | grep PWD` pipe the results of all listed env vars to the grep search.
> wizardry is upon us!

What is your home directory set to?

> `env | grep HOME` piped it to the grep search
> `HOME=/Users/Drew` 

Can you set your environment to have DEBUG set to true?

> `export DEBUG="true"`
> `echo DEBUG`
> `true`

Explain how you would change your PATH on your computer

> `export PATH=$PATH:(new dir path)` to set a new path
> `echo $PATH` to see new path

Can you remove the DEBUG environment variable?

> `unset DEBUG` This removes the variable
> `echo DEBUG` This prints the var
> ` `
> `env` It's nowhere to be found. Success!

Why is it dangerous to run "rm -rf /". DO NOT RUN THIS COMMAND. Simply explain why it's a very bad idea.

> Because a student uprooted/deleted his entire root directory!

Can you put "This class is fun" into bar.txt?

> `5 Drew$ echo "This class is fun" > bar.txt`

Can you put "Oh so much fun" into foo.txt?

> `5 Drew$ echo "Oh so much fun" > foo.txt`

Run find in the class directory, pipe the output to pbcopy and create a gist with the content.  Paste the Gist URL below.

> `find ~/workspace/davinci_coders_t3_2016/ | pbcopy` then < command > v into gist file
` Gist URL:  https://gist.github.com/drewesk/6677620f39352a5e343d16b9d145aedc `

Please logout.



