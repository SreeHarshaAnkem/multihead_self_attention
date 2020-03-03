# Multihead_self_attention
Encoder of Transformer
Components:
 - Multi Head Self Attention
Can be used as a layer in keras model with Functional API. 

Advantages:
1. Better parallelization as all time steps are processed simulataneously.
2. Multiple heads imply multiple vector space representations.
3. Better performance on long sequences.
