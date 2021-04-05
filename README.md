# Scheduling-DOCPLEX-Examples_CP

Constraint programming formulations for different machine scheduling problems are provided in this repository. 

Optimization models are formulated in Python and solved with Cplex by using DOcplex Python Modeling API.

Problems addressed are: 
- [Single machine scheduling to minimize weighted number of tardy jobs](https://github.com/ErayCakici/Scheduling-DOCPLEX-Examples_CP/blob/main/SingleMch_WeightedNbrOfTardyJobs.ipynb) 
- [Single machine scheduling to minimize maximum lateness (with release times)](https://github.com/ErayCakici/Scheduling-DOCPLEX-Examples_CP/blob/main/SingleMch_MinMaxLatenessReleaseDates.ipynb)
- [Single machine scheduling to minimize total weighted completion times (with precedence constraints)](https://github.com/ErayCakici/Scheduling-DOCPLEX-Examples_CP/blob/main/SingleMch_TWCT_PrecedenceConstraints.ipynb)
- [Single machine scheduling to minimize total weighted completion times (with batching and incompatible job families)](https://github.com/ErayCakici/Scheduling-DOCPLEX-Examples_CP/blob/main/SingleMch_TWCT_Batching.ipynb)
- [Single machine scheduling to minimize makespane (with sequence dependent setup times)](https://github.com/ErayCakici/Scheduling-DOCPLEX-Examples_CP/blob/main/SingleMch_SeqDepSetUp.ipynb) 

Same problems are formulated in Optimization Programming Language (OPL) at [Scheduling-OPL-Examples_CP](https://github.com/ErayCakici/Scheduling-OPL-Examples_CP) repository. 
