### Image AI Generator
17\18
1. Some bug by AI generate
2. Video accomplish;
3. Style Transform
4. Multi-Format Generate
#### How to See
1. SSDYOLO
2.  Transformer
3. Same Patch to Encoder
#### Evaluation
1. Clip to judge the wrong from the right
2. Rein-Enhancing
#### Generate
1. Spatial attention
2. Temporal Attention
3. From little to huge
##### From my prospective
1. Fetch the embedding of the information: Encode
2. Transform it into possibility: Encode
3. Decode with Attention
4. Output the last one
-----
##### General Speaking
VAE Flow-Based Diffusion-Based Transfomer
1. Original->encoder->()->decoder
2. Original->(invertible decoder)->decoder
3. original->(noise)->()->denoise
###### Vague
Photo-Encoder-Decoder
###### Flow-Based
Decoder(veritable)-->Noise--->Decoder
- Original-AntiTarget+Target=Enhanced Photo
###### Diffusion
Same Decoder
Noise->(Lexical+Denoise)*n
- TrainData +Data= Noise1
- etc. = Ultimate Noise
- Denoise= Noise-Data
- Devided
-----
##### GAN Is a Plugin
- Discriminator
- GoodData、BadData
- Generator Parameter Modify
- Output the possibility of the Resource
- ***Noise is contained between Label Data***
-----
Genie: Generative Interactive Environment
1. Frame 1+ Action1=F2
2. F2+F1+A2=F3
-   'In my opinion, We can use K-Cluster Classification but not the label'
-   So We can just offer the number of Classification.
-   