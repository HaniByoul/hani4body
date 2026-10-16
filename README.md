# HANI 4 BODY

**HANI 4 BODY**는 최근 2주 동안의 몸 상태를  
한의학의 **기(氣)·혈(血)·음(陰)·양(陽)** 관점에서 살펴보는  
대중용 탐색적 자가점검 웹앱입니다.

이 앱은 타고난 체질을 판정하는 검사가 아니라,  
수면·과로·스트레스·식사·운동·계절 등의 영향을 받아 달라질 수 있는  
**현재의 몸 상태**를 돌아보는 것을 목적으로 합니다.

---

## 주요 기능

- 기(氣)·혈(血)·음(陰)·양(陽) 4가지 점수 확인
- 최근 상태를 4축 레이더 차트로 시각화
- 상태별 캐릭터 뱃지 제공
- 결과 이미지 저장 및 SNS 공유
- QR코드를 통한 검사 링크 공유
- 친구에게 검사 보내기 및 결과 비교
- 같은 브라우저에서 과거 검사 기록 확인
- 필요 시 가까운 “동네한의원” 상담 안내

---

## 결과 분류 기준

현재 버전의 기본 분류 기준은 다음과 같습니다.

- 기·혈·음·양 **모두 90점 이상** → **풀밸런스**
- 기·혈·음·양 **모두 80점 이상** → **균형양호**
- 그 이하 → 부족한 축의 조합에 따라  
  **저전력, 빈 저장고, 기름 부족, 예열 필요, 과열 방전, 겨울잠, 사막, 빈 난로, 올다운** 등의 상태로 표현합니다.

이 기준은 대중용 시각화와 자기점검을 위한 현재의 운영 기준이며,  
향후 실제 참여자 데이터가 충분히 축적되면 분포와 타당도 검토를 통해 조정될 수 있습니다.

---

## 과학적·학술적 배경

HANI 4 BODY는 기존 한의학·중의학의  
기허·혈허·음허·양허 관련 설문 연구와 진단 연구를 참고해 개발한  
**탐색적 자가점검 도구**입니다.

주요 참고 연구는 다음과 같습니다.

1. **Kim J, Ku B, Kim KH.**  
   *Validation of the Qi Blood Yin Yang Deficiency Questionnaire on chronic fatigue.*  
   Chinese Medicine. 2016;11:24.  
   https://link.springer.com/article/10.1186/s13020-016-0092-y

2. **Kim J, Kim KH.**  
   *Protocol for the evaluation and validation of Qi Blood Yin Yang deficiency pattern questionnaire.*  
   Integrative Medicine Research. 2015.  
   https://pmc.ncbi.nlm.nih.gov/articles/PMC5481822/

3. **Lee S, et al.**  
   *Development and validation of Yin-Deficiency Questionnaire.*  
   American Journal of Chinese Medicine. 2007.  
   https://pubmed.ncbi.nlm.nih.gov/17265546/

4. **Zhu Y, et al.**  
   Japanese validation study of the Constitution in Chinese Medicine Questionnaire.  
   Kampo Medicine. 2008.  
   https://www.jstage.jst.go.jp/article/kampomed/59/6/59_6_783/_article/-char/en

5. **Traditional Chinese Medicine Constitution Identification Based on Objective Facial and Tongue Features.**  
   2022.  
   https://pmc.ncbi.nlm.nih.gov/articles/PMC8983216/

HANI 4 BODY의 문항과 점수체계는 위 연구들을 참고하되,  
일반인이 쉽고 재미있게 사용할 수 있도록 별도로 구성한 대중용 버전입니다.

---

## 개인정보 및 데이터 처리 원칙

HANI 4 BODY는 가능한 한 **최소한의 정보만 사용**하는 것을 원칙으로 합니다.

현재 버전에서 개인 기록 기능은 사용자의 브라우저 내부 저장공간인  
**localStorage**에 저장됩니다.

저장되는 정보는 다음 정도입니다.

- 연령대
- 성별
- 기·혈·음·양 점수
- 검사 날짜와 시간

현재 개인 검사 기록은 서버로 전송되지 않으며,  
같은 브라우저 안에서만 확인할 수 있습니다.

브라우저 데이터나 사이트 데이터를 삭제하면 기록도 삭제될 수 있으며,  
다른 기기나 다른 브라우저와 자동으로 동기화되지 않습니다.

향후 연령대·성별 비교 통계 기능을 운영할 경우에도  
이름, 전화번호, 주민등록번호, 정확한 생년월일, 얼굴사진 등  
직접 식별 가능한 개인정보는 수집하지 않는 방향을 원칙으로 합니다.

통계 기능이 활성화될 경우에는  
**“국민 평균”이 아니라 “HANI 4 BODY 참여자 중 같은 연령대·성별 기준”**으로 표시합니다.

---

## 통계 기능

연령대·성별 비교 기능은 현재 서버 연결 준비 단계입니다.

실제 참여자 데이터가 충분히 누적되기 전에는  
불안정한 평균이나 백분위를 표시하지 않습니다.

향후에는 같은 연령대·성별 참여자가 충분히 모였을 때:

- 집단 평균
- 평균과의 차이
- 백분위
- 반복 검사 변화

등을 제공할 수 있도록 설계하고 있습니다.

---

## 친구 공유와 확산

HANI 4 BODY는 건강정보를 일방적으로 읽는 것보다  
사람들이 자신의 현재 상태를 서로 비교하고 이야기할 수 있도록 설계했습니다.

검사 결과는 캐릭터 뱃지 형태로 제공되며,  
뱃지 안의 QR코드를 통해 다른 사람이 바로 검사를 시작할 수 있습니다.

---

## 웹앱

**HANI 4 BODY**

https://hanibyoul.github.io/hani4body/

---

## 한의학 관련 앱 모음

다른 한의학 관련 웹앱과 자료는 아래 공간에 계속 정리할 예정입니다.

https://cafe.daum.net/k-starmedi/W4sM

---

## 의료적 주의사항

**이 설문은 의료를 대신할 수 없습니다.**

HANI 4 BODY의 결과는 질병의 진단, 치료 여부 결정,  
의료인의 진료를 대체하기 위한 것이 아닙니다.

건강과 질병에 대한 상담이 필요하거나  
불편한 증상이 지속·반복되는 경우에는  
가까운 **“동네한의원”** 또는 적절한 의료기관을 방문하시기 바랍니다.

심한 통증, 호흡곤란, 실신, 지속되는 출혈, 고열, 급격한 체중감소 등  
응급 또는 중대한 증상이 있는 경우에는 자가점검 결과와 관계없이  
적절한 의료평가를 우선해야 합니다.

---

## 현재 개발 방향

HANI 4 BODY는 다음 방향으로 발전시키고 있습니다.

- 결과 뱃지 및 SNS 공유 기능 개선
- 친구 결과 비교
- 개인 과거 기록 확인
- 익명 참여자 통계
- 연령대·성별 비교
- 반복 측정에 따른 상태 변화 확인
- 한의학적 건강 이해를 돕는 대중 교육 콘텐츠 확장

---

## Disclaimer

HANI 4 BODY is an exploratory self-check tool for educational purposes.  
It is not a medical diagnostic device and does not replace professional medical care.
