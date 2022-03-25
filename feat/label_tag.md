## label 태그로 input 태그 인식범위 넓히기

- label 태그로 input 태그를 감싸줌

<br />

> ### 명시적 방법   

- for 속성에 input 태그의 id를 할당하면 명시적으로 연결해 줌. 주로 사용되는 방식.

```
<label for="input-id">아이디를 입력해주세요<label />
<input id="input-id" />
```

<br />

> ### 암묵적 방법

- label 태그 안에 input 태그를 아예 넣어주면 id 값을 주지 않아도 됨. 단 호환성 문제로 위의 방식이 선호됨.

```
<label>                   
  아이디를 입력해주세요
  <input />
</label>

```
