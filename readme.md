# 프로젝트 기간
2024/1/29~2024/1/30

# 프로젝트 소개
공공데이터 분석을 통해 취업 시장을 분석해보자

# 팀원 내용(클릭시 상세 내용 확인 가능)
<details>
<summary> 김규량 <a href="https://github.com/KimGyuR" height="5" width="10" target="_blank">
	<img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/><a> : 국민연금으로 보는 기업 성장 추이 / ppt 04p~11p </summary>
<div markdown="1">
내용추가해주세요
</div>
</details>

<details>
<summary> 이윤서 <a href="https://github.com/voo0o08" height="5" width="10" target="_blank">
	<img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/><a> : 국민연금으로 보는 지역별 급여 분석 / ppt 12p~26p </summary>
<div markdown="1">
  
## 국민연금으로 보는 지역별 급여 분석

→ 국민 연금은 급여의 9%가 고지되며, 월급여 역추정 가능
단, 급여 상한액 : 5,240,000

### ✏️ 2020~2024 지역별(시도별) 국민연금 고지금액

빨간 색 : 광역시

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/fd027132-ee61-48b5-a7a2-858df68e856a)

- 울산 : 지방임에도 불구하고 현대중공업과 같은 선박관련 산업으로 평균 국민연금 고지금액이 높음
- 서울/경기 : 예상대로 순위가 높음
- 부산/대구/광주 : 광역시임에도 불구하고 급여가 낮다는 것을 알 수 있음

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/774c3afe-71ef-4133-9c62-0004203ebf06)

- 평균 고지금액 상승 = 평균 월급 상승
- 순위는 큰 차이 없음

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/e4e9a88a-2384-43b4-8628-826612dd7c25)

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/401bd846-cf62-4a78-9207-435d327ab9d1)

- 현대엘리베이터 본사 이전으로 충청북도 순위 상승

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/26993e5a-9d27-47d6-839a-fbd6276e8f2d)

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/a3ba71bd-f208-4ac0-8afa-364da884f913)

- 부산/대구/광주 : 광역시임에도 임금이 크게 상승되지 않는 것을 알 수 있음

```
**결론**
-대구, 부산, 광주는 광역시임에도 불구하고 비교적 급여가 낮음을 알 수 있음

-해마다 국민연금 고지 금액 평균이 늘어나는 것을 보아, 평균 급여가 늘어나는 것을 알 수 있음
```

### ✏️ 2024년 지역별(군구별) 국민연금 고지금액

빨간색 : 수도권 / 광역시가 아닌 지역

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/e0150c20-55f9-4fdb-8e66-18b4817d670c)

2024년도 1월 기준, 군구 단위 top10

- 지방 : 한전/수자원공사 -> 공기업 
현대제철, 포스코, 현대트랜시스 -> 제조업
- 지방은 공기업, 대기업 지사가 아니면 군구 Top에 들기 힘듦

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/48bd1dfc-4702-4ecd-8cb4-5834c18adba6)

수도권 자료를 제외한 자료만 보았을 때,

- 공기업 : 한전, 발전소, 수자원공사, 강원랜드 …
- 대기업 지사 : 현대 …
- 지방이 본사 : 포스코, 부산은행, HMM(항구)

```
**결론**
공기업과 대기업을 제외하면 본사를 지방에 둔 기업은 연봉 Top에는 보기 힘든 것을 알 수 있음
```

### ✏️ SW 업체만 분류했을 때 고지금액 차이

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/62be4659-ca38-4448-806e-e71e28d1badb)

전체 업체 포함 : 266,825 원

SW 업체만 : 285,059원

국민 연금 고지 금액 차이 : 18,234
급여차이 : 202,600

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/21204f92-07ec-47a2-a84f-f50c42302b7e)

전체 업체 포함 : 275,286 원

SW 업체만 : 294,610 원

국민 연금 고지 금액 차이 : 19,354
급여 차이 : 215,044

![image](https://github.com/voo0o08/KDT5_PublicData_PROJECT/assets/155411941/2441789c-c176-4364-80b9-1cd40987adb8)

전체 업체 포함 : 299,164 원

SW 업체만 : 318,597 원

국민 연금 고지 금액 차이 : 19,433
급여 차이 : 215,922

```
**결론**
전체 업체와 SW업체의 국민연금 고지금액을 비교해보았을 때, 
고지금액 격차가 커짐을 알 수 있었음

SW업체만 걸러도 대구/부산/광주의 연봉은 낮음을 알 수 있음
```

---

## 개인 결론

급여를 많이 받고 싶다면?! 수도권 / 대기업 SW업체로 취업하는 것이 좋음
</div>
</details>

<details>
<summary> 변주영 <a href="https://github.com/rileybyun" height="5" width="10" target="_blank">
	<img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/><a> : 미국 산업별 임금 동향 / ppt 27p~36p </summary>
<div markdown="1">
내용추가해주세요
</div>
</details>

<details>
<summary> 이화은 <a href="https://github.com/Skylee0310" height="5" width="10" target="_blank">
	<img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/><a> : 데이터 분석가 직무 취업 준비 / ppt 37p~52p </summary>
<div markdown="1">
내용추가해주세요
</div>
</details>
