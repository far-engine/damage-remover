# damage-remover

Detect and remove (via inpainting) cracks in crystals of heterogeneous energetics (HE). 

Input - grayscale HE microstructure images (100-500 microns) image. 
Output - same image, with cracks removed. 

## Progress and Updates

**3/31/2021** - Initial data transform pipeline added
**4/23/2021** - U-Net implemented
**4/24/2021** - Dataset expanded, images resized 

## dataset 

- `he_images_base` is the raw image files
- `he_images_subsampled_with_base` includes the raw image files, with 256x256 samples of portions of them 
- `he_images_subsampled_without_base` is features the 256x256 subsamples, without the original images
