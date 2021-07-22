---

layout: post

title: Programmers Scala Study (level 1.3)

date: 2021-07-22 14:27:00 +0100

description: Programmers coding study with programming language Scala. The difficulty selected is level 1.

tags: [programming, study, scala]

---

# 3. 체육복

## 문제 설명

도둑이 들어 체육복을 도난 당했다. 여벌의 체육복 있는 학생들이 도난 당한 친구들에게 빌려준다. (여벌 체육복이 있는 게 신기한데?) 

단, 학생들의 번호는 체격순으로 매겨져있기 때문에 바로 앞이나 바로 뒷 번호 학생만이 빌려줄수 있다.

체육복이 없으면 수업을 들을 수 없기 때문에 체육복을 빌려서 최대한 많은 학생들이 수업을 듣게 하려한다.

이때 수업을 들을 수 있는 최대 학생수는?

 ## Inputs

| Variable Name | type        | meaning                                   |
| ------------- | ----------- | ----------------------------------------- |
| n             | Int         | Number of students                        |
| lost          | Vector[Int] | indices of student who lost their clothes |
| reserve       | Vector[Int] | indices of student who has extra clothes  |

## output

~~~scala
return Int // Maximum number of students who can listen to the PE class
~~~



## Conditions

* n
  * 2~30
* lost
  * length: 1~n 
  * no duplicate numbers
* reserve
  * length: 1~n
  * no duplicate numbers
* ! there is a possibility that student who has extra lost their clothes.
  * if this is the case, this student can lend their clothes