---
title: Virtual Environments in Anaconda
linktitle: Virtual environments in Anaconda
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
## Introduction
You can think of a virtual environment as a container for a Python project.  You can make as many virtual environments as you like (usually one per project), and assign each one a unique name.

What you'll have is a working copy of Python that's isolated from other Python environments. Each environment has separate files, directories, and paths; nothing you do in one environment will impact projects in other environments.

Why does this matter? Well, if  Project Blue expects to find a certain version of a file in a certain place, and Project Red replaces that file with a different version, Project Blue might stop working. Virtual environments make sure that doesn't happen.

## Create an environment  
The easiest way to create a virtual environment is using the conda create command:

```
conda create --name myname
```

You'd replace "myname" with the name of your virtual environment.

## Activate an environment

To enter in your virtual environment and start using it, type
```
conda activate myname
```

Of course, you will enter the actual name of your environment instead of "myname." You'll now see that (base) has been replaced with the name of your environment to indicate that it is now active.

## Deactivate your environment
You can deactivate your environment and return to base with:
```
conda deactivate
```

## Other commands
We've compiled a list of helpful commands in this post.
