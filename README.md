# info1
## h2에 대응
### h3에 해당
#### h4에 해당
##### h5에 해당
###### h6에 해당

**강조합니다.**
*이탤릭*
***이탤릭+강조입니다***

~~지우기입니다.양쪽에 물결이 2개씩 있고, 
띄어쓰기하면 안됩니다.~~

## Blockquotes
>인용문입니다. 들여쓰기처럼 출력됩니다.
>> 내부인용문입니다. 
>>> 한 번 더 들여쓴 인용문입니다.
## unordered list 방식
* 이것은 unordered list입니다. 별표 다음은 띄어써야 합니다.
 * 안으로 들어간 ul list입니다.
 * 안으로 들어간 ul list입니다.
  * 다시 안으로 들어가 ul list입니다. 내부로 들여쓴 list는 별표를 한칸 들여쓰면 됩니다.
    * 정말로 이해가 되시나요
    
나는
집에<br>
가고 싶다. Markdown

나는 두칸 공백  
집에 두칸 공백  
가고 싶다.

## 코드 블록을 넣어봅니다.
``` python
  #back tick(왼쪽의 `)을 앞 뒤로 3개씩 사용합니다.
  #처음에 사용할 코드 블록의 언어를 써줍니다.
  function add(a, b) :
    return a+b
  add(3,4)
  z = add(4,5) +5
```
``` javascript
  //back tick(왼쪽의 `)을 앞 뒤로 3개씩 사용합니다.
  //처음에 사용할 코드 블록의 언어를 써줍니다.
  var a=1, b=2;
  function add(a, b) :
    return a+b
    }
  console.log(add(3,4);
```
### a 태그의 역할을 알아보기[link]
[DAUM 사이트](http://www.daum.net)를 접속해 보세요.  

## image 가져오기(이미지 주소 복사, 작업 폴더에서 불러올 수 있음)
![아름다운 그림](https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885_960_720.jpg)
이미지 크기를 지정하고 싶으면 그냥 html의 img 태그를 사용하자(아래와 같은 방식)  
&lt;img src="/images/img1.png" width="300" height="300"&gt; <-- 실제로는 html syntax적용
