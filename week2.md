광운대학교 전기공학과 2018732062 박주환
---
# 구글코랩(Google Colab)
* 구글코랩이란?  
구글에서 제공하는 클라우드 기반의 Jupyter notebook 개발 환경이다. 머신러닝기법을 프로그래밍 할 수 있고 그 결과 까지 확인이 가능하다. **GPU**의 무료 엑세스를 제공하기 때문에 웬만한 개인PC보다 성능이 좋고 빠르다.
* 사용방법  
  * 구글 계정 마운트 하는 법  
  __구글 드라이브__ 에 마운트 해놓으면 자신이 만든 파일을 관리하기 쉬워지므로 자신의 구글 계정을 이용하여 마운트하자. 좌측에 파일 아이콘을 클릭한 후 드라이브 마운트 아이콘을 클릭해주면 된다.

* 타이틀  
'#'의 갯수에 따라 제목의 크기를 조절할 수 있다. 적을수록 큰 글씨.
#굵게6  
##굵게5  
###굵게4  
####굵게3  
#####굵게2  
######굵게1

* 강조
원하는 글씨 양 옆에 아래의 특수문자를 활용해 글씨를 강조할 수 있다.  
__진하게__  
<u>밑줄</u>  
~취소~  
*기울임*  
_기울임_  
`인라인코드`  

* 문장 줄바꿈  
markdown문법에서는 띄어쓰기2개를 포함해야 줄바꿈이 가능하다.
문장
줄바꿈
안함  
문장  
줄바꿈  
함  

* 블럭(인용) 들여쓰기  
'>'를 이용해 들여쓰기를 사용할 수 있다.  
>들여쓰기 1단  
>>들여쓰기 2단  

* Code Block  
"```(esc아래 키)"사이에 코드를 쓰면 코드형식으로 표현이 가능하다.  
```
import something
a=10
print(a)
if a>10:
print(a)
```

* 수식  
(Latex 문법 참조 [링크1](https://ko.wikipedia.org/wiki/%EC%9C%84%ED%82%A4%EB%B0%B1%EA%B3%BC:TeX_%EB%AC%B8%EB%B2%95), [링크2](https://velog.io/@d2h10s/LaTex-Markdown-%EC%88%98%EC%8B%9D-%EC%9E%91%EC%84%B1%EB%B2%95), [링크3](https://itpro.tistory.com/115), [링크4](https://huni0318.github.io/blog/blog-etc/2020-12-21-markdown-tutorial2/))  
$\begin{matrix}1&2\\3&4\\ \end{matrix}$  
$\begin{pmatrix}1&2\\3&4\\ \end{pmatrix}$  
$\begin{bmatrix}1&2\\3&4\\ \end{bmatrix}$  
$\begin{Bmatrix}1&2\\3&4\\ \end{Bmatrix}$  
$\begin{vmatrix}1&2\\3&4\\ \end{vmatrix}$  
$\begin{Vmatrix}1&2\\3&4\\ \end{Vmatrix}$  

문장내 $\frac{1+s}{s(s+2)}$ 삽입  
$$\frac{1+s}{s(s+2)}$$  

---
$$
\begin{aligned}
f(x)&=ax^2+bx+c\\
g(x)&=Ax^4
\end{aligned}
$$
---

* 그림  
url 문법에서 앞에 느낌표를 붙힌다는 차이가 있다. url에 링크된 사진을 넣는다.  
#**사진**
![광운대](https://d1qzykz9iz00c7.cloudfront.net/static/logo_new/logo_c050.png)

아래'[]'에 x의 유무에 따라 체크된 박스또는 체크없는 박스를 만들 수 있다.  
#**체크박스**
* [ ] 비어있는 체크박스  
* [x] 체크된 체크박스  

* 하이퍼링크  
'[]'안에 대체할 텍스트를 넣고'()'안에 url을 지정해 하이퍼링크를 만들수 있다.'<>'안에 url을 직접넣어 바로 하이퍼링크를 할 수도 있다.  
#**하이퍼링크**
[바로가기](https://klas.kw.ac.kr/std/lis/evltn/OnlineCntntsStdPage.do)
<https://klas.kw.ac.kr/std/lis/evltn/OnlineCntntsStdPage.do>

* 수평선  
'---'2개를 입력하여 수평선을 나타내어 문서를 나눌 수 있다.  
#**수평선**
***
___

* 표  
표의 목록이름과 정렬기준을 지정할 수 있다.  
#**표**
|1열|2열|3열|
|:---|---:|:---:|
|바디1|바디2|바디3|
|바디4|바디5|바디6|

* 목록  
'*, +, -'를 이용해 목록표시를 만들 수 있다. (tab)키를 함께 활용하면 다른 목록표시를 사용가능하다.   
#**목록**
* 사과
* 오렌지
  + 딸기
  + 자두
- 포도
- 바나나
1. 참외
2. 수박

