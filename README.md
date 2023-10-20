# High-Throughput Multi-Codeword Non-Binary LDPC (NB-LDPC) Decoder on GPU
This is the source codes of NB_LDPC decoder on CUDA GPU. The article a
Z. Liu, R. Liu, Y. Hou and L. Zhao, "High-Throughput Multi-Codeword Decoder for Non-Binary LDPC Codes on GPU," in IEEE Communications Letters, vol. 22, no. 3, pp. 486-489, March 2018,  https://ieeexplore.ieee.org/document/8254357
It is better to rebuild the project according to your GPU architecture and CUDA version. Before running the rebuilt NB-LDPC decoder, the parameters LOG_GF, BLOCK_FRAME, ACTIVE_BLOCK defined in "TotalDefine.h" should be set according to the code you select.
