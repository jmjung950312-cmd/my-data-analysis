# 데이터 분석 포트폴리오

이정모 · Data Analyst / AI Engineer

부트캠프 캡스톤으로 진행한 데이터 분석 프로젝트 3종입니다.
EDA(탐색적 데이터 분석)부터 머신러닝 모델링, 대시보드 배포까지 End-to-End로 수행했습니다.

---

## 1. 서울 에어비앤비 호스트 수익 최적화

서울 25개 자치구 32,061개 리스팅 데이터로 RevPAR(객실당 매출)을 예측하고 호스트 수익 최적화 전략을 도출했습니다.

- LightGBM 2-Stage 앙상블(ADR + 예약률 분리 예측) + Isotonic Regression 보정 → RevPAR 예측 Test R² 0.64
- K-Means 클러스터링으로 4개 시장 유형 분류, 자치구별 차별화 전략 도출
- Streamlit 인터랙티브 대시보드 라이브 배포 (5단계 위자드 + 6개 분석 탭)
- 슈퍼호스트 RevPAR 프리미엄 +83.1%를 데이터로 검증

기술: Python · LightGBM · scikit-learn · SHAP · Streamlit

- 코드: https://github.com/jmjung950312-cmd/seoul-airbnb-revpar-optimization
- 라이브 대시보드: https://revmax-for-hosts.streamlit.app/

---

## 2. Google Merchandise Store 매출 전환 분석

Google Analytics 90만 세션(903,530행) 데이터로 채널별 전환 효율 격차를 통계적으로 검증하고 마케팅 예산 재배분 전략을 수립했습니다. (4인 팀 프로젝트)

- 통계 검정 3종 수행: Kruskal-Wallis / Z-Test / Chi-squared + 효과 크기 보고
- 채널별 전환 퍼널 이탈 구간 분석 — 추천 유입 5.08% vs 소셜 0.06% (85배 격차)
- BigQuery 원본 데이터 추출 + 전처리 파이프라인 설계
- 사용자 가치 세그먼트 설계 및 마케팅 전략 제안

기술: Python · pandas · scipy · BigQuery · seaborn

- 코드: https://github.com/jmjung950312-cmd/google-merchandise-store-analysis

---

## 3. LendingClub 대출 부도 예측 & 투자 포트폴리오 전략

226만 건 P2P 대출 데이터로 부도 예측 모델 3종을 비교하고 투자자 관점의 최적 포트폴리오 전략을 도출했습니다. (팀 프로젝트)

- 모델 3종 비교: Logistic Regression / Random Forest / LightGBM
- SHAP 기반 모델 해석 + 피처 중요도 분석
- 등급별 리스크-수익률 분석, 이자율 26.8% 임계점 발견
- 수익 시뮬레이션 기반 투자 포트폴리오 전략 도출

기술: Python · LightGBM · SHAP · scikit-learn · seaborn

- 코드: https://github.com/jmjung950312-cmd/lendingclub-default-prediction

---

## 기술 스택

Python · pandas · NumPy · scikit-learn · LightGBM · SHAP · scipy · Streamlit · BigQuery · matplotlib · seaborn

## 연락

- 포트폴리오 사이트: https://jmjung950312-cmd.github.io/my-profile-site/
- GitHub: https://github.com/jmjung950312-cmd
- Email: jmjungtube@gmail.com
