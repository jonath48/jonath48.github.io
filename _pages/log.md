---
layout: default
title: Jonathan Thompson's IMMERSE Log
---

### May - August 2022

* **Summary:** Worked with Hayden Cook to setup and run experiments to spoof ROPUFs. Assisted in the submission of ROPUF spoof paper to FPT Conference. Worked with Zephram Tripp on the characterization of ROPUFs on the Arty A7 and Ultra96 v2 boards. Used the characterization data to analyze the effectivity of the ROPUFs in terms of uniqueness, reliability, uniformity, bit-aliasing, and diverseness. Tried different methods of comparing ROs within the PUFs and compared results between the methods. Started working on equivalency checking on the bfasst project.

### April 2022

* **Summary:** Started working with Hayden to create ROPUFs for more short experiments.

### January 2022

* **Summary:** Created more plots to visualize the data from the current tests that were run. Made a power point to relate results.

### November/December

* **Summary:** Set up project to allow for the recording of current used by board while running voting shorts. Began to run test collecting data. Plotted first small set of data collected from first test experiment. Created plots with the minimum, maximum, and mean of the current of each test.

### October

* **Summary:** Collected the data from the tests run and made some diagrams and tables for the data. Read Ken Zick's paper on LUT burn in https://ieeexplore.ieee.org/document/6927475

### September

* **Summary:** Ran test using ground and VCC as the inputs to the bels of the voting short modules.

### Week 19: August 30, 2021 - September 3, 2021

* **Summary**: Continued to run tests and collect data.

### Week 18: August 23, 2021 - August 27, 2021

* **Monday**: Didn't work.
* **Tuesday**: Continued testing and collecting data.
* **Wednesday**: Didn't work.
* **Thursday**: Went to weekly FPGA aging meeting. Put together the stats of the test run so far. 
* **Friday**: Started testing and collecting data on another board. On the ARTY A7 board #3.

### Week 17: August 16, 2021 - August 20, 2021

* **Monday**: Worked on setting up the automation of creating checkpoint and bitstream files for the testing of voting shorts with GND and VCC as input signals and then tested them.
* **Tuesday**: Continued testing of files created.
* **Wednesday**: Didn't work.
* **Thursday**: Didn't work.
* **Friday**: Didn't work.

### Week 16: August 9, 2021 - August 13, 2021

* **Monday**: Out sick with COVID (Didn't work)
* **Tuesday**: Out sick with COVID (Didn't work)
* **Wednesday**: Out sick with COVID (Didn't work)
* **Thursday**: Out sick with COVID (Didn't work)
* **Friday**: Out sick with COVID (Didn't work)

### Week 15: August 2, 2021 - August 6, 2021

* **Monday**: Worked on using the custom router in RapidWright. 
* **Tuesday**: Got the custom router to work. Looked at some of the irregularities.
* **Wednesday**: continued working on the custom router results.
* **Thursday**: Started trying to use GND and VCC as inputs to the voting shorts instead of signals supplied by an arduino.
* **Friday**: Worked on setting up computer at home and started to work on using GND and VCC to power the inputs of the voting shorts.

### Week 14: July 26, 2021 - July 30, 2021

* **Monday**: Vacation (Didn't work)
* **Tuesday**: Continued to work on getting lights to work with shorts. Started working with a smaller portion of the board to see if it's the amount of shorts causing lights to not work.
* **Wednesday**: Went to breakout room meeting. Got the lights to work and started to focus on getting shorts to output the right values.
* **Thursday**: I found the voting shorts were taking odd routes which could be one reason the outputs are incorrect.
* **Friday**: I continued to try and correct the routing by using the router and router tools found in RapidWright. 

### Week 13: July 19, 2021 - July 23, 2021

* **Monday**: Vacation (Didn't work)
* **Tuesday**: Vacation (Didn't work)
* **Wednesday**: Vacation (Didn't work)
* **Thursday**: Vacation (Didn't work)
* **Friday**: Vacation (Didn't work)

### Week 12: July 12, 2021 - July 16, 2021

* **Monday**: Worked on getting the voting short checkpoint to not having overlapping nodes.
* **Tuesday**: Continued to work on the overlapping nodes issue.
* **Wednesday**: I was out sick. I did not work.
* **Thursday**: Continued to work on getting lights to work.
* **Friday**: Vacation (Didn't work)

### Week 11: July 5, 2021 - July 9, 2021

* **Monday**: Celebrated Independence day. I didn't work
* **Tuesday**: Chip Camp Counselor.
* **Wednesday**: Chip Camp Counselor.
* **Thursday**: Chip Camp Counselor.
* **Friday**: Worked on making a checkpoint that will light up the LEDs on the FPGA to make debugging easier. 

### Week 10: June 28, 2021 - July 2, 2021

* **Monday**: Worked on making a checkpoint that sends the inputs to LEDs to make it easier to debug. Went to chip camp meeting and prepared for chip camp.
* **Tuesday**: Chip Camp Counselor.
* **Wednesday**: Chip Camp Counselor.
* **Thursday**: Chip Camp Counselor.
* **Friday**: Worked on Hooking up LEDs for debugging purposes.

### Week 9: June 21, 2021

* **Monday**: Worked on routing the 5 way voting shorts. Went to bootcamp meeting.
* **Tuesday**: Worked on finding better nodes to route through to decrease the number of hops needed while routing.
* **Wednesday**: I continued to work and test differently routed checkpoints and testing on different boards. Went to Immerse, Broader Impact, and Bootcamp meeting.
* **Thursday**: Went to FPGA Aging meeting. Worked on redoing the routing on the voting shorts. Worked on improving the quality of the code used to run the voting shorts experiments.   
* **Friday**: Worked on improving arduino code and voting shorts experiment code. Started trying to add LEDs to voting short checkpoint to allow easy verification of correct inputs.

### Week 8: June 14, 2021

* **Monday**: Worked on Immerse powerpoint. Worked on getting experiment to work properly
* **Tuesday**: Worked on getting voting short experiment to work and made graphs from data found. Worked on IMMERSE presentation.
* **Wednesday**: Fixed some of the graphs of the voting short experiments. Finished IMMERSE presentation powerpoint. Went to IMMERSE, broader impact, and short circuit meetings.
* **Thursday**: Worked on getting code cleaned up and merge into github shorty repo. Started trying to use router to route the voting shorts differently.
* **Friday**: Worked on getting the router to work.

### Week 7: June 7, 2021

* **Monday**: Worked on getting the 5 way voting checkpoint set up properly. Started working on coding arduino for doing voting shorts experiments. Went to bootcamp meeting with guest speaker Tim Ansell.
* **Tuesday**: Worked on coding arduino for voting shorts experiments.
* **Wednesday**: Went to SHREC workshop, Immerse meetings, and Bootcamp meetings. Worked on getting the arduino set up.
* **Thursday**: Went to FPGA aging meeting. Got arduino to work and started to get the arduino to work together with other files made earlier.
* **Friday**: Worked on getting arduino work with FPGA. Worked on Immerse presentation.

### Week 6: May 31, 2021

* **Monday**: Memorial day I did not work.
* **Tuesday**: Home for Grandfather's funeral. I did not work.
* **Wednesday**: Home for Grandfather's funeral. I did not work.
* **Thursday**: Home for Grandfather's funeral. I did not work.
* **Friday**: Home for Grandfather's funeral. I did not work.

### Week 5: May 24, 2021

* **Monday**: Worked on getting readback to work with the checkpoint of voting shorts on all the even row tiles on the board. Went to the FPGA deep dive Bootcamp meeting. Worked on setting up a vnc.
* **Tuesday**: Got X11 forwarding to work to allow remote work. Figured out how to use readback with the checkpoints that have voting shorts on the entire board. Used readback to get the output of all the voting shorts for each possible input for the 6 way voting shorts. Started working on displaying data in graph form.
* **Wednesday**: Worked on creating graphs to display the data on the outputs of the voting shorts. Went to Immerse and Bootcamp meetings. 
* **Thursday**: Finished making the graphs about the voting shorts outputs. Went to FPGA aging meeting. 
* **Friday**: Worked on selfpaced Bootcamp FPGA tcl activities and started making a new voting short bitstream.

### Week 4: May 17, 2021

* **Monday**: Got readback to work properly with voting shorts. Started modifying the existing readback parser file for our projects needs. Went to bootcamp meeting.
* **Tuesday**: Worked on writing tcl file to open vivado and create readback file. Wrote Immerse Proposal paper. Applied information taught in bootcamp by working on CVS_Parser. 
* **Wednesday**: Went to Immerse and Bootcamp meetings. Worked on writing a script for voting shorts. Started making a checkpoint file with voting shorts across the entire board.
* **Thursday**: Went to FPGA aging meeting. Worked on creating a checkpoint with voting shorts on the entire board.
* **Friday**: Worked on getting checkpoint of all voting shorts. Went to bootcamp meeting on docker. Worked on setting up computer for remote work.

### Week 3: May 10, 2021

* **Monday**: Worked on broader impact group project of helping to make a new lab for ECEn 301. Worked on getting the clock to connect to two sites in the same tile. Went to bootcamp class on python.
* **Tuesday**: Figured out how to connect the clock to the two sites within the same tile. Started reading up on readback. Made some adjustments to my website.
* **Wednesday**: Went to Immerse and bootcamp meetings. Practiced using python and learned how to setup and use venv and miniconda. Started trying to get readback to work with the voting shorts.
* **Thursday**: Worked on getting readback to work properly. Went to FPGA aging meeting.
* **Friday**: Worked on connecting readback to voting shorts. Went to bootcamp meeting about python packages.

### Week 2: May 3, 2021

* **Monday**: Worked on making voting shorts in one site and voting shorts in two sites on the same tile.
* **Tuesday**: Made a voting short with four signals and checked all possible outcomes.
* **Wednesday**: Worked on connecting a flip flop to the clock. Went to Immerse presentations and meetings as well as the bootcamp meeting on Make.
* **Thursday**: Figured out how to connect the clock to a flip flop. Started working on connecting switches to the inputs of a voting short.
* **Friday**: Worked on connecting switches to the inputs of voting shorts and creating functions that will work with shorts containing 2-6 signals. Went to bootcamp class on CMake.

### Week 1: April 26, 2021

* **Monday**: Linux Tutorial and Computer and Website setup.
* **Tuesday**: Read accelerated FPGA Aging Article and RapidWright Docs. Added immerse log link to bootcamp site. Started RapidWright Setup.
* **Wednesday**: Practiced using RapidWright and Vivado together on Lesson1 example. Went to Immerse meetings. Met with Broader Impact group.
* **Thursday**: Practiced git and set up and practiced RapidWright.
* **Friday**: Practiced creating shorts using RapidWright and programming them to an FPGA. 