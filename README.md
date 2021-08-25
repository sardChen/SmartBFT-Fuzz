# SmartBFT-Fuzz

This is a fuzz project for SmartBFT-Go/fabric

Compared with original Smartbft node, a function 'func (e *Egress) SendConsensusFuzz(targetID uint64, m *protos.Message)' is added in egress.go, messageFuzzer.go is added in package smartbft.

To run the fuzzer node locally, just replace SendConsensus with SendConsensusFuzz in egress.go.
