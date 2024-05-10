# 마크다운 작성법
## 1. headers
> [#] 하나당 크기가 작아져영
   
   ># header1
   >## header2
   >### header3
   >#### header4
   >##### header5
   >###### header 6

문법 )   
   \# header1   
   \## header2   
   \### header3   
   \#### header4   
   \##### header5   
   \###### header6   

## 2. BlockQuote
[>] 이 문자를 사용   
ex)
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.     
   
문법)   
\> This is a first blockqute.   
\>	\> This is a second blockqute.   
\>	\>	\> This is a third blockqute.

## 2.3 목록
* ### 순서대로 목록
>1. 첫번째      
>2. 두번쨰    
>3. 세번째

* 무조건 내림차순으로만 작성됨.   
* #### 순서 무시 목록
\* 별   
\+ 플러스   
\- 마이너스   
>* 별
>+ 플러스   
>- 마이너스   
## 2.4 code
4개의 공백, 또는 하나의 TAB으로 들여쓰기 하지않으면 계속 써짐.

**Enter** 두번 입력시 행 건너뛰기 가능

## 2.4.1 codeblock
2가지 방식으로 이용가능
* \<pre>\<code> {code} \</code>\</pre>
<pre>
</code>   
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
</code>
</pre>

* \```  코드 블럭 코드 이용


```
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

## 2.5 수평선 \<hr/>
> \* &nbsp;&nbsp;    * &nbsp;&nbsp; *   
> \***   
> \*****   
> \- &nbsp; - &nbsp; -    
> \--------------------------


* * *   
***   
*****   
-  -  -    
--------------------------


## 2.6 link
* 참조링크 
> [link keyword][id]  
>
> //code    
> Link : &nbsp; [Google]\(googlelink)

Link : [google](https://google.com)

* 자동 연결
> 일반적인  URL을 사용하면 알아서 링크를 연결해줌

## 2.7 강조

>\*single asterisks*   
>\_single underscores_   
>\**double asterisks**   
>\_\_double underscores__   
>\~\~cancelline~~   
> \${\textsf{\color{green}Green}}$


${\textsf{\color{green}Green}}$    
*single asterisks*   
_single underscores_   
**double asterisks**   
__double underscores__   
~~cancelline~~   

## 2.8 이미지

>![Alt text]\(/path/to/img.jpg)   
>![Alt text]\(/path/to/img.jpg "Optional title")   


사이즈 조절 기능은 없음

\<img width="" height="">\</img>를 사용
>\<img src="/path/to/img.jpg" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck">\</img>\<br/>
>
>\<img src="/path/to/img.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="RubberDuck">\</img>


## 2.9 줄바꿈
3칸 이상 띄어쓰기 하면 줄이 바뀜

Enter 두 번 이상 사용시 줄 한 줄 뛰어넘음


\&nbsp; 사용시 스페이스바 가능


\<br> 사용시 줄 바꿈 가능
## 3.1 표 생성
>테이블 생성

헤더1|헤더2|헤더3|헤더4   
\---|---|---|---   
셀1|셀2|셀3|셀4   
셀5|셀6|셀7|셀8   
셀9|셀10|셀11|셀12   

테이블 정렬

헤더1|헤더2|헤더3   
\:---|:---:|---:   
Left|Center|Right   
1|2|3   
4|5|6   
7|8|9   

* 생성 결과

테이블 생성

헤더1|헤더2|헤더3|헤더4
---|---|---|---
셀1|셀2|셀3|셀4
셀5|셀6|셀7|셀8
셀9|셀10|셀11|셀12

테이블 정렬

헤더1|헤더2|헤더3
:---|:---:|---:
Left|Center|Right
1|2|3
4|5|6
7|8|9
