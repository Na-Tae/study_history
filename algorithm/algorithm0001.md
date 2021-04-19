# <알고리즘 문제풀이>
```
입력된 수 만큼
*****
****
***
**
*
형태로 '*'를 출력하는 프로그램을 작성하시오.
위의 그림은 5를 입력했을 경우입니다. 입력한 수가 출력될 삼각형의 층(Level)
이라고 생각하시면 될 것 같습니다.

입력 - 100이하의 자연수
출력 - 입력의 맞는 층의 '*'로 이루어진 삼각형 
```
```
풀이)
on("line", function(line) {
    for (var i = line; i > 0; i--) {
        var printing = '' 
        for(var j = 0; j < i; j++) {
        printing = printing + '*'
        }
    console.log(printing)
    }
})
```