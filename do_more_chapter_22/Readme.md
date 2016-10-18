
# Chapter 22: Changing Environment Variables (export)

## Do More

### Take and list out all the environment variables you've found and then go look up what they are online (please do 5-10 or so).

> `er_22 Drew$ env`

> ```__CF_USER_TEXT_ENCODING, _system_arch, _system_name, _system_type, _system_version, 
> Apple_PubSub_Socket_Render, GEM_HOME, GEM_PATH, HOME, IRBRC, ITERM_PROFILE, ITERM_SESSION_ID,
> LANG, LOGNAME, MY_RUBY_HOME, OLDPWD, OSX, PATH, PWD, RUBY_VERSION, rvm_bin_path, rvm_path, 
> rvm_prefix, rvm_version, SHELL, SHLVL, SSH_AUTH_SOCK, TERM, TERM_PROGRAM, TERM_PROGRAM_VERSION, 
> TERM_SESSION_ID, TMPDIR, USER, XPC_FLAGS, XPC_SERVICE_NAME```

> I researched 10 easy variables.

> `TERM_PROGRAM` is variable for the application being used to run commands(ex/iTerm2).
> `IRBRC` is the configuration variable for interactive ruby.
> `USER` is the current user name within the operating system.
> `SHELL` is the location of shell settings in bin/bash or whatever you set it to.
> `rvm_path` is the location of RVM.
> `PWD` is the current working directory.
> `PATH` is the location of a set of directories filled with settings for executing certain processes. 
> `OSX` is the operating system.
> `LANG` is the keyboard language setting.
> `OLDPWD` is the last visited working directory.

### Read the man page for env again. What else can it do?

> man def: set environment and execute command, or print environment
> env allows me to view current variable settings, 
> potentially modify the set value,
> and therefore update the settings/see current env status info.

