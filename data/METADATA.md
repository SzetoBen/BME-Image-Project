***Metadata***

**Data Set Link** \
https://universe.roboflow.com/uni-o612z/facial-emotion-recognition

**Data Summary** \
The dataset used in this project was obtained from the Roboflow Universe platform and published by the user uni-o612z. It contains labeled facial images categorized by emotional expression, including happy, sad, angry, surprised . Each sample consists of an image paired with an emotion label, and all images have been preprocessed into a consistent resolution suitable for computer vision tasks. The dataset is accessible online via Roboflow’s hosted version or through their API.

**Provenance** \
The dataset was originally uploaded to Roboflow Universe in 2024 and continues to be available as a public project. It aggregates facial expression samples from openly available emotion recognition datasets and was cleaned and standardized using Roboflow’s preprocessing tools, including resizing and bounding-box labeling. The dataset is tagged with the following descriptors: Facial Emotion Recognition, Computer Vision, Affective Computing, Human Emotion Classification, Roboflow Universe. It can be accessed directly on Roboflow Universe under the Facial Emotion Recognition project page.

**License** \
This dataset is published under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. This license permits anyone to share, adapt, and build upon the data, including for commercial purposes, as long as proper attribution is provided and any changes are clearly indicated. The dataset may be used freely within academic research, machine learning model training, and derivative works.

**Ethical Statements** \
The dataset contains facial images sourced from publicly available emotion recognition repositories intended for research use. All images contain faces but no personally identifying metadata such as names, locations, or demographic identifiers beyond the visual content itself. Users should exercise caution when deploying emotion recognition models, as affective computing can raise ethical concerns regarding surveillance, consent, demographic bias, and psychological inference. This project uses the dataset exclusively for educational and research purposes, and no models will be applied to real-time surveillance or individual profiling.

**Data Dictionary** \
Feature, Description, Possible Responses
image, The facial image used as input for model training, 48×48 grayscale image or 48×48 RGB image depending on version
label, The annotated emotional category assigned to the image, angry, disgust, fear, happy, neutral, sad, surprise
split, Indicates which dataset partition the sample belongs to, train, valid, test

See data folder for exploratory plots images \
Fig 1: Distribution of images across four emotion labels \
Fig 2: Histogram of aggregated counts for number of unique categories in each training image