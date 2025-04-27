# l1met-regression

/project_root/
│
├── config/
│   └── config.yaml         # 설정 파일 (모델 구조, 학습 파라미터 등)
│
├── data/
│   ├── dataloader.py        # 데이터셋 로딩, 전처리 정의
│   └── transforms.py        # 데이터 변환(Augmentation 등)
│
├── models/
│   ├── met_regressor.py     # MET 예측용 모델 정의
│   └── __init__.py          # 다양한 모델 import 관리
│
├── trainers/
│   └── trainer.py           # 학습 루프(Training loop) 관리
│
├── utils/
│   ├── metrics.py           # Bias, Resolution 계산 함수
│   ├── logger.py            # 로깅 관련 유틸
│   └── helpers.py           # 기타 편의 함수
│
├── scripts/
│   ├── train.py             # 학습 실행 스크립트
│   └── eval.py              # 평가용 스크립트
│
├── outputs/
│   ├── models/              # 저장된 학습 모델
│   ├── logs/                # 로그 파일
│   └── plots/               # 학습 결과 플롯
│
└── README.md                # 프로젝트 설명
