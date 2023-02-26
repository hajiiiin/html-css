## 메뉴 강조 효과 주기 js 이용
![image](https://user-images.githubusercontent.com/101108440/221406964-e549e017-6206-40e3-a3a3-518c4b4cbc8d.png)
세로, 가로 버전 2개 만들

```js
horizontalMenus.forEach((menu) =>
  menu.addEventListener('click', (e) => horizontalIndicator(e.currentTarget))
);
```
forEach문을 이용하여 클릭했을 때 이벤트 발생 함수 
