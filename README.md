# CS292F_Project

## Environment setup
Create and activate conda environment named ```ldm``` from ```environment_cs292.yml```
```sh
cd CS292F_Project
conda env create -f environment_cs292.yml
conda activate ldm
```

Install Stable Diffusion v1.4 (under the diffusion_sd1/ directory), download checkpoint (sd-v1-4.ckpt), and place it under the ```codes/diffusion_sd1/stable-diffusion/models/ldm/stable-diffusion-v1/``` directory.

All reconstructed images are availble: [TODO]

note: I hard-coded some file paths, please do 
```sh
grep -r '/hdd/yuchen'
```
and change file paths accordingly to make sure everything is stored in the intended location



