# Life of an EIP (Ethereum Improvement Proposal)

For more information about EIPs, please check the [Ethereum EIP website](https://eips.ethereum.org/).


| Final Core EIPs | 	Title    | 	"Complexity of EIP" | 	Upgrade name |	Date of "first mention" |	Link of "first mention" |	Date of PR |	Link of PR |	Network update |	Date of upgrade going live to mainnet |	Link |	Time between 1st mention and EIP going live to mainnet (in days) |	Additional comments |
|----------|-----------|----------------------|---------------|----------|----------|----------|----------|----------|-----------|-----------|-----------|-----------|
|2	| Homestead Hard-fork Changes    	| 2             	|Homestead	|Nov 2015	|https://github.com/ethereum/EIPs/blob/master/EIPS/eip-2.md	|Nov 2015	|Same	|Mainnet	|Apr 2016	|https://blog.ethereum.org/2016/02/29/homestead-release/	|151	|Released around Pi Day at block 1.150.000 @ https://ethereum.stackexchange.com/questions/587/when-will-the-eip-2-fork-kick-in|
|5	| Gas Usage for `RETURN` and `CALL*`	|3	|//	| Nov 2015	|https://github.com/ethereum/EIPs/issues/8	|Nov 2015	|Same	|Mainnet	|Nov 2015	|https://eips.ethereum.org/EIPS/eip-5#specification	|6	|Deprecated since/by EIP211 according to latest comment @ https://github.com/ethereum/EIPs/issues/8|
7	DELEGATECALL	1	Homestead	Nov 2015	https://github.com/ethereum/EIPs/blob/master/EIPS/eip-7.md	Nov 2015	Same	Mainnet	Apr 2016	https://blog.ethereum.org/2016/02/29/homestead-release/	151	Released around Pi Day as well (block 1.150.000)
100	Change difficulty adjustment to target mean block time including uncles	4	Byzantium	Apr 2016	https://github.com/ethereum/EIPs/issues/100	Apr 2016	Same	Mainnet	Oct 2017	https://github.com/ethereum/EIPs/issues/100	536	There was an update on June 2017, according to https://github.com/ethereum/EIPs/issues/100
140	REVERT instruction	2	Byzantium	Aug 2016	https://github.com/ethereum/EIPs/issues/140	Aug 2016	Same	Mainnet	Oct 2017	https://eips.ethereum.org/EIPS/eip-140	420
141	Designated invalid EVM instruction	2	//	Aug 2016	https://github.com/ethereum/EIPs/issues/141	Aug 2016	Same	Mainnet	Feb 2017	https://eips.ethereum.org/EIPS/eip-141	164
145	Bitwise shifting instructions in EVM	4	Constantinople	Sep 2016	https://github.com/ethereum/EIPs/issues/145	Sep 2016	Same	Mainnet	Feb 2017	https://eips.ethereum.org/EIPS/eip-145	157	"The issue seems to have gone quiet and missed the Byzantium fork. I'd like to express interest in it being included for Constantinople" @ https://github.com/ethereum/EIPs/issues/145
150	Gas cost changes for IO-heavy operations	2	Tangerine Whistle	Sep 2016	https://github.com/ethereum/EIPs/issues/150	Sep 2016	Same	Mainnet	Oct 2016	https://github.com/ethereum/EIPs/issues/150	24	EDITOR UPDATE (2017-08-15): This EIP is now located at https://github.com/ethereum/EIPs/blob/master/EIPS/eip-150.md
152	Add BLAKE2 compression function `F` precompile	4	Istanbul	Oct 2016	https://github.com/ethereum/EIPs/issues/152	Oct 2016	Same	Mainnet	Dec 2019	https://github.com/ethereum/EIPs/issues/152	1160	"Generalize EIP-152 to other BLAKE2 variants #2293" on September 2019
155	Simple replay attack protection	2	Spurious Dragon	Oct 2016	https://github.com/ethereum/EIPs/issues/155	Oct 2016	Same	Mainnet	Nov 2016	https://github.com/ethereum/EIPs/issues/155	39
158	State clearing	3	Tangerine Whistle	Oct 2016	https://github.com/ethereum/EIPs/issues/158	Oct 2016	Same	Mainnet	Oct 2016	https://github.com/ethereum/EIPs/issues/158	10
160	EXP cost increase	2	Spurious Dragon	Oct 2016	https://github.com/ethereum/EIPs/issues/160	Oct 2016	Same	Mainnet	Nov 2016	https://github.com/ethereum/EIPs/issues/160	33	EDITOR UPDATE (2017-08-15): This EIP is now located at https://github.com/ethereum/EIPs/blob/master/EIPS/eip-160.md. Please go there for the correct specification
161	State trie clearing (invariant-preserving alternative)	3	Spurious Dragon	Oct 2016	https://github.com/ethereum/EIPs/issues/161	Oct 2016	Same	Mainnet	Apr 2017	https://github.com/ethereum/EIPs/issues/161	169	On 2016-11-24, a consensus bug occurred due to two implementations having different behavior in the case of state reverts.[3] The specification was amended to clarify that empty account deletions are reverted when the state is reverted.
170	Contract code size limit	3	Spurious Dragon	Nov 2016	https://eips.ethereum.org/EIPS/eip-170	Nov 2016	Same	Mainnet	Nov 2016	https://github.com/ethereum/EIPs/issues/170	18
196	Precompiled contracts for addition and scalar multiplication on the elliptic curve alt_bn128	4	Byzantium	Jan 2017	https://github.com/ethereum/EIPs/issues/196	Jan 2017	Same	Mainnet	Nov 2017	https://github.com/ethereum/EIPs/issues/196	300
197	Precompiled contracts for optimal ate pairing check on the elliptic curve alt_bn128	4	Byzantium	Jan 2017	https://github.com/ethereum/EIPs/issues/197	Jan 2017	Same	Mainnet	Oct 2017	https://github.com/ethereum/EIPs/issues/197	270
198	Big integer modular exponentiation	5	Byzantium	Jan 2017	https://github.com/ethereum/EIPs/pull/198	Jan 2017	Same	Mainnet	Oct 2017	https://github.com/ethereum/EIPs/pull/198	259
211	New opcodes: RETURNDATASIZE and RETURNDATACOPY	3	Byzantium	Feb 2017	https://github.com/ethereum/EIPs/pull/211	Feb 2017	Same	Mainnet	Dec 2017	https://github.com/ethereum/EIPs/pull/211	291
214	New opcode STATICCALL	2	Byzantium	Feb 2017	https://github.com/ethereum/EIPs/pull/214	Feb 2017	Same	Mainnet	Nov 2017	https://github.com/ethereum/EIPs/pull/214	278
225	Clique proof-of-authority consensus protocol	3	//	Mar 2017	https://github.com/ethereum/EIPs/issues/225	Mar 2017	Same	Rinkeby	Mar 2017	https://github.com/ethereum/EIPs/issues/225	0	First proposal of the Rinkeby testnet and its PoA implementation ideas.
649	Metropolis Difficulty Bomb Delay and Block Reward Reduction	2	Byzantium	Jun 2017	https://github.com/ethereum/EIPs/issues/649	Jun 2017	Same	Mainnet	Oct 2017	https://github.com/ethereum/EIPs/issues/649	117
658	Embedding transaction status code in receipts	1	Byzantium	Jun 2017	https://github.com/ethereum/EIPs/pull/658	Jun 2017	Same	Mainnet	Oct 2017	https://github.com/ethereum/EIPs/pull/658	108
1014	Skinny CREATE2	4	Constantinople	Apr 2018	https://github.com/ethereum/EIPs/pull/1014	Apr 2018	Same	Mainnet	Sep 2018	https://github.com/ethereum/EIPs/pull/1014	135	2018.09.02: Version 2: use sha3(msg.sender ++ salt ++ sha3(init_code))[12:]
1052	EXTCODEHASH opcode	3	Constantinople	May 2018	https://eips.ethereum.org/EIPS/eip-1052	May 2018	Same	Mainnet	May 2018	https://github.com/ethereum/EIPs/pull/1052	0	The new opcodes introduced in Constantinople are not supported
1108	Reduce alt_bn128 precompile gas costs	4	Istanbul	May 2018	https://github.com/ethereum/EIPs/pull/1108	May 2018	Same	Mainnet	Dec 2019	https://github.com/ethereum/EIPs/pull/1108	566	Update: some updates were recently added and it’s been added to EIP-1679, the meta-EIP for the forthcoming Istanbul hardfork, as a proposed EIP
1234	Constantinople Difficulty Bomb Delay and Block Reward Adjustment	3	Constantinople	Jul 2018	https://eips.ethereum.org/EIPS/eip-1234	Jul 2018	Same	Mainnet	Jul 2018	https://github.com/ethereum/EIPs/pull/1234	1	The new opcodes introduced in Constantinople are not supported in Pyethereum
1283	Net gas metering for SSTORE without dirty maps	5	//	Aug 2018	https://eips.ethereum.org/EIPS/eip-1283	Aug 2018	Same	Mainnet	Aug 2018	https://github.com/ethereum/EIPs/pull/1283	5
1344	ChainID opcode	4	Istanbul	Aug 2018	https://eips.ethereum.org/EIPS/eip-1344	Aug 2018	Same	Mainnet	Dec 2019	https://github.com/ethereum/EIPs/pull/1344	473
1559	Fee market change for ETH 1.0 chain	5	London	Aug 2018	https://ethresear.ch/t/draft-position-paper-on-resource-pricing/2838	Aug 2018	Same	Mainnet	Aug 2021	https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1559.md	1100	Note: Multidimensional EIP 1559 proposed in 2022 @ https://ethresear.ch/t/multidimensional-eip-1559/11651
1884	Repricing for trie-size-dependent opcodes	4	Istanbul	Mar 2019	https://eips.ethereum.org/EIPS/eip-1884	Mar 2019	Same	Mainnet	Dec 2019	https://github.com/ethereum/EIPs/pull/1884	255
2028	Transaction data gas cost reduction	5	Istanbul	May 2019	https://eips.ethereum.org/EIPS/eip-2028	May 2019	Same	Mainnet	Dec 2019	https://github.com/ethereum/EIPs/pull/2028	219
2200	Structured Definitions for Net Gas Metering	2	Istanbul	Jul 2019	https://eips.ethereum.org/EIPS/eip-2200	Jul 2019	Same	Mainnet	Dec 2019	https://github.com/ethereum/EIPs/pull/2200	143	This is a combination of EIP-1283 and EIP-1706
2384	Muir Glacier Difficulty Bomb Delay	2	Muir Glacier	Nov 2019	https://eips.ethereum.org/EIPS/eip-2384	Nov 2019	Same	Mainnet	Jan 2020	https://github.com/ethereum/EIPs/pull/2384	43
2565	ModExp Gas Cost	4	Berlin	Mar 2020	https://eips.ethereum.org/EIPS/eip-2565	Mar 2020	Same	Mainnet	Apr 2020	https://github.com/ethereum/EIPs/pull/2565	26
2681	Limit account nonce to 2^64-1	2	//	Apr 2020	https://eips.ethereum.org/EIPS/eip-2681	Apr 2020	Same	Mainnet	Jul 2020	https://github.com/ethereum/EIPs/pull/2681	83
2718	Typed Transaction Envelope	2	Berlin	Jun 2020	https://eips.ethereum.org/EIPS/eip-2718	Jun 2020	Same	Mainnet	Sep 2020	https://github.com/ethereum/EIPs/pull/2718	81
2929	Gas cost increases for state access opcodes	5	Berlin	Sep 2020	https://eips.ethereum.org/EIPS/eip-2929	Sep 2020	Same	Mainnet	Sep 2020	https://github.com/ethereum/EIPs/pull/2929	0
2930	Optional access lists	4	Berlin	Aug 2020	https://eips.ethereum.org/EIPS/eip-2930	Aug 2020	Same	Mainnet	Sep 2020	https://github.com/ethereum/EIPs/pull/2930	4
3198	BASEFEE opcode	1	London	Jan 2021	https://eips.ethereum.org/EIPS/eip-3198	Jan 2021	Same	Mainnet	Jan 2021	https://github.com/ethereum/EIPs/pull/3198	1
3529	Reduction in refunds	3	London	Apr 2021	https://eips.ethereum.org/EIPS/eip-3529	Apr 2021	Same	Mainnet	Aug 2021	https://github.com/ethereum/EIPs/pull/3529	105
3541	Reject new contract code starting with the 0xEF byte	2	London	Mar 2021	https://eips.ethereum.org/EIPS/eip-3541	Mar 2021	Same	Mainnet	Aug 2021	https://github.com/ethereum/EIPs/pull/3541	142
3554	Difficulty Bomb Delay to December 2021	4	London	May 2021	https://ethereum-magicians.org/t/eip-3554-ice-age-delay-targeting-december-2021/6188	May 2021	Same	Mainnet	Aug 2021	https://github.com/ethereum/EIPs/pull/3554	96
3607	Reject transactions from senders with deployed code	1	//	Jun 2021	https://eips.ethereum.org/EIPS/eip-3607	Jun 2021	Same	Mainnet	Oct 2021	https://github.com/ethereum/EIPs/issues/3608	116
4345	Difficulty Bomb Delay to June 2022	2	Arrow Glacier	Oct 2021	https://eips.ethereum.org/EIPS/eip-4345	Oct 2021	Same	Mainnet	Dec 2021	https://github.com/ethereum/EIPs/pull/4345	65	





| Final Core EIPs | Title | Complexity | Upgrade name | "First mention" | Date of PR | Network update | Date of upgrade going live to mainnet | Days between 1st mention and EIP going live to mainnet | Additional comments |
|----------|----------|----------|----------|-----------------|----------|----------|----------|----------|-----------|
| Data 1   | Data 2   | Data 3   | Data 4   | Data 5          | Data 6   | Data 7   | Data 8   | Data 9   | Data 10   | 
| Data 1A  | Data 2A  | Data 3A  | Data 4A  | Data 5A         | Data 6A  | Data 7A  | Data 8A  | Data 9A  | Data 10A  | 
| Data 1B  | Data 2B  | Data 3B  | Data 4B  | Data 5B         | Data 6B  | Data 7B  | Data 8B  | Data 9B  | Data 10B  | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 
| ...      | ...      | ...      | ...      | ...             | ...      | ...      | ...      | ...      | ...       | 

