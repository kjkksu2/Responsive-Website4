# Responsive-Website4

 1. css transition 효과가 media query에 의해 나타나는 것을 방지하려면 transition을 javascript로 구현하면 된다.

 2. removeEventListener를 사용하려면 임시함수를 사용하면 안된다.

&emsp; ex) moreItem.addEventListener("click", controlMoreItem); -- OK<br/>
&emsp;&emsp;   moreItem.addEventListener("click", () => { console.log("hi) }); -- NO

 3. removeAttribute

![image](https://user-images.githubusercontent.com/80094949/137414886-b8e6bfef-264a-437c-94a0-fccea83c2c71.png)
