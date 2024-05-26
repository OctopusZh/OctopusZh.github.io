+++
title = 'How debugers work'
date = 2024-05-26T18:34:56+08:00
draft = false
tags = ["debugger"]
Description = "Introduce to linux debuggers in a simple way."
+++

`Debuger` and `Compiler` are common tools for all developers. But I notice that there was too few information about how a debuger works compared to how a compiler works.

Today, I will introduce you the principles of debuggers in linux[^1] in a simple way.

[^1]: [Writing a linux debugger](https://blog.tartanllama.xyz/writing-a-linux-debugger-setup/)

Before we start, let's remain what a debuger can do:

1. Start a new process or attach to a existing process
2. Block process's execution at any point
3. Read or write process's private data