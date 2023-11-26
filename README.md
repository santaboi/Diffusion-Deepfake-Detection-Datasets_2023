# Diffusion-Deepfake-Detection-Datasets_2023
Since there is no conventially selected DFD benchmarks hitherto, this repository is a thorough survey of useful diffusion deepfake detection datasets to foster further researches.

## :mag_right: Diffusion Deepfake Detection Datasets
1. **DiffusionForensics (ICCV'23)**
    * Paper: https://arxiv.org/abs/2303.09295
    * Github: https://github.com/ZhendongWang6/DIRE
    * Generation Models: Diffusion Models, GAN
    * Type: **General**
    * Potential Issues: **Real,Fake image size and image type mismatched**
2. **ArtiFact (ICIP'23)**
    * Paper: https://arxiv.org/abs/2302.11970
    * Github: https://github.com/awsaf49/artifact
    * Generation Models: Diffusion Models, GAN
    * Type: **General**
3. **DeepFakeFace (arXiv'23)**
    * Paper: https://arxiv.org/abs/2309.02218
    * Github: https://github.com/OpenRL-Lab/DeepFakeFace
    * Generation Models: Stable Diffusion
    * Type: **Face**
4. **GenImage (arXiv'23)**
    * Paper: https://arxiv.org/abs/2306.08571
    * Github: https://github.com/GenImage-Dataset/GenImage
    * Generation Models: Stable Diffusion
    * Type: **General**
5. **CIFAKE (arXiv'23)**
    * Paper: https://arxiv.org/pdf/2303.14126.pdf
    * Github: -
    * Kaggle: https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images
    * Generation Models: SDM(LDM)
    * Type: **General** (Follow CIFAR-10)
6.  **DMimageDetection (ICASSP'23)**
    * Paper: https://arxiv.org/abs/2211.00680
    * Github: https://github.com/grip-unina/DMimageDetection
    * Generation Models: Diffusion Models, GAN
    * Type: **General** 
    * Potential Issues: **Real parts should be downloaded from IMAGENET,COCO,UCID on your own.(Possible mismatch subset based on your own selection)** 
7.  **Towards the Detection of Diffusion Model Deepfakes (arXiv'22)**
    * Paper: https://arxiv.org/pdf/2210.14571.pdf
    * Github: https://github.com/grip-unina/DMimageDetection
    * Generation Models: Diffusion Models, GAN
    * Type: **General** 
    * Potential Issues: **You have to recreate the train and validation set on your own** 


## :milky_way: Other synthetic Data by Diffusion Models 
1. **(SFHQ)Synthetic Faces High Quality**
    * Paper: -
    * Github: https://github.com/SelfishGene/SFHQ-dataset
    * Kaggle: 
        * Part2: https://www.kaggle.com/datasets/selfishgene/synthetic-faces-high-quality-sfhq-part-2
        * Part3: https://www.kaggle.com/datasets/selfishgene/synthetic-faces-high-quality-sfhq-part-4
    * Generation Models: 
        * Part2: Stable Diffusion v1.4
        * Part4: Stable Diffusion v2.1
    * Type: **Face**

## Acknowledgement
Sincerely appreciate for all the contributions from original authors. If you find there are any needed updates, please feel free to fork and pull request.