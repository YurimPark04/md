마크다운(줄바꿈 자동으로 안됨)
# 제목 1단계
## 제목 2단계
1, 2단계와 3단계 사이 차이점: 밑줄 여부
### 제목 3단계
#### 제목 4단계
##### 제목 5단계
###### 제목 6단계

제목 1단계
=
제목 2단계
-

# 수평선
***
---
___

# 줄바꿈
줄바꿈 1번

방식(중간에 엔터를 넣는다 -> p태그와 같은 효과, 문단 구별)

줄바꿈 2번  
엔터하고 그 사이에 스페이스 두번(br처럼)

줄바꿈 3번<br> 작동함

# 서식 적용
**진하게** __진하게__ (굵게)
*기울기* _기울기_
***굵고 기울게*** ___굵고 기울게___
~~취소선~~<u>밑줄</u>
<mark>형광펜</mark>

# 인용문
> 박스로 특정 문구를 강조한다
> 내 죽음을 알리지 말라

> 첫번째 인용문
>> 두번째 인용문 (쌓으면 계속 쌓이게 된다. 제약 없음 - 권장은, 4번째까지만 괜찮음)

# 목록 (list)
> li, ol, ul
## 순서가 있는 목록
1. 하나
2. 둘
3. 셋
- 가장 최근에 등장했던, 같은 문단의 숫자 번호를 이어서 작성됨. 
3. 하나
2. 둘
1. 셋


1. 들여쓰기 하면
   1. 그 밑으로 작성된다

* 별표나
- 대시나
+ 플러스를 순서 없는 목록
    - 탭을 눌러서 혹은
    - 스페이스 2번 혹은 4번으로 들여쓰기 가능하다

한줄 코드(간단하게) : `console.log("hello world")`
여러줄 코드 : ```로 묶어준다 (이때, 언어를 기재하면, 언어에 맞는 강조점(?)을 살려준다
```
console.log("hello java")
```

```javascript
console.log("hello java")
```

```sh
git add .
echo "hello world"
```


```html
<div>
  <span>hello world</span>
</div>
```

# 테이블(표) - 제목, 구분선, 내용
|머리|
|---|
|내용|

|제목1|제목2|제목3|
|-|-|-|
|내용1|내용2|내용3|


|제목11111111111111|제목2|제목3|
|-:|:-:|:-|
|내용1|내용2|내용3|

표 내부의 스페이스는 모두 무시된다. 정렬하기 위해 스페이스X

