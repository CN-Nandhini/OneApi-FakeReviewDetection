# Leverage OneAPI to Identify Fake Reviews for e-marketplace using NLP techniques
### This project is based on Online Intel Hackaton on Open Innovation
To design a unified framework to implement Fake Reviews Identification using ML and DL accelerations on Intel Hardware

# Features of Intel OneAPI
* Helps developers in creating high performance applications for HPC, AI and IoT.
* Simplifies application development across different hardware platforms (CPU, GPU, FPGA).
* Provides unified API's to write applications in high-level, hardware agnostic manner without rewriting the code.
* Provides optimization tools to optimize application for specific hardwares.
 
# Importance of Fake Reviews Identification
## Role of reviews in e-marketplace
Nowadays customers relies on a particular product based on the reviews available on the
online e-commerce site. The growth of social media allows everyone to express their opinions
about the product without any restrictions and it reaches the maximum people. 
* It affects the customer’s purchase decision.
* Positive Reviews - promotes a company's product.
* Negative Reviews - helps the manufacturer to improve their quality. 
## Fake Reviews and their Impacts
* Fake Reviews - Spammers express deceptive opinions without using the product.
* Used as a tool to express false opinions against competitor’s product.
* Fake Reviews - mislead the consumers and it affects the product reputation.

# Dataset
* Adapted from Salminen, Joni, et al. "Creating and detecting fake reviews of online products." Journal of Retailing and Consumer Services 64 (2022): 102771.
* Key Fields in the dataset 
---------------------------------------------------------
|       Fields  |    Description                         |
| ------------- | ---------------------------------------|
| Category      | Books, Kitchen, Electronics            |
| Label         | CG (Computer Generated), OR (Original  |
| Rating        | Rating for the product (1 to 5 (high)  |
| Review Text   | Review about the product               |
----------------------------------------------------------
# Proposed Methodology

![oneAPI logo 11](https://user-images.githubusercontent.com/126956038/227208516-04ce405a-10cc-4307-b872-b7fdfd9abcfc.jpg)
# Results 
![graph1](https://user-images.githubusercontent.com/126956038/227219087-2bb94e95-c658-41a2-92e8-74489845ffb0.png)


# OneAPI Learnings:
## Hands-on 
* OneAPI devcloud - using Jupyterlab integrated with oneAPI kernel for python development.
* Sklearnex patching techniques - provides acceleration using familiar scikit-learn package for machine learning frameworks.
* Python daal4py API - that provides abstract to oneDAL.
## Good to know about
* Modin pandas - for accelerating distributed dataframe using existing pandas framework.
* Neural compressor - for model compression using quantization, speed up the inference for deployment benefits.
