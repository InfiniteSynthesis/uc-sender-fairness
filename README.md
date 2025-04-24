<h1 align="center">Universal Composable Transaction Serialization<br/>with Order Fairness</h1>

<p align="center">
Michele Ciampi<sup>1</sup>, Aggelos Kiayias<sup>1,2</sup>, Yu Shen<sup>1</sup>
</p>

<p align="center">
<sup>1</sup>University of Edinburgh
<sup>2</sup>IOG
</p>

<p align="center">
    <a href="http://creativecommons.org/licenses/by/4.0/"><img src="https://img.shields.io/badge/License-CC--BY--4.0-bb6688.svg?style=for-the-badge&labelColor=884499" alt="License"></a>
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-68379-4_5"><img src="https://img.shields.io/badge/Proceedings-CRYPTO 2024-8888cc.svg?style=for-the-badge&labelColor=884499" alt="Proceedings"></a>
    <a href="https://eprint.iacr.org/2024/1296"><img src="https://img.shields.io/badge/Full-Version-ccaa88.svg?style=for-the-badge&labelColor=884499" alt="Full Version"></a>
</p>

> [!NOTE]  
> This repository contains the LaTeX source code of "Universal Composable Transaction Serialization with Order Fairness." An abridged version of this paper appears in *Proc. CRYPTO 2024*.

## :books: Abstract

Order fairness in the context of distributed ledgers has received recently significant attention due to a range of attacks that exploit the reordering and adaptive injection of transactions (violating what is known as "input causality"). To address such concerns an array of definitions for order fairness has been put forth together with impossibility and feasibility results highlighting the difficulty and multifaceted nature of fairness in transaction serialization. Motivated by this we present a comprehensive modeling of order fairness capitalizing on the universal composition (UC) setting. Our results capture the different flavors of sender order fairness and input causality (which is arguably one of the most critical aspects of ledger transaction processing with respect to serialization attacks) and we parametrically illustrate what are the limits of feasibility for realistic constructions via an impossibility result. Our positive result, a novel distributed ledger protocol utilizing trusted enclaves, complements tightly our impossibility result, hence providing an *optimal* sender order fairness ledger construction that is also eminently practical.