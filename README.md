# Mask_RCNN

1. mask_rcnn 공식 github에서는 python 3.6을 권장하고 있지만 anaconda에서 최소가 3.7이기에 3.7로 가상환경을 생성하였습니다.
2. Mask_RCNN 파일 내부에 추가로 https://github.com/matterport/Mask_RCNN/releases에서 제공하고 있는 balloon datasets을 추가하였습니다.
3.  https://github.com/matterport/Mask_RCNN/releases에서 제공하는 mask_rcnn_balloon.h5 파일과 mask_rcnn_coco.h5 파일도 추가하였습니다.
4. datasets/train의 18849792632_aad23ad513_k.jpg와 datasets/val의 3800636873_ace2c2795f_b.jpg를 Mask_RCNN을 활용하여 객체탐지하여 결과물을 samples/balloon 폴더에 splash_20231123T175049.png와 splash_20231123T200356.png로 저장하였습니다.
5. h5 모델은 용량이 매우 커서 lfs를 사용하여도 push가 되지 않아, h5모델은 github에 저장하지 않았습니다.
