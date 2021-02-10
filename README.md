# To-Do-List 만들기(3) 
## javascript
---

1️⃣ input.classList.add("error");

리스트를 입력하는 `<input>` 태그에 value값이 없으면 outline 주기 >> `border:red` 사용
❗ css내 `outline:none;` 설정을 하지 말아야 한다

2️⃣ 엔터 치면 리스트 생성

console.log(e.key) ➡ "enter" / console.log(e.keyCode) ➡ "13"  >> `if문에 활용`
```js
input.addEventListener("keypress", (e) => {
    console.log(e.key);
    if (e.key === "Enter") {
        btn.click();
    }
    return;
});
```
