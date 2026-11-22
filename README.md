## 이규민 · On-device AI / Embedded

작은 기기 위에서 실제로 도는 AI를 만듭니다.
시뮬레이션에서 잘 되던 것이 실제 기기에서는 왜 안 되는지 확인하고, 그 제약 안에서 다시 맞추는 일을 주로 해 왔습니다.

한국외국어대학교 컴퓨터전자시스템공학부 (2027.02 졸업예정) · steve918@naver.com

### 대표 프로젝트

| 프로젝트 | 한 일 | 결과 |
| --- | --- | --- |
| [**이기종 Raspberry Pi 연합학습**](https://github.com/29-min/Federated-Learning-based-Medical-Image-Classification-in-raspberry-pi)<br>졸업논문 · 단독 | 사양이 다른 Pi 3대로 실기기 클러스터 구성, 2GB에서 도는 약 100K 파라미터 CNN 설계, FedAvg·FedProx 비교, ONNX 추론 최적화 | 정확도 82.44% (중앙집중형의 96.7%)<br>추론 평균 1.36배 빠름, 정확도 손실 0% |
| [**MRI 복소수 MP-PCA 디노이징**](https://github.com/29-min/MRI-Complex-Data-Denoising-Comparison)<br>캡스톤 · 5인 팀장 | 실수·허수 부호가 잘리던 DIPY 코드를 고쳐 위상 보존, 세 도메인 × 30개 조건 비교 | 노이즈 50%에서 SNR 최대 260.8% 향상<br>수치 최고점이 눈으로는 뭉개진 영상임을 확인해 지표 한계 정리 |
| [**Luminar 사진 관리 서비스**](https://github.com/29-min/Luminar-Product-Case-Study)<br>1인 기획·개발 · 실사용 | 운영비 0원 서버리스(Next.js + Drive API), 자동 라벨링·분류, 동시 업로드 race condition 해결 | 약 70명 동아리에서 1년 넘게 사용<br>사진 취합·분류 수작업 제거 |
| [**Map Track**](https://github.com/29-min/map-track)<br>1인 기획·개발 · 진행 중 | 글·영상에 나온 맛집·장소를 뽑아 지도에 표시. LLM은 장소 추출, 지도 API는 위치 확인으로 역할을 나누고, 확신이 낮은 장소는 사용자가 고르게 설계 | 이름이 같은 다른 지역 매장이 찍히던 오류를 구조 변경으로 줄임 |

### 그 밖의 작업

- [YOLOv5 교내 혼잡도 분석](https://github.com/29-min/YOLOv5--PNP) · 학회 프로젝트, 식당 인원 집계 후 시계열 예측
- [PhotoSelect](https://github.com/29-min/PhotoSelect_tool) · 출사 사진을 키보드로 빠르게 고르는 Electron 데스크톱 앱 (RAW/JPG)
- [Content Repurposer](https://github.com/29-min/content-repurposer) · 글 하나를 채널별 SNS 포맷으로 바꾸는 풀스택 웹앱 (FastAPI)

### 기술

| 분야 | 사용 |
| --- | --- |
| AI / ML | Python, PyTorch, ONNX Runtime, Flower, YOLOv5, NumPy |
| Edge / Embedded | Raspberry Pi, Arduino, Linux |
| Web / LLM | Next.js, React, TypeScript, FastAPI, Gemini API |

### 왜 이 분야인지

학창 시절엔 휴머노이드 로봇으로 대회에 나갔고, 군에서는 기동헬기 승무원으로 복무했습니다.
편대 비행 중 인접 기체가 충돌하는 사고를 가까이에서 본 뒤로, 서버를 기다리지 않고 기기 스스로 판단하는 AI를 공부하고 있습니다.
