Branch Predictor in C++

This project implemented a two-level branch predictor. 
The branch predictor's configuration is flexible and can be defined at the beginning of the simulation using parameters. 

including global and local history, global and local finite state machines (FSM),
and different sizes of Branch Target Buffers (BTB).

The BP is tasked with predicting each branch event based solely on the instruction address.
Subsequently, it updates its state according to the actual branch outcome and decision made in the execution stage (EXE).

Branch's Features:
Initialization of the branch predictor.
Update of the branch predictor based on branch outcomes.
Prediction of branches using different predictor configurations.
Display of statistics related to branch prediction accuracy.


