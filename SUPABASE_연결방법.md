# HANI 4 BODY 실제 연령·성별 통계 연결

앱은 서버가 없어도 정상 작동합니다. 서버가 연결되지 않은 동안에는 브라우저 내부 기록을
'집단 통계'라고 표시하지 않고, 통계 준비 중이라고만 보여줍니다.

## Supabase 연결 절차
1. Supabase에서 새 프로젝트를 만듭니다.
2. SQL Editor에서 `supabase_setup.sql` 전체를 실행합니다.
3. Project Settings → API에서
   - Project URL
   - anon / publishable key
   를 확인합니다.
4. `index.html`에서 아래 두 줄에 값을 넣습니다.

```js
const SUPABASE_URL = '여기에 Project URL';
const SUPABASE_ANON_KEY = '여기에 anon/publishable key';
```

5. GitHub에 다시 올립니다.

## 개인정보 최소화
서버에는 연령대, 성별, 기·혈·음·양 점수, 생성시각만 저장하도록 구성했습니다.
이름, 전화번호, 생년월일, 사진은 저장하지 않습니다.

## 백분위
같은 연령대·성별 표본이 100건 이상일 때만 백분위를 표시하도록 앱에 설정되어 있습니다.
