<h1 align="center"> IWantToLearn (iwtl) </h1>
<p align="center">
Task manager for the curious procrastinator
</p>
<p align="center">
<a href="https://github.com/POeticPotatoes/iwtl/releases">
    <img src="https://img.shields.io/github/commits-since/POeticPotatoes/iwtl/latest.svg?color=green" alt="Version Badge">
</a>
</p>

    [poeticpotato@POeticPotato ~]$ iwtl complete 25
    Task: Fix iwtl and stop it from inting
    Are you sure you have completed this? [y/N]:y
    =============================================
     _________________________________________ 
    / “I find television very educational.  \
    | Every time someone turns it on, I go in |
    | the other room and read a book.’      |
    \ ―Groucho Marx                         /
     ----------------------------------------- 
      \
       \   \_\_    _/_/
        \      \__/
               (oo)\_______
               (__)\       )\/\
                   ||----w |
                   ||     ||
    =============================================
    Completed task: Fix iwtl and stop it from inting
    I like this player. It played well. It did not give up.
    =============================================
    [poeticpotato@POeticPotato ~]$ iwtl random
    Here's a new task for you:
              15	There is no task. Do 20 pushups.

## About
IWantToLearn (iwtl) is a super-lightweight task manager that is designed to motivate even the laziest of people (me).

It was written because I find myself procrastinating on even the most basic of tasks during my holidays (like cleaning my room), and I use it daily for suggesting new things to learn or keeping track of my studies.

## Features
iwtl provides several simple features:
- Task tracking by ID
- A search function to find tasks
- Random task suggestions
- Funky pixel art upon task completion
- Customisable motivational messages

Learning is ultimately self-driven. The point of iwtl is to provide the user with a (randomised) framework to manage themselves when they find themselves with too many want-to-do's and too little brainspace to actually choose what to do.

## Usage

    Syntax: iwtl [add|list|random|complete|delete|find]
    options:"
    add        Add a new task to the tasklist
    list       See all existing tasks and taskids
    random     Get a random task from your tasklist
    complete   Complete a task. Removes it from the tasklist
    delete     Delete a task (forever)
    find       Find a task in the tasklist

### Configuration
iwtl comes with a list of default motivational text that displays upon completion of a task (mainly taken from Julian Gough's <a href="https://minecraft.fandom.com/wiki/End_Poem">end poem</a>, among other things). This list can be overriden by creating a file `.tome` in the home directory of the user.

    cp /usr/share/iwtl/tome ~/.tome

## Notes
* The configuration file is named 'tome' not as a reference to a large scholarly paper pile, but as an allusion to the fact that it is written to motivate your future self ("to myself in the future", ie. "to me").
* I intend to create a proper Makefile for this project, and also (possibly) create some release for MacOS. (Don't worry, it's in my iwtl list).

