---
title: Towards securing low-power digital circuits with ultra-low-voltage vdd
  randomizers
publication_types:
  - "1"
authors:
  - Dina Kamel
  - Guerric de Streel
  - Santos Merino Del Pozo
  - Kashif Nawaz
  - François-Xavier Standaert
  - Denis Flandre
  - David Bol
doi: https://doi.org/10.1007/978-3-319-49445-6_13
publication: "SPACE 2016: Security, Privacy, and Applied Cryptography
  Engineering pp 233-248"
abstract: With the exploding number of connected objects and sensitive
  applications, security against side-channel attacks becomes critical in
  low-cost and low-power IoT applications. For this purpose, established
  mathematical countermeasures such as masking and shuffling always require a
  minimum amount of noise in the adversary’s measurements, that may not be
  guaranteed by default because of good measurement setups and powerful signal
  processing. In this paper, we propose to improve the protection of sensitive
  digital circuits by operating them at a random ultra-low voltage (ULV)
  supplied by a   𝑉𝑑𝑑 randomizer. As the   𝑉𝑑𝑑 randomization modulates the
  switching current, it results in a multiplicative noise on both the current
  consumption amplitude and its time dependence. As ULV operation increases the
  sensitivity of the current on the supply voltage, it magnifies the generated
  noise while reducing the side-channel information signal thanks to the
  switching current reduction. As a proof-of-concept, we prototyped a simple
  𝑉𝑑𝑑 randomizer based on a low-quiescent-current linear regulator with a
  digitally-controlled resistive feedback divider on which we apply a 4-bit
  random number stream. Using an information theoretic metric, the measurement
  results obtained in 65 nm low-power CMOS confirm that such randomizers can
  significantly improve the security of cryptographic implementations against
  standard side-channel attacks in case of low physical noise in the attacks’
  setups, hence enabling the use of mathematical countermeasures.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-09-11T11:32:28.952Z
---
