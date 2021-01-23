# Video compressive sensing via weighted residual tensor decomposition
We compare the proposed method (WRTD-VCS) with KTSLR[1], MCME[2], Video-MH[3], RRS[4], VCSNet[5]. [1]-[4] are taditional model-based methods and [5] is a recently proposed CNN-based methd. Six sequences are used to evaluate the proposed method.   
# Results
## The sampling rate of key frames and non-key frames are 0.5 and 0.2, respectively.

**Average PSNR for  seven GOPs of different methods**  

|  Sequences | KTSLR |  MCME | Video-MH |  RRS  | VCSNet-1 | VCSNet-2 | Proposed |
|:----------:|:-----:|:-----:|:--------:|:-----:|:--------:|:--------:|:--------:|
|    Akiyo   | 35.97 | 38.30 |   39.97  | 44.45 |   40.80  |   41.14  |   **45.99**  |
| Coastguard | 27.75 | 29.03 |   30.38  | 31.99 |   32.12  |   32.53  |   **32.77**  |
|   Foreman  | 31.95 | 33.45 |   35.85  | 37.98 |   35.32  |   35.59  |   **39.69**  |
|   Mother   | 36.29 | 39.35 |   40.41  | 43.53 |   42.35  |   42.44  |   **44.79**  |
|    Paris   | 24.89 | 26.37 |   26.21  | 31.52 |   27.89  |   28.46  |   **33.78**  |
|   Silent   | 31.50 | 33.47 |   34.04  | 36.14 |   36.39  |   36.44  |   **36.88**  |
|   Average  | 31.39 | 33.33 |   34.48  | 37.60 |   35.81  |   36.10  |   **38.98**  |

**Average SSIM fo seven GOPs of different methods**  

|  Sequences |  KTSLR |  MCME  | Video-MH |   RRS  | VCSNet-1 | VCSNet-2 | Proposed |
|:----------:|:------:|:------:|:--------:|:------:|:--------:|:--------:|:--------:|
|    Akiyo   | 0.9535 | 0.9696 |  0.9714  | 0.9859 |  0.9797  |  0.9807  |  **0.9889**  |
| Coastguard | 0.7117 | 0.7966 |  0.8411  | 0.8742 |  0.8720  |  0.8823  |  **0.8940**  |
|   Foreman  | 0.8949 | 0.9103 |  0.9303  | 0.9517 |  0.9426  |  0.9456  |  **0.9611**  |
|   Mother   | 0.9321 | 0.9586 |  0.9615  | 0.9786 |  0.9736  |  0.9743  |  **0.9830**  |
|    Paris   | 0.8007 | 0.8466 |  0.7887  | 0.9470 |  0.9044  |  0.9101  |  **0.9599**  |
|   Silent   | 0.8534 | 0.8960 |  0.9004  | 0.9297 |  0.9445  |  **0.9443**  |  0.9421  |
|   Average  | 0.8577 | 0.8963 |  0.8989  | 0.9445 |  0.9361  |  0.9396  |  **0.9548**  |

## Visual comparisons of first phase.

###


# References
[1] S. G. Lingala, Y. Hu, E. Dibella, and M. Jacob, “Accelerated dynamic mri exploiting sparsity and low-rank structure: k-t slr,” IEEE Transactions on Medical Imaging, vol. 30, pp. 1042–1054, January 2011.  
[2] S. Mun and J. E. Fowler, “Residual reconstruction for block-based compressed sensing of video,” in Data Compression Conference (DCC). IEEE, 2011, pp. 183–192.  
[3] E. W. Tramel and J. E. Fowler, “Video compressed sensing with multihypothesis,” in Data Compression Conference (DCC). IEEE, 2011, pp. 193–202.  
[4] C. Zhao, S. Ma, J. Zhang, R. Xiong, and W. Gao, “Video compressive sensing reconstruction via reweighted residual sparsity,” IEEE Transactions on Circuits and Systems for Video Technology, vol. 27, pp. 1182–1195, June 2017.  
[5] W. Shi, S. Liu; F. Jiang and D. Zhao, "Video compressed sensing using a convolutional neural network," IEEE Transactions on Circuits and Systems for Video Technology, March 2020.        
