# Spacemacs Setup Instructions #
  * Setup Spacesmacs for your OS by following the instructions at https://www.spacemacs.org/
  * Copy the `.spacemacs` file from this repo to your home directory
  * **Important Note** I run on the develop branch of Spacemacs. I've been doing this for years without an issue. If you decide to run on stable my config may or may not work for you!
    * To use the develop branch:
      * `cd ~/.emacs.d/`
      * `git co origin/develop`
    * Auto-update / new version checking is disabled when on the develop branch. To update:
      * `cd ~/.emacs.d`
      * `git tag #{date "+%Y-%m-%d"}` (makes it easy to revert if the recent changes were to hose your environment)
      * `git co origin/develop`

# Tips #
  * Commands in Sapcemacs are arranged mnemonically and are well organized and easily discover-able. 
    * Hitting `space` will show you the root commands, 
    * Hitting `,` shows the command related to the current major mode (id. Ruby)
  * Vim compatibility is **very** good. Many things you might not expect to work will work (NORM!)
  * You can extend the functionality by adding configuration layers
    * [Configuation Layer Introduction](https://www.spacemacs.org/doc/LAYERS.html) 
    * [List of Configuration Layers](https://www.spacemacs.org/layers/LAYERS.html) 
    * You can search for a particular layer's help in Emacs by hitting `space`, `h`, `l` (spacemacs -> help -> layers)
  * elsip is pretty easy to get the hang of and it's turtles most of the way down so it's good to know (ie. most of emacs is implemented in elisp functions you can view and even alter during runtime)
    * [Intro to Elisp](https://www.gnu.org/software/emacs/manual/html_node/eintr/) 
    * There's an associated `describe-something` function where something can be a key press, function/command or even theme, that will allow you to view it's documentation and source code.
  * Pressing `space`, `space` will allow you to search and run any emacs command
