<!-- 제목 -->
# Heading1
## Heading2
### Heading3
#### Heading4
##### Heading5
###### Heading6

<!-- 수평 라인 추가 --> 
___

<!-- 글씨체 -->
1. **bold**
2. *italic*
3. ~~strikethrough~~ <- ~~ ~~

<!-- 인용 -->
>Quote

<!-- 목록 -->
list 1 :
* 🍉
* 🍓
(* 뒤에 띄어쓰기 해줘야함)

list 2 :
- 🍑
- 🍋
(- 뒤에 띄어쓰기 해줘야함)

<!-- 숫자 리스트 -->
Number list :
1. first
2. second
3. third

<!-- 링크 -->
Click [here](naver.com)
<- []대괄호 안에 원하는 문장 넣고 ()소괄호 안에 링크 넣기

<!-- 이미지 추가(링크) -->
![image description](https://images.velog.io/images/gunu/post/abc4347b-d1ad-4b80-a238-e168a7a05d9e/github.png)
<- 느낌표 + []대괄호에 이미지 설명 + ()소괄호에 이미지 링크

+ pc 에 있는 이미지 드래그 해도 다음과 같이 만들어짐
![github](https://user-images.githubusercontent.com/101249847/183553610-ba27c855-48d4-41d0-82f8-b0ddc64637bf.png)

+ HTML 태그 중 하나인 이미지 태그를 이용해서 이미지 사이즈 조절 가능
<img src="https://images.velog.io/images/gunu/post/abc4347b-d1ad-4b80-a238-e168a7a05d9e/github.png" width="400">

<-- 테이블(표) -->
|Header|Description|
|--|--|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|

<- 정렬:
1. 오른쪽 정렬 : |:--|
2. 왼쪽 정렬 : |--:|
3. 가운데 정렬 : |:--:|

<!-- 코드 -->
~표시의 아래 키인 ` 백틱 키를 이용하면 `코드를 인라인 형태`로 감싸줄 수 있다. 

```
` 백틱키 3번 으로 코드블럭 생성할 수 있다.
```의 뒤에 프로그램 언어를 붙여서 랭귀지 설정도 가능하다.
```

```ts
console.log('type script')
```

```js
console.log('java script')
```

```java
console.log('java')
```

```kotlin
console.log('kotlin')
```

<!-- GitHub Flavored Markdown -->
깃허브에서는 GitHub Flavored Markdown 라는 것도 확장 지원함. 
[관련 링크](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

<!-- Task list -->
- [ ] 할일 1
- [x] 할일 2
- [ ] 할일 3
