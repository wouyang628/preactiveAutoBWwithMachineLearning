# preactiveAutoBWwithMachineLearning on-going
preactive Auto BW with Machine Learning.

Juniper auto bandwidth feature allows a traffic engineering tunnel to adjust bandwidth reservation automatically according to how much traffic it actually carries and react to traffic change. With the Machine Learning capability of Healthbot , a traffic patter baseline can be built for each traffic engineering tunnel, instead of reacting to traffic change, the LSP can preactively change the reservation bandwidth.

1. configure Healthbot to collect LSP stats using JVision

2. configure Healthbot to build a 24 hour baseline for LSP traffic

3. use the baseline model to signal the traffic engineering LSP bandwidth
