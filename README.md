# Demo_Kathara

A use case to demonstrate the possibilities with Kathara (Network Emulation).

# What is Kathara

According to [the official website](https://kathara.org), Kathara is an open source container-based network emulation system for showing interactive demos/lessons, testing production networks in a sandbox environment, or developing new network protocols.

![credit for the framework](https://github.com/Eunnella/Demo_Kathara/blob/72143ccb74fede46a75974f0d91b514f6340528f/Images/copyright.png)

# Scenario

Hardening of a network infrastructure.

![What I wanted](https://github.com/Eunnella/Demo_Kathara/blob/main/Images/What_I_wanted.png)

# Usage

Assuming you already installed Kathara and you have docker running on your device :

- Open a terminal and go to the files directory of this project
`cd files`
- To start the project
`kathara lstart`
- To stop the project
`kathara lclean`

# Reality

I was too ambitious considering the timeframe.
Easy to understand but the GUI is nowhere to be found so I had to do it without visual representation of my work.
The configurations to avoid broadcast storms cannot be done on the switches (I think that I just don't know how to do it).
I do recommand the framework for an introduction to network infrastructures or simpler tasks on the subject.

![What I got](https://github.com/Eunnella/Demo_Kathara/blob/main/Images/what_I_got.png)