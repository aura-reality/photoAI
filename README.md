# Photo AI

## Terms: 
  - Matting: refers to the problem of accurate foreground estimation in images and video
  - Matting vs binary segmentation:  The difference between segmentation and matting is the following: the result of segmentation is binary, which is either 0 or 1, while the result of matting is a continuous opacity, which is distributed among [0, 1]. 
  - Clipping Mask / Mask: photoshop term to cut image
  - Background extractin/subtraction
  - Foreground extraction
  - Lecture with some terms: (binary segmentation, semantic segmentation, soft segmentation) http://vision.stanford.edu/teaching/cs131_fall1314_nope/lectures/StanfordSegmentationLectureNov2013.pdf
  Tutorial on https://www.analyticsvidhya.com/blog/2019/02/tutorial-semantic-segmentation-google-deeplab/
## Blogs/Notes: 
  - https://www.jeremyjordan.me/semantic-segmentation/#loss
  - https://towardsdatascience.com/semantic-segmentation-with-deep-learning-a-guide-and-code-e52fc8958823
  - Lecture Notes: http://cs231n.github.io/
  - Tutorial on deeplab: https://www.analyticsvidhya.com/blog/2019/02/tutorial-semantic-segmentation-google-deeplab/
  
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
    ### Lighting
    - Learning to See in the Dark: https://arxiv.org/pdf/1805.01934.pdf
    - Relighting: http://cseweb.ucsd.edu/~viscomp/projects/SIG18Relighting/
    - Image based relighting using neural networks https://www.semanticscholar.org/paper/Image-based-relighting-using-neural-networks-Ren-Dong/e0ff65c1d6e8ba731265675f7a39727291a6b3c3
 ## Datasets: 
  ### Semantic Segmentation: 
  - http://videomatting.com/#datasets
  - http://www.wisdom.weizmann.ac.il/~vision/Seg_Evaluation_DB/scores.html
  - http://homepages.inf.ed.ac.uk/rbf/CVonline/Imagedbase.htm#segmentation
  - Berkeley Segmentation Dataset and Benchmark: https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/
  - COCO segmentation: http://cocodataset.org/#explore
  - ADE20K segmentation: http://groups.csail.mit.edu/vision/datasets/ADE20K/
  - PascalVOC Segmentation: http://host.robots.ox.ac.uk/pascal/VOC/voc2012/segexamples/index.html
  ### Matting/Binary Segmentation: 
  - Stanford binary segmentation: http://vision.stanford.edu/teaching/cs231b_spring1415/project.html
  - AlphaMatting dataset/competition: http://www.alphamatting.com/datasets.php  
  ### Product Data: 
  - https://pixabay.com/fr/photos/search/?colors=transparent&min_height=640&min_width=640&order=latest&pagi=2
  - https://data.world/datafiniti/mens-shoe-prices
  - https://data.world/datafiniti?
  - https://datafiniti.co
  - http://jmcauley.ucsd.edu/data/amazon/links.html
  - https://data.world/crowdflower/ecommerce-search-relevance

