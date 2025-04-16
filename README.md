## Program

This repository contains materials for the introductory workshop on Julia for spatial analysis.

The programme will be as follows:

| What | When |
| -------- | ------- |
| Help with installing Julia (maybe coffee/tea?)  | 09:00-09:30 |
| Basic Julia lecture (notebook 1) | 09:30-10:30 |
| Basic Julia excercises and break | 10:30-11:00 |
| Spatial analysis in Julia (notebook 2) | 11:00-12:00 |
| Spatial analysis excercises and break | 12:00-12:30 |
| Spatial analysis lecture contined | 12:30-13:00 |
| **BREAK FOR LUNCH** | 13:00-14:00 |
| Optional: more advanced Julia + work on your own problems | 14:00-17:00 |

I will upload the notebooks in this workshop to Google Colab, so you can run them in you browser without installing Julia.

However, installing Julia on your computer is recommended if you are interested in continuing to use it.

### Installing Julia

To participate in this workshop, we recommend that you follow these steps to get started with a Julia programming environment:

0. **Clone this GitHub repository.** This contains the Jupyter notebooks that we will use for the tutorials, the exercise solutions, and the installation script.
1. **Install Julia.** We recommend to use the [`juliaup`](https://github.com/JuliaLang/juliaup) command line tool for installing and managing Julia, but you can use whatever means you want. After installing Julia, you can launch it, which will launch the REPL (read-evaluate-print-loop) environment where you can immediately start coding and running Julia in.
2. **Install VSCode.** We recommend [VSCode](https://code.visualstudio.com/) as the environment to code and run Julia in, because it has an integrated text editor and a REPL console, it can run Jupyter notebooks out of the box, and has high quality debugging tooling.
3. **Install the Julia for VSCode extension.** To do this, open VSCode, go to Extensions, search for `Julia` and install. Once this is done, you should be able to run Julia within VSCode without any further configuration. Examples of what is possible:
   1. A console for Julia which you can get by typing `Alt+J, Alt+O` in VSCode.
   2. Using Julia in a scripting environment in VSCode. When working on a Julia script (a `.jl` text file) you may evaluate any amount of code in the script interactively. E.g., `Ctrl+Enter` evaluates current line being edited. The Julia process that evaluates the script is the same as the one in the console you get in point 1. **The Julia console and the text editor window are linked!**
   3. You can open Jupyter notebooks without installing anything else. Simply drag+drop the notebook into VSCode and it will request a "kernel" (choose Julia).  Each Jupyter notebook launches a dedicated Julia process, so the Jupyter notebooks are not linked with the standard text editor and Julia console of VSCode!