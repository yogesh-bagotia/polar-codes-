# Polar Codes – Communication Systems Proj
repository contains the implementation and analysis of **Polar Codes**, developed as part of the *Introduction to Communication Systems (CT-216)* course project. Polar codes are the first class of error-correcting codes proven to achieve Shannon capacity for a wide class of communication channels with efficient encoding and decoding.

## 📚 Project Overview

This project explores:

* Theoretical foundations of Polar Codes
* Channel polarization and its proof
* Construction and decoding techniques
* Performance analysis through MATLAB simulations

## 👨‍💻 Team Members

Group 11 (Lab Group 2):

* Diyen Pambhar – 202301113
* Yogesh Bagotia – 202301114
* Meet Dobariya – 202301115
* Kavya Chauhan – 202301116
* Sanya Vaishnavi – 202301117
* Mudit Rungta – 202301118
* Dharva Patel – 202301119
* Krutant Jethva – 202301120
* Sri Sadana Dharavath – 202301121

Instructor: **Prof. Yash Vasavada**
Date: May 6, 2025

---

## 📖 Contents

### 1. Theoretical Concepts

* Binary Erasure Channel (BEC)
* Polar Transform & Channel Polarization
* Bhattacharyya Parameters
* Shannon Capacity & Proof

### 2. Code Construction

* Arıkan’s Transform
* Frozen and Information Bits
* Successive Cancellation (SC) Coding

### 3. Decoding Algorithms

* Successive Cancellation (SC)
* Successive Cancellation List (SCL) with CRC

### 4. MATLAB Simulations

* BER and BLER vs Eb/N0
* SCL vs SC performance
* Rate adaptation

---

## 📊 Simulation Results

Simulations were carried out in MATLAB using:

* Block lengths up to 256
* Rates: 0.25, 0.5, 0.625
* SC and SCL decoders

Key highlights:

* SCL decoding significantly improves reliability over SC
* Polar Codes approach theoretical limits under high SNR
* CRC enhances error detection in SCL decoding

---

## 🧠 Key Learnings

* **Polarization**: Using recursive transforms to convert channels into either nearly perfect or completely noisy.
* **Channel Capacity**: Achieving reliable transmission close to Shannon's theoretical limit.
* **Trade-offs**: Between complexity, code rate, and performance for SC vs SCL.

---


## 📎 References

* E. Arikan, “Channel Polarization: A Method for Constructing Capacity-Achieving Codes for Symmetric Binary-Input Memoryless Channels,” *IEEE Transactions on Information Theory*, 2009.
* MATLAB documentation for AWGN and CRC modeling.

---

For queries, reach out via GitHub Issues or contact any group member.

---

Would you like me to generate the actual `README.md` file you can directly upload to GitHub?
