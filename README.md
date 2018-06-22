# markdown


alright, here we go:

**bold1**

__bold2__

*italic1*

_italic2_

**_bolditalic1_**

_**bolditalic2**_

*__bolditalic3__*

__*bolditalic4*__

~~strikethrough~~


**HEADINGS**

   type 1:'#'

# Heading1
 ## heading2
  ### heading3
  #### heading4
##### heading 5
###### heading6
####### that's as far as you can go!!

  type 2: '-/='
heading1
===

heading2
---

that's as far as you can go via this type!!

 # 1. **<https://www.youtube.com>**

 (_**p.s**
the <> should be inside the doble underscores for bold!!!!_)

## 2 [youtube](https://www.youtube.com "text can be passed only in this way of linking.")

### 3 [youtube]         [y]

[y]: https://www.youtube.com

# **images**

## 1
![alternate text](http://unsplash.it/500/500?random "text can be passed only in this type")

## 2

![][1]
[1]: http://unsplash.it/500/500?random
[2]: http://unsplash.it/50/50?random

## 3

[![alt.txt.](http://unsplash.it/50/50?random "click here to get  bigger pic (this is nested pic, say a pic serving as a link)")][1]

## 4

[<img src= http://unsplash.it/500/500?random>][1]

## 5 Using html, css
<img src="http://unsplash.it/500/500?random" width="500" height="490">
<style>
img {
  width:500px
  }</style>

  # **lists**

## unordered
* item1
  + sub1.1
  + sub1.2
    * Sub1.2.1

      a para under sub1.2.1
      ![alternate text](http://unsplash.it/500/500?random "an img under sub1.2.1")





* item
* item




## ordered
1. item1
1. item2
1. item3



word1 <br> word2

word1 <br>
word2

word word word
------------------

word word word1

-----------------

word1 word2

===


# block quotes
> text
>
>
>text
>text



>text
text

--------------
# code block
```html
  <img src="http://unsplash.it/500/500?random" width="500" height="490">
  ```
  ```css
   <style>
  img {
    width:500px
    }</style> ```

  ```
    var x = 100;
    - var y = 200;
    + var y = 300; ```

# Tables

|serial number|coloumn1|coloumn2|
|:-------------:|:-----------:|:---------------:|
|1|text|text|
|2|[![alt.txt.](http://unsplash.it/50/50?random "click here to get  bigger pic (this is nested pic, say a pic serving as a link)")][1]|[![alt.txt.](http://unsplash.it/50/50?random "click here to get  bigger pic (this is nested pic, say a pic serving as a link)")][1]|
|3|![][2]|![][2]|

# checkboxes
+ [x] text
+ [ ] text
+ [x] text
