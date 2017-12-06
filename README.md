Steps to setup your terminal

1. Install prezto following the steps in the main documentation

   https://github.com/sorin-ionescu/prezto

2. Import Tomorrow Night theme in the Terminal preferences (Get file from this repository)

3. Copy prompt_monkey_setup file to ~/.zprezto/modules/prmopt/functions/

4. Edit file ~/.zprezto/runcoms/zpreztorc

   On line 35 after 'prompt' add 'git'
    
    It should look like this:
   'prompt' \
   'git'

   Change line 89 changing "sorin" by "monkey"
   -zstyle ':prezto:module:prompt' theme 'sorin'
   +zstyle ':prezto:module:prompt' theme 'monkey'

5. Install powerline fonts from https://github.com/powerline/fonts and use DejaVu Sans Mono for Powerline on 12pt or whatever looks best for you

For meteor users
If you are developing meteor custom packages add the following export at the end of 
~/.zprezto/runcoms/zprofile

\# Define PACKAGE_DIRS for Local Meteor Packages
export METEOR_PACKAGE_DIRS="$HOME/Development/packages"

