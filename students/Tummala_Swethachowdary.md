# A trusted IoT data sharing method based on secure multi-party computation
Source link to explore:[Source Link](https://journalofcloudcomputing.springeropen.com/articles/10.1186/s13677-024-00704-x)

# *Abstract*
- ***Edge computing nodes close to the perception layer of IoT systems are susceptible to data leaks and unauthorized access*** 
- ***To address these security concerns, this paper proposes a trusted IoT data sharing method based on secure multi-party computation (SMC).*** 
- ***By running a reliable third-party blockchain service at edge computing nodes, the data computation relationships between IoT devices in the perception layer are registered in blockchain smart contracts.***

## *Design of IoT data sharing protocol*
- a trusted third-party service, namely an authorized blockchain network, is introduced into the edge servers
- The IoT devices initiating tasks first register the computation relationships needed among participating IoT devices in the form of arithmetic circuits to the blockchain smart contract.
- The IoT devices initiating tasks first register the computation relationships needed among participating IoT devices in the form of arithmetic circuits to the blockchain smart contract.



## *Protocol execution process*
## *Bloom filter design that can trace the trust state of the sensing layer*
- the IoT data sharing service with high security requirements, the IoT device shall pass the verification of the Blum filter that can trace its trust status according to the device Id number in its certificate.
- After the verification is passed, the on-chain smart contract layer will process the IoT data sharing request of the IoT device of the task initiator.

### *Analysis of misjudgment rate*:
- The Blum filter that can trace the trust state of the device at the sensing layer has three layers and the structure update mode of the third layer is different from that of the traditional Blum filter, the misjudgment rate needs to be re-analyzed and calculated.
