# Making segmentation mask using CelebAMask-HQ dataset

There are masks that annotated with all facial component correspond to CelebA-HQ dataset. But it was neither merged nor colored. So I decided to merge all separated masks and colored them by components. 

I found a github page that has those codes. Although I could visit that page directly to get codes, I wanted to get the codes easily. So I organized it.

## Dataset

* CelebA-HQ - [download link](https://github.com/switchablenorms/CelebAMask-HQ)

## Codes

* merge_mask.py - [link](https://github.com/ji-in/CelebAMask-HQ_to_colorImage/blob/main/merge_mask.py)

  It merges masks

* get_color.py - [link](https://github.com/ji-in/CelebAMask-HQ_to_colorImage/blob/main/get_color.py)

  It colors masks by components(eyes, lips, skin, ...)

## Reference

https://github.com/TracelessLe/FaceParsing.PyTorch