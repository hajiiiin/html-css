# 부트스트랩 이용하여 랜딩 페이지 만들기

### 모바일 버전
![image](https://user-images.githubusercontent.com/101108440/220680188-0dd57668-d217-439a-838e-941316325d24.png)
![image](https://user-images.githubusercontent.com/101108440/220680267-5b2dc75c-6809-4c5c-851c-ac37d08b4e4a.png)

### pc 버전
![image](https://user-images.githubusercontent.com/101108440/220680369-0b73c85f-9ba6-488e-ba4d-9a44a3b8e69b.png)
![image](https://user-images.githubusercontent.com/101108440/220680433-bb74b244-f2ec-40a9-bca1-f806bab57d26.png)

## 부트스트랩을 사용하기 위해선 .. 
- CDN 링크 적기
  - <.head>에 <link ~~> 추가 
    이때, 가져온 링크를 먼저 적어주어야 내가 수정한 css가 적용됨 => 오버라이트
- 모바일 버전 적용을 위해 js CDN도 필요함
  - <script></script>를 <body> 맨 마지막에 추가해주기


## media 쿼리 사용하기
```css
@media screen and (max-width:48rem) {
  .first-line{
    text-align: center;
  }
}
```
max-width가 48rem일때 (즉, 너비 0~48)
first-line 클래스의 텍스트를 중앙정렬한다.

### 추가
```
display: block;
```
display에 적용된 css를 없애겠다. (적용 취소)
