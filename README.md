﻿# **Python 太乙神數 Kintaiyi 堅太乙 堅太乙時計**
[![Python](https://img.shields.io/pypi/pyversions/kintaiyi)](https://pypi.org/project/kintaiyi/)
[![PIP](https://img.shields.io/pypi/v/kintaiyi)](https://pypi.org/project/kintaiyi/)
[![Downloads](https://img.shields.io/pypi/dm/kintaiyi)](https://pypi.org/project/kintaiyi/)
[![TG](https://img.shields.io/badge/chat-on%20telegram-blue)](https://t.me/gnatnek)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg?logo=paypal&style=flat-square)](https://www.paypal.me/kinyeah)&nbsp;

![alt text](https://github.com/kentang2017/kintaiyi/blob/master/pic/64459296_2342412609170469_2685042927293431808_n.jpg "太乙")
 ## 1. 導讀 Introduction
太乙神數是古代漢族占卜術的一種，與遁甲，六壬合稱三式，是推算天時以及歷史變化規律的術數學。周武王時以術數"卜世三十，卜年八百"推之，至邵雍形成歷史哲學而大備。據太乙神數推算，上古時有一年冬至日半夜，恰好日月合璧、五星連珠，定為甲子年、甲子月、甲子日、甲子時，稱作太極上元，上元甲子以來的年數，叫太乙積年。由太乙積年再求出太乙流年和太歲值卦，以斷本年各月的氣運凶吉，預測一些重大政治事件和天災人禍。採用五元六紀，三百六十年為一大周期，七十二年為一小周期，太乙每宮居三年，不入中宮，二十四年轉一周，七十二年遊三期。

太乙以一為太極生二目(主、客目)，二目生主客大小客與計神共八將。太乙乃天地之神，其星在太乙之前，統十六神而知風雨、水旱、兵革之事。昔黃帝與蚩尤大戰，適逢大霧，以霧書昏風後相，造指南車克之，是以取太乙之法，傳至今三千餘年，例目以為術數。外閱龍圖，內演龜文，凡天地之所以設君臣父子，之所以立陰陽，太乙了然演數則理昭著，太乙周行流運六十四卦，貴神入門十精之星，使經緯錯縮表理，集為一書。延續至今三千餘年不衰，為當今社會預測、決斷，提供了寶貴依據。

相傳太乙式產生于黃帝戰蚩尤時。其法大扺本于《易緯.乾鑿度》太乙行九宮法。採用五元六紀，三百六十年為一大周期，七十二年為一小周期，太乙每宮居三年，不入中宮，二十四年轉一周，七十二年遊三期。太乙以一為太極生二目(主、客目)，二目生主客大小客與計神共八將。(與易經太極分二儀，二儀生四象，四象生八卦相仿)。以太乙八將所乘十六神之方位關系定出格局。可佔內外祝福。又臨四時之分野，可佔水旱疾疫。再推三基五福大小遊二限，可預測古今治亂。又可推出年卦、月卦等。

Taiyishenshu, one of the Ancient Chinese Divinations, along with Qimendunjia and Dailiuren known as "three styles".


## 2. 安裝套件 Installation
```python
	pip install kintaiyi
	pip install sxtwl == 1.0, numpy
```
## 3. 起課方式 Quickstart
```python
	from kintaiyi import kintaiyi
	kintaiyi.Taiyi(2021,11,14,20).pan()
```
