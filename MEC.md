# MEC

## Task Model

### Binary offloading

Question:(what is soft deadline and the number of CPU cycles  random variable X.

- whole,either locally or offloaded
- (L,τd,X) : inputdata size L, deadline, computation workload (CPU cycles per bit).

### Partial offloading

Specifically, the program can be partitioned into two parts with
one executed at the mobile device and the other offloaded for
edge execution.

- two parts, one on cpu, the other on edge.

	- data-partition model task bit-wise independent
	- task-call graph(DAG)

## Resource management

### Single-User MEC Systems

- Deterministic Task Model with binary offloading

	- mobile-energy consumption and latency
	- latency

- Deterministic Task Model  with partial Offloading

	- Energy
	- Latency
	- Energy and latency

- Stochastic Task Model

	- Energy
	- Latency
	- Energy and latency

### Multiuser MEC Systems

- Joint Radio-and-Computational Resource Allocation

	- centralized resource allocation
	- distributed 

- MEC server scheduling

	- Bursty data arrivals
	- Heterogeneous deadlines
	- Task dependency

- Cooperative computing

	- D2D communication
	- Cooperation
	- Share computation results
	- Share computational resource
	- Small BSs cooperation

## 分支主题 3

## 分支主题 4

## Computation Models

### Moile Devices

- energy consumption for task (L,τ,X):E=kLXf^2(1)
- t=LX/f(2)
- (1)(2)-> offloading is necessary

### MEC Servers

- deterministic
- stochastic

### Summary

- leverage both wireless communication and mobile computing
- choose suitable computation task models for different MEC applications
- Dynamic CPU-cycle frequency control is the key tech for controlling the communication latency and energy consumption .
- Apart from the task execution latency the computation scheduling delay is non-negligible, if MEc has small capacity or heavy computation loads. Load-balancing and intelligent scheduling policies can be designed to reduce the total computation latency.

*XMind: ZEN - Trial Version*