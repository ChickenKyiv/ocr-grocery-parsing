# OCR Grocery list parcing


Table of Contents
=================

 * [Synopsis](###Synopsis)
 * [Screenshot](#screenshot)
 * [Installation](#installation)
       * [OR using Pathogen:](#or-using-pathogen)
       * [OR using Vundle:](#or-using-vundle)
 * [License](#license)

* [Headers](#headers)  
[Emphasis](#emphasis)  
...snip...    
<a name="headers"/>
## Headers



#### Synopsis
At this project we're trying to create an algorithm, that will be able to proceed images from Pinterest into js/json arrays, that we can use in our project. We're interested in images, that contains grocery list templates. 





GS(GroceriStar - current project) GL(grocery list) At GS we have only one grocery list template for cloning. it's name Ultimate Grocery List but it have all items in one place. For a lot of cases - we don't need all this data. Usually people will need to delete a lot of items from personal lists.

So i think it'll be good feature to have another GL templates at GS.

Web is full with GL for different topics. Vegan, healthy, cheap, diabetic, etc.

#### Ravi
Hi Arthur... I was able to solve the bug and was able to read the initial grocery list you have used to make the Groceristar but it is failing for images with very small font as they are indistinguishable for it.. 
I am trying to improve  accuracy by different methods (opencv thresholds) etc.. 
will let you know if there is any improvement .. 
fyi ignore if you already know it.. 
there is a image scrapper python script which helps to scrap images for a given URL..

#### Ravi
Hi Arthur, Can you send me few links which are most important for you .. I will try to use other software to improve the accuracy of text recognition.. my initial idea was to scrape through all websites but it seems the images are quite different from one another...

#### Arthur
Check TESTS.md for different samples. i tried a different layouts, fonts

#### Ravi
it would do for clear image but can't for small font ones.. so I have asked your help to find which images are important for you such that I can fine tune the algo to our needs..

I thought of improving model by highlighting the text and then converting it but it couldn't complete ..
I have added  a sample image and sample output of the code for reference..


#### How to use it
Install tesseract
install below python packages
* pytesseract
* opencv 
* opencv contrib
* nltk
* autocorrect
* re

in pytesseract script at tesseract_cmd add your  tesseract ocr location


Code credits: @vpisarev

How to check is this algorythm working well - check TESTS.md
