# codefundo++ idea

In our project, we intend to solve different problems: 1)voting from different locations,2)adding a person into the voters list, 3)hacking accusations and 4)declaring results.

Everyone is given an e-voter card (e-ID) which has an address ,uniquely representing each individual (like an address of crypto wallet), which he/she uses to vote. The difference between the e-voter card and wallet would be that, wallet stores cryptocurrency whereas e-ID is used to just vote by the voters.
This enables voters to vote from any place in the world.

In addition to this, each baby born is given an eID (an individual must be able to register at any point of time, but can be able to vote only after (s)he is 18), which is activated whenever they turn 18, simultaneously adding their name to voters list. This solves the problem of addition of names to the voters list.

As soon as the voter votes, he gets cryptographically signed receipt containing hashed information of whom he voted,his ID no., his name etc. (which obviously cant be read by humans). These receipts can be published on a portal(alongwith the corresponding IDs) where every individual can verify the hash corresponding to his ID. In case of accusations of hacking by the losing candidate, these receipts can be helpful in proving the authenticity of results, by verifications using some or all the receipts.

Since the counting is done on blockchain in real-time, the results can be published as soon as the voting time ends.
