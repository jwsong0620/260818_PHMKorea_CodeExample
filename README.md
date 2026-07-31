# 260818 PHM Korea Code Example

Crimp Force Monitoring(CFM) 데이터를 이용해 정상/불량 공정을 판별하는 강습회용 JupyterLite 예제입니다.

## 바로 실행

GitHub Pages 배포 후 아래 링크에서 브라우저로 바로 실행할 수 있습니다.

- [JupyterLite Lab 열기](https://jwsong0620.github.io/260818_PHMKorea_CodeExample/lab/index.html)

## 노트북 순서

1. `0_DataReview.ipynb`: 데이터 읽기, 요약, 파형 확인
2. `1_Prototype.ipynb`: 10AWG/24AWG AutoEncoder prototype
3. `2_FieldDataPrototype.ipynb`: 날짜별 현장 데이터 AutoEncoder 적용
4. `3_DriftPrototype.ipynb`: Drift 보정 기반 Reconstruction Error 확인

## 데이터

예제 데이터는 `content/data` 폴더에 포함되어 있습니다.

- `10AWG.csv`
- `24AWG.csv`
- `20230420.csv`
- `20230426.csv`
