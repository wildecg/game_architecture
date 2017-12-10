# TCG Protocol

##Introduction
Mental Poker works well with poker because both players have the same deck.
In TCG there isn't this assumption.
In literature there are some solutions could be used:
1. Match+Guardian : paper + thesis included. The thesis is very detailed, and their solution using p2p + server could be well adapted to our use case p2p + blockchain
2. FairShuffle (2013): Probably inspired by the former one, look for differences.

##TODO
1. Implement card collection and deck storage in the blockchain
2. Implement matchmaking system starting from leaderboard in the blockchain, could use a really naive one first (i.e. try to request a game to every player listed, starting from the ones with similar ELO)
3. Implement secure shuffling and card dealing system starting from the references above.
4. Implement secure registration of results ,without any TP, for the two clients to the blockchain.
