---
title: Helpful commands for Anaconda VMs
linktitle: Helpful commands for Anaconda VMs
toc: true
type: docs
date: "2020-04-15"
draft: false
authors:
- Christopher Hoover
menu:
  GettingStarted:
    parent: Python
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---
### Create an environment using a specific version of Python
You can create a virtual environment with a specific version of python this way:
```
conda create -n myenv python=3.6
```      
<br />        
### Clone environment
You can clone an environment
```
conda create --name myclone --clone myenv
```
<br />
### List environments
What environments have you created? Find out with this:
```
conda env list
```
<br />
### List packages in an environment
To list the packages when you are inside an active environment, type this (within the environment).
```
conda list
```
<br />
### List the packages in an inactive environment
Maybe you want to see the packages in an environment you aren't currently using. Just type this (substituting the name of the environment for myenv).
```
conda list -n myenv
```
<br />
### Listing specifications of an environment
This command can be helpful to see the details about what's installed within an environment
```
conda list --explicit
```
