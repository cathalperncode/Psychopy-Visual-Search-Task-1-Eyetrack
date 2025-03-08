# <p align="center"> Psychopy Search Task 1 </p>
# <p align="center"> This Version Incorproates Eye Tracking using Eyelink 1000 by connecting to a wrapper code by Nick DiQuatro that you can find [here](https://github.com/ndiquattro/pylinkwrapper) </p>
## <p align="center"> Searching for a mushroom shape in an assigned context (between subjects) with either similar or distinct distractor mushrooms shapes </p>

### Paradigm Overview:
* Pseudorandomly assigns participants to 1 of 2 tagets and 1 of 2 group contexts based on a randomization excel file
* Assigns file name as TargetNumber|GroupLetter|Random5Digit#
* Runs 5 16 trial training in assigned context with assigned target that consistently phases out the presentation of the target cue. Stores Data.
* Runs 10 iterations of the 16 trial test block, in which there is pseudorandom placement of unassigned context "switch" trials and memory probe trials

### Key Functionality for Visual Search Experiments
* 4 item search trials where target is in every trial with 3 distractors (chosen from 6 possible from the assigned context). Four items are always 90 degrees apart, but jitter around locations at 0 degrees, 90 degrees, 180 degrees, and 270 degrees on screen.
* Responses are completed with button press of arrow keys, because there is always a top-most, left-most, bottom-most, and right-most position
