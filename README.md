# 260818 PHM Korea Code Example

와이어 하네스 압착공정에서 수집된 실제 Crimp Force Monitoring(CFM) 데이터를 이용해 정상/불량 공정을 분석하는 강습회용 JupyterLite 코드 예제입니다.  
데이터 리뷰부터 AutoEncoder 기반 Reconstruction Error 계산, 현장 데이터 적용, Drift 보정 실험까지 브라우저에서 직접 실행해볼 수 있습니다.

## 바로 실행

아래 링크를 통해 Chrome 또는 Edge 브라우저에서 바로 실행할 수 있습니다.

- [JupyterLite Lab 열기](https://jwsong0620.github.io/260818_PHMKorea_CodeExample/lab/index.html)

## 노트북 순서

1. `0_DataReview.ipynb`: 데이터 읽기, 요약, 파형 확인
2. `1_Prototype.ipynb`: 10AWG/24AWG AutoEncoder prototype
3. `2_FieldDataPrototype.ipynb`: 날짜별 현장 데이터 AutoEncoder 적용
4. `3_DriftPrototype.ipynb`: Drift 보정 기반 AutoEncoder

## 데이터

예제 데이터는 `content/data` 폴더에 포함되어 있습니다.

- `10AWG.csv`
- `24AWG.csv`
- `20230420.csv`
- `20230426.csv`
