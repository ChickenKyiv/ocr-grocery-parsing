

first article: https://medium.com/groceristar/how-i-think-we-can-add-machine-learning-into-groceristar-chickenkyiv-projects-b3af40bb266

repo: https://github.com/GroceriStar/ocr-grocery-parsing

one of the samples
https://github.com/GroceriStar/creative/blob/master/OCR/CareComHealthyGroceryList.png

all samples that i prepared(i have at some place i have more): https://github.com/GroceriStar/creative/tree/master/OCR

---

we also tried quickly to use google vision, but right now i think it's better to finish this project with your
current tesseract library logic.
google vision is not free, but they have some startup based plans, maybe later we'll apply into it.


this data that Omkar(Our Lead) shared with me
https://docs.google.com/document/d/1yp9TxbeddRxn1Gj1RoJQcChtUgUy00nio_LBMm4IjMM/edit

https://docs.google.com/document/d/131_U1EDOdaQ60AiMNmQaTumHN38FMyeeXKEbFCtbYBI/edit

https://docs.google.com/document/d/1yJX8t5ILsneM2hBxWDT14hLkeQ3IwpeDeOE9jQGtKdY/edit

---


This is an end result that should be: https://github.com/GroceriStar/ocr-grocery-parsing/issues/2

- more details about how our plugin structured
- repository: https://github.com/GroceriStar/groceristar-fetch
- documentation: https://groceristar.github.io/groceristar-fetch/

- different grocery lists: https://github.com/GroceriStar/groceristar-fetch/tree/master/data/Grocery
- more lists: https://github.com/GroceriStar/groceristar-fetch/tree/master/grocery-lists

I'll think that we complete this assignment, when i'll be able to easily grab json file with grocery lists - move it to our fetch plugin and import our data from that file into our server.



New, not processed images stored here:
https://github.com/GroceriStar/creative/blob/master/OCR/Readme.md

But in order to get them into our system we should have
website link, so we can add credits, image, title that we can use in our system


So, How the end result will looks.

End result is: we have 100 imported grocery lists into our database and they displayed in our project.
Before that we should have our 30 images, that was converted at output.txt be updated, in order to follow the structure that we have.

This is how our database looks like https://raw.githubusercontent.com/ChickenKyiv/creative/master/database-schemes/Groceristar%20%20%20SqlDBM.png


groceristar right now have 8-15 templates related to shopping.
i want to add other templates, that more specific and oriented to vegan food, or diabetics food, etc
and when i research different templates i find at least 200 grocery lists
i save that urls
but i think it's a pretty dump to open each link and just copy data from it and save to grocerystar
what do you think it;s possible to accomplish with ML
and this is a main idea for now, but it can be changed for sure - just teach me what ML is capable for my project
