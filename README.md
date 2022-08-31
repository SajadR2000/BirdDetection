# BirdDetection
This work detects birds using segmentation methods. First, I segment the input image using Felzenszwalb method. After that I compare the features (intensity histograms) of sample bird with features of each segment. If they are close, I label that segment as a bird. To remove false positives, I use morphological opoerations (reconstruction by opening).
