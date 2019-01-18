## ORE Block Producer Agreement

I, {{producer}}, hereby nominate myself for consideration as an elected block producer.

I {{producer}} understand that producing blocks on the ORE Blockchain will require running additional service components in the future, including but not limited to the Verifier service. 

I {{producer}} understand that Block Producers are required to roll-out new services (when released) within the timeline agreed to by a majority vote of the network. I, {{producer}}, agree not to install smart contracts or create accounts outside of the existing deployed contracts on the chain - I understand that the ORE blockchain is not a general-purpose public chain.

I, {{producer}}, agree that in return for operating block producing node(s), I will receive my share of the producer pool of 2% annual inflation on a beginning token supply of 1 Billion ORE tokens. In total, the ORE blockchain has 5% annual inflation. I understand that, in addition to the BP inflation, there will be a grant of 2% to developers and projects using the ORE chain and 1% to AIKON for continuing development of the ORE protocol and related products and that these allocations may be reconsidered during the process of creating and ratifying a constitution.

I, {{producer}}, understand that ORE Blockchain SYS token will not be publicly circulated and that I will use a custom smart contract for claiming by block producer rewards as ORE tokens and that I will never attempt to claim, own, or use the SYS token.

I, {{producer}}, understand that ORE tokens will be valued at a rate of one SYS to one ORE token and that these ORE tokens will have voting rights, claim to network resources and will be circulated publicly on exchanges.

If {{producer}} is selected to produce blocks by the eosio contract, I will sign blocks with {{producer_key}} and I hereby attest that I will keep this key secret and secure.

If {{producer}} is unable to perform obligations under this contract I will resign my position by re-submitting this contract with the null producer key.

I acknowledge that a block is 'objectively valid' if it conforms to the deterministic blockchain rules in force at the time of its creation, and is 'objectively invalid' if it fails to conform to those rules.

{{producer}} hereby agrees to only use {{producer_key}} to sign messages under the following scenarios:
proposing an objectively valid block at the time appointed by the block scheduling algorithm
pre-confirming a block produced by another producer in the schedule when I find said block objectively valid
confirming a block for which {{producer}} has received 2/3+ pre-confirmation messages from other producers

I hereby accept liability for any and all provable damages that result from my:
signing two different block proposals with the same timestamp with {{producer_key}}
signing two different block proposals with the same block number with {{producer_key}}
signing any block proposal which builds off of an objectively invalid block
signing a pre-confirmation for an objectively invalid block
signing a confirmation for a block for which I do not possess pre-confirmation messages from 2/3+ other producers

I hereby agree that double-signing for a timestamp or block number in concert with 2 or more other producers shall automatically be deemed malicious and subject to a fine equal to the past year of compensation received and immediate disqualification from being a producer, and other damages. An exception may be made if {{producer}} can demonstrate that the double-signing occured due to a bug in the reference software; the burden of proof is on {{producer}}.

The community agrees to allow {{producer}} to authenticate peers as necessary to prevent abuse and denial of service attacks; however, {{producer}} agrees not to discriminate against non-abusive peers.

I agree to process transactions on a FIFO best-effort basis and to honestly bill transactions for measured execution time.

I {{producer}} agree not to manipulate the contents of blocks in order to derive profit from:
the order in which transactions are included
the hash of the block that is produced

I, {{producer}}, hereby agree to cooperate with other block producers to carry out our respective and mutual obligations under this agreement, including but not limited to maintaining network stability and a valid blockchain.

I, {{producer}}, agree to maintain a website hosted at {{url}} which contains up-to-date information on all disclosures required by this contract.

I, {{producer}}, agree to set {{location}} such that {{producer}} is scheduled with minimal latency between my previous and next peer.

I, {{producer}}, agree to maintain time synchronization within 10 ms of global atomic clock time, using Network Time Protocol (https://www.ietf.org/rfc/rfc5905.txt)

I, {{producer}}, agree not to produce blocks before my scheduled time unless I have received all blocks produced by the prior producer.

I, {{producer}}, agree not to publish blocks with timestamps more than 500ms in the future unless the prior block is more than 75% full by either CPU or network bandwidth metrics.

I, {{producer}}, agree not to set the RAM supply to more RAM than my nodes contain and to resign if I am unable to provide the RAM approved by 2/3+ producers, as shown in the system parameters. 
