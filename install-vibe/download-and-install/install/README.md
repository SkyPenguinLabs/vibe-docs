---
description: Shell (install.sh) script for installing VIBE systemwide/userwide/etc.
---

# Install

Before we get started, we have to install the language we have downloaded. After you download the repository, and are in your terminal inside of the working directory of vibe, go ahead and run that install script!

```
./install.sh
```

This will walk you throgh the install wizard.

#### Example output from wizard

***

```
[test@test/vibe]$ ./install.sh 

| [Environment] | 20:19:54
[20:19:54] INFO  starting interactive setup for vibe
[20:19:54] WARN  existing vibe found on PATH: /home/...../.local/bin/vibe
Install artifact mode (prebuilt/source) [prebuilt]:       
Install scope (user/system/custom) [user]: 
Command name to install [vibe]: 
Release version tag [latest]: 
Write a toolchain config preset? [Y/n] 
Config preset (minimal/default/dev) [default]: 
Environment integration (none/path/full) [full]: 
Bash profile file [/home/..../.bashrc]: 
Install bash completion? [Y/n] 

| [Plan] | 20:20:06
...... restated inputs for verification checking 
```

#### Advanced Configuration

***

The install script has some cool advancements to it! Check it out on the next page.
