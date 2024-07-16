### DAS_Healthcare16July2024
This is the matlab simulation code which contains the Matlab code and data files for simulating a VFC-enabled infrastructure. The simulation uses greedy-heuristic approach based solution termed as "Divide and Schedule (DAS)" and four other resource allocation and schedueling methods.
### Step 1: To compare the response latencies by the five different resource allocation and schedueling methods, ranging from MACTER, FVNET, LFT, SFT, BSM, and DAS, we used the following matlab data(.mat) and script (.m) files:
1) workspace27Sep2023PDFAllmethodsV5.mat           % It is the matlab data file to initialize the VFC-enabled infrastructure variables and parameters
2) AllinOne27Sep2023DAS.m     (averages)                     % This is the matlab file that simulates the DAS resource allocation and task schedueling method. These simulations give us a probable and approximate values of response latencies. <br/>
                                                   % These achieved response latencies are then recorded in an excel sheet. <br/>
                                                   % THe record in excel sheets are then used to plot the response latencies versus tasks.... <br/>
3) AllinOne10July2024MinMinversionV6_DAS.m (averages_Max)           % The phrase within small brackets is the name of variable/parameter which is used to hold the final response latencies for SFT method
4) Allinone10July2024MaxMax_RespLatency_DAS.m (TotalTRespMinMax1)    % The phrase within small brackets is the name of variable/parameter which is used to hold the final response latencies for LFT method 
5) AllinOne10July2024BSMversionV5_DAS.m   (averages_FCFS)             % The phrase within small brackets is the name of variable/parameter which is used to hold the final response latencies for BSM method
                                                                      % For obtaining the response latencies for MACTER, and FVNET methods, we have used the values shared by their developers during the analysis section of the published work. 
### Step 2: We ploted the Probabililty Density Function (PDF) using the above obtained values of response latencies to confirm the average/mean response latency exhibited by each considered method. The matlab file that is used for calculating the PDF is: PDF_DAS_AllOtherMethods19April2024V3.m
### Step 3: 
