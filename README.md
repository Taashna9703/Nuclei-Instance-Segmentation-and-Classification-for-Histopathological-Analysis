# Nuclei-Instance-Segmentation-and-Classification-for-Histopathological-Analysis
Deep learning excels in medical image analysis, especially segmenting nuclei from histopathology images. Deterministic models prioritize accuracy but lack confidence assessment. Our approach uses Deeplabv3+ for precise nuclei segmentation, addressing this limitation.


#Dataset:
This dataset, also known as PanNuke, contains semi automatically generated nuclei instance segmentation and classification images with exhaustive nuclei labels across 19 different tissue types. The dataset consists of 481 visual fields, of which 312 are randomly sampled from more than 20K whole slide images at different magnifications, from multiple data sources.
In total the dataset contains 205,343 labeled nuclei, each with an instance segmentation mask. Models trained on PanNuke can aid in whole slide image tissue type segmentation, and generalize to new tissues.

#Our usage:
We used only one folder fold1 for masks.npy, images.npy and labels.npy
The data was vast, and dur to limitations of resources available to us, we performed with only 2000 images and 2000 masks.

#The results:
Train Loss: 0.306
Val Loss: 0.476
Train mIoU:0.501 
Val mIoU: 0.395 
Train Acc:0.890 
Val Acc:0.830

# I won 2nd place in the esteemed National level Data Science Challenge 2.0 jointly organized by IEEE SPS SCET SBC, IEEE SCET SB and SIP Club with Deeplabv3+ approach
