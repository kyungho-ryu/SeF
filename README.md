# SeF : A Secure Fountain Architecture for Lightweight Blockchain Storage


### Summary

Since all nodes in the blockchain have to maintain all blockchain data, nodes with low capacity are more difficult to participate in blockchain consensus. This problem further weakens the decentralization of blockchain. Therefore, we lighten the blockchain by storing the block data as encoded sybols through the LT code.

### Simulation 

- Encoding process
  - A node propagates symbols to the nodes of the blockchain network
  - the sending side
  <img src="https://user-images.githubusercontent.com/73271891/157414197-def0be43-7e86-46fa-9854-382beb7de8d1.jpg" width="50%">
  <img src="https://user-images.githubusercontent.com/73271891/157414365-65f1353a-1ca5-4bc6-a1b4-9efa91cb2b77.jpg" width="40%">

  - the receiving side
  <img src="https://user-images.githubusercontent.com/73271891/157414327-c4cfe6fb-73f3-44d0-a8ec-a49cbac9952d.jpg" width="50%">
  <img src="https://user-images.githubusercontent.com/73271891/157414426-1d684222-68c5-4f40-b71f-8d1b940273cb.jpg" width="40%">
  
- Decoding process
  - Decoding after receiving symbols from multiple nodes
  <img src="https://user-images.githubusercontent.com/73271891/157441202-4f76ed7f-a658-4d13-b30e-6c17c0416b26.jpg" width="40%">
  

  - Detecting malicious nodes
  <img src="https://user-images.githubusercontent.com/73271891/157441253-0255d06e-3edc-47be-b572-a9bf97d5d5c9.jpg" width="40%">
  <img src="https://user-images.githubusercontent.com/73271891/157441326-628a1fcd-dc0d-4063-ab87-37c7b9084db1.jpg" width="50%">
  
  


### REFERENCE
- [INTRODUCTION TO FOUNTAIN CODES: LT CODES WITH PYTHON](https://franpapers.com/en/algorithmic/2018-introduction-to-fountain-codes-lt-codes-with-python/)
- M. Dai, S. Zhang, H. Wang and S. Jin, "A Low Storage Room Requirement Framework for Distributed Ledger in Blockchain," in IEEE Access, vol. 6, pp. 22970-22975, 2018
- KADHE, Swanand; CHUNG, Jichan; RAMCHANDRAN, Kannan. SeF: A secure fountain architecture for slashing storage costs in blockchains. arXiv preprint arXiv:1906.12140, 2019.

