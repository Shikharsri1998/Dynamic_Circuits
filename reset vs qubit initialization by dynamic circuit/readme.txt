reset took 1 sec less than feedforward way of resetting to |0> when we replaced "mid measurement and feedforward" with reset
i.e. with reset timing were (30 sec)
with mid measurement followed by feedforward, timing were 29 seconds.
In case of qubit reuse plugin, before reusing qubit, measurement appeared before resetting but that measurement had not a role in resetting. That was for storing value of measured qubit. 
1 sec difference is probably due to 2 reasons- resetting happened with spontaneous decay to |0> which take large time compared to that done by dynamic circuit approach OR memory required for feedforward operation is located very far from the qubit only that can explain 1 sec time lag.
Also when we mimic the plugin given kind of circuit, then 48 seconds were used. That has mid measurements but no feedforward from them. Resets were applied independently.
efficiency of reset is less compared to Dynamic Circuit. i.e. spontaneous decay can not be trusted much 
