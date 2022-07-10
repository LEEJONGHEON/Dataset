# Dataset

# LMDB
- LMDB 변환 예시 코드: https://github.com/clovaai/deep-text-recognition-benchmark/blob/master/create_lmdb_dataset.py
- Sysmas Lightning Memory-mapped Database
- 파일 구조
## ![image](https://user-images.githubusercontent.com/54635552/178135607-9b4ddcf1-4efe-45b3-b80e-3263171a8bbe.png)
- train 폴더안에 모든 이미지 파일 이동
- train 상위폴더에 gt_train.txt 파일
## ![image](https://user-images.githubusercontent.com/54635552/178135640-0b8bf24b-ccd4-4d25-b381-fc81bbc9a6ee.png)
- 해당 파일내용은 이미지경로와 라벨값, 이미지경로와 라벨값은 \t으로 구분하며 각 문장마다 \n로 넘김
- ex) train/test1.png \t 라벨값 \n 

## 예제코드
- python3 create_lmdb_dataset.py --inputPath data/ --gtFile data/gt_train.txt --outputPath data_lmdb/train





## 출처 
- https://cvml.tistory.com/22
