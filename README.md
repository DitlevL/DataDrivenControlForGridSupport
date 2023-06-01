# DataDrivenControlForGridSupport
Generic code example from the mater thesis: Development and implemtation of data driven control for district heating power plant to provide grid support

Download all files and place them in the same path. "DHNCSV812163_genericExample.mlx" is the control script from which a new agent can be trained, or testing can be done using one of the two included pre-trained agents. The agents were trained on an MVA price signal using binary controll with all PLA and NPLA features enabled.

agent0_NoStartUpPenalty_MVASignal.mat - An agent with no start-up penalty for using the straw boiler
agent1_WithStartUpPenalty_MVASignal.mat - An agent with start-up penalty (0.17) for using the straw boiler.

The file was creating using Matlab 2022B. Matlab simulink, Matlab Deep Learning Toolbox and Matlab Reinforcement Learning Toolbox must be installed.
