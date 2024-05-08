# Introduction
The VM252.circ is a logisim circuit which is a multi-clock cycle design that simulates the VM252 assembly language instructions. Please check out the `VM252MultiClockCycle.pdf` file to learn/understand how the instructions work, how the control unit works, how to write programs(encode instructions) for the computer etc. Also consult the files inside the `resources` directory as appropriate. <br><br>
This project was done as a part of my CS375( directed reading/ independed study) course at Luther College with Prof. Alan Zaring as my instructor. The hardware model is shown below:
<img width="1130" alt="image" src="https://github.com/paudsu01/Multi-Clock-Cycle-Logisim-VM252/assets/114323952/5191d76d-bcf1-4c7c-a447-7ce67347e268">
<p> The actual circuit in logisim looks like this: </p>
<img width="1100" alt="image" src="https://github.com/paudsu01/Multi-Clock-Cycle-Logisim-VM252/assets/114323952/caf9d457-f5c7-4f76-a7e4-880ce118ebf8">


# What is VM252 ?
VM252 is an exremely simple virtual computer created by Prof. Alan Zaring. Prof. Alan uses the VM252 to teach about assembly language (the VM252 assembly language) in one of his courses at Luther. This project was to create the VM252 computer in logisim. 
You can read more about the VM252 in `VM252ArchitectureSoftwareAndProgrammingInformation.pdf` file inside the `resources` folder.


# How to run programs in the VM252?

* Firstly, download [logisim](https://github.com/logisim-evolution/logisim-evolution) in your computer. It is open-source and free to use.
* Secondly, Clone the repository to get the required files or download the zip file.
Now, follow these instructions as mentioned in the guide/docs:

From `VM252MultiClockCycle.pdf` :
> * Download the VM252.circ, VM252ControlUnit if you haven’t already.
> * Open VM252.circ with logisim and navigate to the MultiClockCycleVM252 circuit which is the main circuit.
> * Initialise the Control Unit ROM if it hasn’t been initialized already. To do
so, right-click on the ROM → Select ”Load image” → Select VM252ControlUnit
> * Select a program to run as follows:
>     * You can either write your own program by modifying the VM252 memory. Make sure to properly encode instructions.
>     *  Or, you can load up some programs from the programs directory. To do so, right-click on the memory → Select ”Load image” → Select a valid program from the programs folder.
