# Resources

## Swarm, the name
- https://www.facebook.com/swarmcorp, http://swarm.fund/
- https://bitcointalk.org/index.php?topic=650143.0
- https://bitcoinmagazine.com/17956/swarm-1-rick-falkvinges-swarmops-project/
- http://www.amazon.co.uk/Swarmwise-Tactical-Manual-Changing-World/dp/1463533152/

## Self
- our private repo: https://github.com/ethersphere/swarm 
- drafts (private): https://github.com/ethersphere/swarm/doc 
- wiki (private): https://github.com/ethersphere/swarm/wiki
- Dani & Viktor on public wiki: https://github.com/ethereum/wiki/wiki/Distributed-Preimage-Archive
- Gav on public wiki: https://github.com/ethereum/cpp-ethereum/wiki/Swarm
- on kademlia: https://github.com/ethereum/wiki/wiki/Cademlia-Peer-Selection
- Ethereum node discovery protocol on UDP: https://github.com/ethereum/go-ethereum/wiki/RLPx-----Node-Discovery-Protocol

## Talks
- https://twitter.com/ethereumproject/status/538030376858693633
- Dr. Daniel Nagy: Ethereum ÐΞVcon-0: Keeping the Public Record Safe and Accessible - https://www.youtube.com/watch?v=QzYZQ03ON2o&list=PLJqWcTqh_zKEjpSej3ddtDOKPRGl_7MhS&index=7&spfreload=10

## Forum
- empty as of 01/2015: https://forum.ethereum.org/categories/swarm

## Mentions, discussions
- http://www.reddit.com/r/ethereum/comments/2d4uyw/swarm_and_whisper/
- http://www.reddit.com/r/ethereum/comments/2ityfz/ethereum_swarm/
- https://www.maidsafe.org/t/ethereums-swarm-p2p-storage-and-whisper-p2p-messaging/1528
- Vitalik's blogpost of 08/2014 - https://blog.ethereum.org/2014/08/16/secret-sharing-erasure-coding-guide-aspiring-dropbox-decentralizer/
- Vitalik: 'Swarm is out-of-scope': https://www.reddit.com/r/ethereum/comments/2phvml/constructive_criticism_of_ethereum_project_not/cmwtfqq

## Code 
- bzz PR: https://github.com/ethereum/go-ethereum/pull/255, 
- repo https://github.com/ethersphere/go-ethereum/tree/bzz/
- ethereum p2p: https://github.com/ethereum/go-ethereum/p2p
- peer selection, peer pool: https://github.com/ethereum/go-ethereum/pull/253 
- p2p cademlia branch (discontinued): https://github.com/ethersphere/go-ethereum/tree/kademlia
- Felix's node discovery code:

# Alternatives

- storj - http://storj.io/
- maidsafe - http://maidsafe.net/
- ipfs - http://ipfs.io/, https://www.youtube.com/watch?v=Fa4pckodM9g, http://static.benet.ai/t/ipfs.pdf, https://github.com/jbenet/go-ipfs
- filecoin - http://filecoin.io/
- permacoin - https://www.cs.umd.edu/~elaine/docs/permacoin.pdf, https://bitcointalk.org/index.php?topic=640410.0, http://blog.dshr.org/2014/06/permacoin.html
- siacoin - http://www.siacoin.com/
- riak - http://basho.com/riak/
- BitTorrent http://www.bittorrent.com/

- Is it even worth it to reinvent/reimplement the wheel?
- what features do we want now and in future

## Swarm

How far does the analogy go?

-------|------------
swarm of bees | a decentralised network of peers
living in a hive | form a distributed preimage archive
where they | where they
gather pollen | gather data chunks which they 
to produce honey | transform into a longer data stream (document)
they consume and store |  they serve and store  
buzzing bzz | using bzz as their communications protocol


# Brainstorming

- storage economy, incentivisation
- nonoutsourceable proofs of storage as mining criteria 
- proof of storage capacity directly rewarded by contract
- streaming, hash chains 
- routing and learning graph traversal
- minimising hops
- forwarding strategies, optimising dispersion of requests 
- lifetime of requests, renewals (repeated retrieval requests), expiry, reposting (repeated storage request)

# Simulations

- full table homogeneous nodes network size vs density vs table size expected row-sizes 
- forwarding strategy vs latency vs traffic
- stable table, dropout rate vs routing optimisation by precalculating subtables for all peers. expected distance change (proximity delta) per hop




