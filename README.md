Build a Generatively Pretrained Transformer (GPT)

autoregressive language modeling framework and basics of tensors and PyTorch nn  
    
      
----    
      
Building Self-Attention

Version 1: Introduces self-attention by averaging past context using for loops.  
Matrix Multiply: Demonstrates how self-attention utilizes matrix multiplication for weighted aggregation.  
Version 2 and 3: Progresses from basic matrix multiplication to adding softmax for improved attention mechanisms.  
Code Cleanup and Positional Encoding: Minor code improvements and introduction to positional encoding.  
Version 4: Focus on advanced self-attention.

Notes on Attention  
Discusses various concepts related to attention mechanisms:  

Attention as a form of communication.  
Lack of spatial awareness in attention.  
No communication across batch dimensions.  
Differences between encoder and decoder blocks.  
Comparison of attention types: attention, self-attention, and cross-attention.  
Explanation of scaled self-attention.  

--
  
  
  
Building the Transformer   

Incorporating a self-attention block into the network.  
Multi-headed self-attention implementation.  
Adding feedforward layers, residual connections, and layer normalization.  
Scaling the model with new variables and dropout.  

Notes on Transformers  
Comparing encoder and decoder architectures, with insights into nanoGPT and batched multi-headed self-attention.  
