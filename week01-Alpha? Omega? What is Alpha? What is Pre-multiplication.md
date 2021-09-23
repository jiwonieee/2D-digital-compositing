[2D digital compositing] week01_Alpha? Omega? What is Alpha? What is Pre-multiplication
=====================================================================================


2D
-----------
2차원, x축과 y축으로 이루어진 것, 우리가 사용하고 있는 매체

Digital
------------------
digit- 수, 숫자 / al-
digital의 어원_손가락을 뜻하는 라틴어 낱말 digit에서 나온 것으로, 숫자를 세는 데 쓰인다.
(https://ko.wikipedia.org/wiki/%EB%94%94%EC%A7%80%ED%84%B8)

image = digits ?
----------------
우리는 이미지들을 보면서 어떤 사진, 형상을 보고 있다고 시각적으로 받아들이지만, 사실을 숫자로 이루어진 것들을 보고 있다.       
컴퓨터에서는 색상들을 모두 수로 변환해서 인식하고 그 숫자들이 디지털 매체에서는 색상으로 변환되어 나타나 우리 눈에 시각적으로 노출되는 것이다.

compositing
----------------------
compositing- 어떤 이미지나 영상에서 원하는 부분을 도출해서 다른 이미지나 영상에 합성하는 것을 의미한다.

color
--------------
<RGB>
RGB(Red, Green, Blue)라는 color space를 digital에서는 기본적으로 가지고 있다. 영상매체에서 주로 쓰이는 color space이다.          
  

<CMYK>
CMYK(Cyan, Magenta, Yellow, Key/Black)은 인쇄를 기반으로 하는 color space이다.
(https://99designs.com/blog/tips/correct-file-formats-rgb-and-cmyk/)
  

-어떻게 우리의 시각에 색상이 나타날까?        
  
일반적으로 알고 있듯이 물체에 반사되는 빛이 우리의 눈에 보이게 된다.
예를 들어 노란색이 우리 시각에 보인다고 하면, RGB에서 B는 흡수되고 R과 G가 반사되어 우리 눈에 노란색으로 보이게 되는 것이다.
(https://www.scratchapixel.com/lessons/digital-imaging/colors/introduction)
 
color, alpha, color space가 CG작업에서는 어떻게 사용되고 있는가?
-------------------------------------------------------
  

