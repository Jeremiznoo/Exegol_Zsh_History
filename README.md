# Getting started

This repository contains the extracted .zsh_history from Exegol full images. It allows users to integrate the command history into other Linux distributions, including an updated version with more additional history commands.

# Installation

Clone the repository:

```
git clone https://github.com/Jeremiznoo/Updated_Exegol_Zsh_History/
cd Updated_Exegol_Zsh_History/
```
# Applying the History


To append the extracted history to your existing .zsh_history, use:

```
cat zsh_history >> ~/.zsh_history
```

if you are on kali linux, use this command : 

```
cat zsh_history_for_kali >> ~/.zsh_history
```

Then, reload the history for the current session:

```
fc -R ~/.zsh_history
```

# Notes

- The only differences with the Kali Linux version modifies the syntax of certain utilities, such as Impacket tools.
- If you face any issues, ensure that Zsh is your default shell (echo $SHELL).
