---

layout: post

title: Programmers Scala Study (level 1.5)

date: 2021-07-22 14:27:00 +0100

description: Programmers coding study with programming language Scala. The difficulty selected is level 1.

tags: [programming, study, scala]

---

# 5. 문제

## 문제 설명

 ## Inputs

| Variable Name | type | meaning |
| ------------- | ---- | ------- |
|               |      |         |
|               |      |         |
|               |      |         |

## output

~~~scala

~~~



## Conditions

* 

## Test cases

| n    | lost | reserve | return |
| ---- | ---- | ------- | ------ |
|      |      |         |        |
|      |      |         |        |
|      |      |         |        |

## Solution



### 1차 solution

### 2차 solution

### 추가 수정! Idea from Others

~~~scala
var updated_lost = lost.filterNot(idx => reserve.exists(v => v == idx))
var updated_reserve = reserve.filterNot(idx => lost.exists(v => v == idx))
~~~

이 두개를 필터링 하지 않고 set의 diff로 구하는 방법도 있다.

~~~scala
var updated_lost = lost.diff(reserve)
var updated_reserve = reserve.diff(lost)
~~~



## Study from Implementation

* 
