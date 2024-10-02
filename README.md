# classification-AI-generated-news
이 프로젝트는 AI 생성 뉴스와 실제 뉴스를 분류하는 모델을 개발하는 것을 목표로 합니다. 트랜스포머 모델을 사용하여 사용하여 분류 성능을 평가합니다.
학습 간 KoBart, KoELECTRA 모델을 사용하였고, 두 모델을 앙상블한 결과까지 총 3개의 결과를 출력합니다.

## 파일 구조
- `data/`: 학습 및 테스트 데이터셋
- `notebooks/`: Jupyter 노트북 파일 (모델 학습 및 평가)

## 설치 및 실행 방법
1. 레포지토리 클론:
   ```bash
   git clone https://github.com/yhyh4420/classification-AI-generated-news.git

## 데이터 설명
1. 본 데이터는 AI HUB의 '뉴스 기사 기계독해 데이터'의 일부와 해당 데이터를 기반으로 GPT-3.5-turbo모델을 기반으로 재작성한 기사로 구분됩니다.
2. 원데이터는 라벨링 0, AI 생성 기사는 라벨링 1로 구분했습니다.
