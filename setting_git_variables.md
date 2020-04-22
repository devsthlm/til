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

