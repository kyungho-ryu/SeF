# LT Code-Based Blockchain Data Optimization Project

## Overview
Blockchain networks require all nodes to store all data, which creates a barrier for nodes with limited storage capacity. This hinders decentralization, a core principle of blockchain technology.

This project leverages **LT codes** to convert blockchain data into **encoded symbols** for efficient storage and transmission. By optimizing data handling, we enable more nodes to participate in the network while maintaining data integrity and security.

## Key Features and Objectives
- **Efficient Data Optimization**: Enhance storage and transmission efficiency through LT code-based symbolization of blockchain data.
- **Strengthened Decentralization**: Reduce storage burdens, allowing smaller nodes to join the blockchain network.
- **Malicious Node Detection**: Identify nodes transmitting incorrect data, ensuring data integrity.
- **Optimized Distributed Processing**: Implement functionality to receive, merge, and decode data from multiple nodes.

---

## Simulation Process

### 1. Encoding Process
LT codes are used to convert blockchain data into symbols, which are then propagated across the network.

#### A. Sending Side
**Encoding Block Data:**
- Converts input block data into encoded symbols based on LT codes.

**Example Output:**
<div style="display: flex; justify-content: space-between;">
    <img src="image1.png" alt="Image 1" width="45%" style="margin-right: 10px;">
    <img src="image2.png" alt="Image 2" width="45%">
</div>

**File Storage:**
- Encoded symbols are stored in the `encoded_symbol_files` directory.

#### B. Receiving Side
**Receiving Symbol Data:**
- Simulates network operations by receiving transmitted symbols from the sending side.

**Example Output:**
<img src="https://user-images.githubusercontent.com/73271891/157414327-c4cfe6fb-73f3-44d0-a8ec-a49cbac9952d.jpg" width="50%">
<img src="https://user-images.githubusercontent.com/73271891/157414426-1d684222-68c5-4f40-b71f-8d1b940273cb.jpg" width="40%">

**File Storage:**
- Received data is stored in unique folders for each node.

### 2. Decoding Process
The received symbols are used to restore the original data, with additional functionality to detect malicious nodes.

#### A. Decoding Data from Multiple Nodes
**Symbol Integration and Decoding:**
- Combines symbols received from multiple nodes to restore the original block data.
- Decoded data is stored in the `recoveredBlocks` directory.

**Example Output:**
 <img src="https://user-images.githubusercontent.com/73271891/157441202-4f76ed7f-a658-4d13-b30e-6c17c0416b26.jpg" width="40%">

#### B. Malicious Node Detection
**Identifying Invalid Data Sources:**
- Analyzes symbols from each node to verify data integrity.
- Logs malicious nodes and isolates their data.

**Example Output:**
<img src="https://user-images.githubusercontent.com/73271891/157441253-0255d06e-3edc-47be-b572-a9bf97d5d5c9.jpg" width="40%">
<img src="https://user-images.githubusercontent.com/73271891/157441326-628a1fcd-dc0d-4063-ab87-37c7b9084db1.jpg" width="50%">

---

## Results
- Successfully optimized blockchain data using LT codes for efficient transmission and storage.
- Verified the propagation and storage of symbol data between sending and receiving nodes.
- Demonstrated rapid restoration of blockchain data from received symbols across multiple nodes.
- Enhanced security by detecting and isolating malicious nodes.

---

## References
1. **Introduction to Fountain Codes: LT Codes with Python**
2. M. Dai, S. Zhang, H. Wang, S. Jin, "A Low Storage Room Requirement Framework for Distributed Ledger in Blockchain," IEEE Access, vol. 6, pp. 22970–22975, 2018.
3. Kadhe, Swanand, Chung, Jichan, Ramachandran, Kannan, "SeF: A Secure Fountain Architecture for Slashing Storage Costs in Blockchains," arXiv preprint arXiv:1906.12140, 2019.


