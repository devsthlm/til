# Setting git variables

## Problem

I want to have a repo with different credentials than others.

## Solution

Set settings globally with the ```--global``` flag.

```git config --global user.name "my name"```  
```git config --global user.email "my.name@email.com"```  

and then overrun them locally in a repo by not using the global flag.

```git config user.name "my other name"```  
```git config user.email "my.other.name@email.com"```  

## git variables to set

Set editor and wait for editor to return (i.e. for you to write a commit message and save)
```git config --global core.editor "code --wait"```

Edit variables in your editor
```git config --global core.editor "code --wait"```
