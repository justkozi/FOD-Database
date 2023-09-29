# Foreign Object Debris (FOD) dataset

The directory structure containing the dataset is as follows:

  - Images
    - *training* - sets of images used for training neural networks, categorized by resolution. Folders labeled PASCAL_VOC contains additional XML information about location of FOD,
      - 256x256
      - 400x400
      - 4272x2848
      - 256x256_PASCAL_VOC
      - 400x400_PASCAL_VOC
      - 640x640_PASCAL_VOC
    - *testing* - sets of images used for testing neural networks and classical methods, categorized by resolution,
      - 256x256
      - 400x400
      - 4272x2848
  - *Videos* - sets of recordings used for testing neural networks and classical methods.
    - REC_1.MP4
    - REC_2.MP4
    - REC_3.MP4
    - REC_4.MP4
    - REC_5.MP4
    - REC_6.MP4


This dataset was created as part of MSc thesis: 
Weronika Leśna, Łukasz Kozak "Automatic visual detection of FOD on airport surfaces", Supervisor: Tomasz Marciniak, Poznan University of Technology, 2023.
