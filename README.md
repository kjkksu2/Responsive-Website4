# Responsive-Website4

 1. css transition 효과가 media query에 의해 나타나는 것을 방지하려면 transition을 javascript로 구현하면 된다.

 2. removeEventListener를 사용하려면 임시함수를 사용하면 안된다.

&emsp; ex) moreItem.addEventListener("click", controlMoreItem); -- OK<br/>
&emsp;&emsp;   moreItem.addEventListener("click", () => { console.log("hi) }); -- NO

 3. removeAttribute
