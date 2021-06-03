# SRGANs
J-component project for NoSQL.
We're redoing the existing State-of-art(SOA) model.

Dataset: `https://github.com/OlafenwaMoses/IdenProf/releases/download/v1.0/idenprof-jpg.zip`

### Generated Image at epoch-0 :

![img_0_0](https://user-images.githubusercontent.com/68124256/120535971-39e12580-c401-11eb-97ab-46cfcacbc942.png)

### Generated Image at epoch-2900 :

![img_2900_0](https://user-images.githubusercontent.com/68124256/120536073-567d5d80-c401-11eb-8e21-be4df3b34ec9.png)


### Comparision between image enhanced from 64x64 to 256x256 using general interpolation and SRGANs: 

![image](https://user-images.githubusercontent.com/68124256/120711250-c6ace180-c4dc-11eb-9d97-da223e83b1ea.png)


### Scores :

![image](https://user-images.githubusercontent.com/68124256/120710797-379fc980-c4dc-11eb-9642-f98f5636230e.png)

#### Overall :
Intre_ssim     0.033493
-- Gen_ssim       0.598754

Inter_mse      0.621423
-- Gen_mse        0.041707

Inter_psnr     8.287220
-- Gen_psnr      20.125588

![image](https://user-images.githubusercontent.com/68124256/120712156-ebee1f80-c4dd-11eb-980c-7984b564005e.png)

#### Overall :
Intre_ssim     0.702027
-- Gen_ssim       0.598754

Inter_mse      0.020368
-- Gen_mse        0.041707

Inter_psnr    23.594408
-- Gen_psnr      20.125588

![image](https://user-images.githubusercontent.com/68124256/120712092-d547c880-c4dd-11eb-9b77-bf22f5bca475.png)

#### Overall :
Intre_ssim     0.750940
-- Gen_ssim       0.598754

Inter_mse      0.016728
-- Gen_mse        0.041707

Inter_psnr    24.495696
-- Gen_psnr      20.125588

#### Score Scales:
-> SSIM values ranges between 0 to 1, 1 means perfect match the reconstruct image with original one.

-> MSE is a full reference metric and the values closer to zero are the better

-> The higher the PSNR, the better the quality of the compressed, or reconstructed image.


***It's obvious that, if we run for more epochs (like 10000) it'll generated more enhanced image.***
