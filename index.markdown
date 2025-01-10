---
layout: default
---

This page is dedicated to helping students install and use
[SageMath](https://www.sagemath.org) on their personal computers. Sage is a
powerful, free, open-source alternative to computer algebra and
visualization systems like Mathematica, Maple, and Matlab. Based on the
python programming language, it has a syntax that will be familiar to folks
with some python programming background. However, python background is not
required. Most of the major generative AIs, chatgpt, gemini, copilot, are
quite adept at generating sage commands from your natural language prompts
that you can paste into a sage cell and execute to get what you want.

You can try Sage without installing it on your personal computer using the
[cocalc.com](https://www.cocalc.com) platform. However, that platform is
pretty aggressive about getting you to pay a subscription for a better use
experience. To empower students and mathematicians, this page provides
detailed steps to setup and use SageMath on their own computers.

# Installation
The main place to learn about installing SageMath is the [Sage Installation
Guide](https://doc.sagemath.org/html/en/installation/index.html).

## macOS
The Sage Installation Guide is pretty effective and straightforward for
learning how to install Sage on your Apple mac laptop. About the only thing
to note is that in these instructions, you are asked: **Do you want to do
SageMath development?** Overwhelmingly, the answer to this question is
**No**. As a result, overwhemingly people should follow the 2nd section:
**No Development**. The rest is pretty straightforward for mac users that
have ever downloaded and installed a piece of software on their computer.

## Windows
The Sage Installation Guide is _ok_ for learning how to install Sage on
your Windows computer. However, it is quite complicated and this guide
attempts to fill in some of the gaps in the installation guide.

### WSL
The first thing to note is that in these instructions, you are asked: **Do
you want to do SageMath development?** Overwhelmingly, the answer to this
question is **No**. As a result, overwhemingly people should follow the 2nd
section: **No Development**. 

**Note:** Sage relies on the existence of the Windows Subsystem for Linux
(WSL) on your computer. As a result, you're going to need about 40Gb of
free space on your computer to install Sage. 

Follow the Sage Installation Guide through to the grey box showing you how
to activate and run sage. It's at this point that things get challenging.
You have run sage and now you're looking at 
```python
┌────────────────────────────────────────────────────────────────────┐
│ SageMath version 10.4, Release Date: 2024-07-19                    │
│ Using Python 3.11.11. Type "help()" for help.                      │
└────────────────────────────────────────────────────────────────────┘
sage:
```

### Jupyter Interface


