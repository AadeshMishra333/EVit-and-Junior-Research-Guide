# WHAT ARE WE DOING?

### What papers do we have?
* HierarchicalMamba_A_Multiscale_State_Space_Model_With_Dual_Transitions_for_Hyperspectral_Image_Classification.pdf + hierarchical_mamab_hicervix.py
  - Mamba Paper, start by learning its maths then architecture
* PCAM Medical Image Paper.pdf 
  - The medical image paper on thorasic diseases that we are supposed to beat, incorporating EVit or Even mamba vision in its backend
  - Start by replicating the paper execution first
* EVIT.pdf eagle vision transformer
  - BEV block to incorporate inside the baseline of PCAM and beat it
  - Juniors have also implemented it in their Change Detection model
* SiameseJuniors-ConvFormer-CD_Hybrid_CNNTransformer_With_Temporal_Attention_for_Detecting_Changes_in_Remote_Sensing_Imagery.pdf
  - The paper juniors are trying to beat by changing the backend model with BEV eagle vision (and other ablations)
* ERDUnet_An_Efficient_Residual_Double-Coding_Unet_for_Medical_Image_Segmentation.pdf
  - Kushal Bhaiya Paper, main task to execute ablation versions and also suggest some versions to him, he will give the model code and i have to just execute it
  - We have to reduce Gflops, Parameters while maintaining the metrics

### What models are there?
* Bhaiya model - ERSUnet, don't have much understanding of it (using the ERDUnet baseline, trying to beat the same paper as juniors)
* Juniors Model - MSHF-EagleFormer-CD, Need to understand it once **[1]**
* CSA-E net
* Nilay Net

### Resources?
* Param Utkarsh setup of Bhaiya Paper directory ERSUNet
* Param Utkarsh setup of juniors paper directory **[2]**
* Param Utkarsh Quick setup guide for sir laptop...pipeline from start to end **[3]**

### Runtime TO DO:
- [ ] In my paper - TTA set of operation likhna hai, Show the all model table without TTA on CSA-E Net, Write SAUnet in pytorch and find the inference time 
- [ ] In Juniors paper - Edit the model to run 32 batche size, run the evaluation(here done)

### Expected Outcomes-Jai Shree Krishna🙏:
Paper 1: CSAE Net
Paper 2: Juniors MSHF
Paper 3: Kushal Bhaiya ERSUFormer
Paper 4: Nilay Convunext
Paper 5: Juniors MSHF pe Mamba Vision
Paper 6: Thorasic Disease Wala
