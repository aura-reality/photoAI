# Photo AI

## Terms: 
  - Matting: refers to the problem of accurate foreground estimation in images and video
  - Matting vs binary segmentation:  The difference between segmentation and matting is the following: the result of segmentation is binary, which is either 0 or 1, while the result of matting is a continuous opacity, which is distributed among [0, 1]. 
  - Clipping Mask / Mask: photoshop term to cut image
  - Background extractin/subtraction
  - Foreground extraction
  - Lecture with some terms: (binary segmentation, semantic segmentation, soft segmentation) http://vision.stanford.edu/teaching/cs131_fall1314_nope/lectures/StanfordSegmentationLectureNov2013.pdf
  
## Papers: 
  - Overview of common matting techniques: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8110616
  - Foreground Segmentation in Images and Video: Methods, Systems and Applications 2007: https://www.juew.org/publication/JuePhdThesis.pdf
  - Flashcut: using flash/noflash image pair to extract foreground: https://www.researchgate.net/publication/4260039_Flash_Cut_Foreground_Extraction_with_Flash_and_No-flash_Image_Pairs
  - Deep Matting: https://arxiv.org/pdf/1703.03872.pdf
  - AlphaGAN: gan for matting https://arxiv.org/pdf/1807.10088.pdf
  - Image and Video Matting: A Survey (2007) http://juew.org/publication/mattingSurvey.pdf
  - Sample images from vertus: https://www.vertustech.com/imggallery/
  - Interactive Foreground Extraction with Superpixels http://ee.cooper.edu/~keene/assets/rafi_thesis.pdf
  - Medium article describing some nn segmentation models: https://towardsdatascience.com/background-removal-with-deep-learning-c4f2104b3157
  - Video, look at frames, remove moving objects: 
    - Deep Background Subtraction: - https://orbi.uliege.be/bitstream/2268/195180/1/Braham2016Deep.pdf
    - A Deep Convolutional Neural Network for Background Subtraction: https://arxiv.org/pdf/1702.01731.pdf
    - TriMap creation: https://arxiv.org/pdf/1707.00333.pdf
 ## Datasets: 
  - Berkeley Segmentation Dataset and Benchmark: https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/
  - COCO segmentation: http://cocodataset.org/#explore
  - ADE20K segmentation: http://groups.csail.mit.edu/vision/datasets/ADE20K/
  - Foreground dataset: http://www.robots.ox.ac.uk/~vgg/data/iseg/
  - alpha matting dataset/competition??: http://www.alphamatting.com/datasets.php Looks like gold. 
  - pascalVOC: http://host.robots.ox.ac.uk/pascal/VOC/
  
