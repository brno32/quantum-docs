---
author: guanghaolow
description: Explore sample applications of the Microsoft Quantum chemistry library.
ms.author: gulow
ms.date: 02/01/2021
ms.service: azure-quantum
ms.subservice: qsharp-guide
ms.topic: conceptual
no-loc: ['Q#', '$$v']
title: Quantum chemistry sample applications
uid: microsoft.quantum.libraries.overview-chemistry.examples.overview
---

# Quantum chemistry examples

In the quantum chemistry concepts, we manually constructed example fermion Hamiltonians. 
We now combine the chemistry simulation algorithms outlined in [Simulating Hamiltonian dynamics](xref:microsoft.quantum.libraries.overview.standard.algorithms) with [quantum phase estimation](xref:microsoft.quantum.libraries.overview.characterization) in the canon library. 
This combination allows us to obtain  estimates of energy levels in the represented molecule, which is one of the key applications of quantum chemistry on a quantum computer. 

Instead of specifying terms of the Hamiltonian one-by-one, we also work through some examples that allow us to perform quantum chemistry experiments at scale. 
We begin with examples that load a chemistry Hamiltonian encoded in the [Broombridge schema](xref:microsoft.quantum.libraries.overview.chemistry.schema.broombridge).

For molecules that are too large to simulate on the [full state simulator](xref:microsoft.quantum.machines.overview.full-state-simulator), interesting science can still be performed. 
For instance, the resource costs of performing large chemistry simulations may still be evaluated by targeting the [trace simulator](xref:microsoft.quantum.machines.overview.qc-trace-simulator.intro).

Let us now illustrate interesting applications of the chemistry simulation library through a few of the provided samples.