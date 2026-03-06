# 일본 도시 속성 조회하기

[문제 링크](https://www.hackerrank.com/challenges/japanese-cities-attributes/problem?isFullScreen=true)

### 플랫폼
HackerRank

### 난이도
Easy

### 유형
SQL - Basic Select

---

## 문제 설명

Query all attributes of every Japanese city in the `CITY` table. The `COUNTRYCODE` for Japan is `JPN`.

---

## 테이블 구조

| Field | Type |
|------|------|
| ID | NUMBER |
| NAME | VARCHAR2(17) |
| COUNTRYCODE | VARCHAR2(3) |
| DISTRICT | VARCHAR2(20) |
| POPULATION | NUMBER |

---

## 출력 결과
```
1613 Neyagawa JPN Osaka 257315
1630 Ageo JPN Saitama 209442
1661 Sayama JPN Saitama 162472
1681 Omuta JPN Fukuoka 142889
1739 Tokuyama JPN Yamaguchi 107078
```