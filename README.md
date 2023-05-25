# terminal-settings
This stores all of my terminal settings (Windows / Linux).

# Fonts

The font I use for this terminal is available here and needs to be installed first:

https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.1/JetBrainsMono.zip

These fonts were found through https://www.nerdfonts.com

# starship.toml

This file is the customization settings file for the starship prompt (https://starship.rs).
These settings work across any OS that the starship prompt supports.
The starship.toml file should be put in ~/.config/
Check the website for adding the prompt to your specific shell.

# settings.json

This file contains the default profile customization settings for Windows Terminal.
Use this as a template to replace the relevant profiles:defaults: for the Windows Terminal
settings.json file.

# Microsoft.PowerShell_profile.ps1

This file contains the PowerShell Profile settings. This one includes settings for Chocolatey as well as the starship prompt.
This file should be located at %USERPROFILE%\Documents\WindowsPowerShell\.

# .bashrc

This is my .bashrc file for bash.
The only changes are to set nano as my default editor and to have starship as my default prompt.