# wikisource

main file: `indexPagesCountCat.py`  

I am one of the outreach person of Tamil wikisource.   
Many newbies are asking for books on the basis of a specific page number. For e.g. they need books which are having less than 50 pages. So, I am creating this code to classify and write categories according to the *maximum* page of the book.   
Just write index book names in `அட்டவணைகள்.txt` and run this program. This program will then add the category according to the highest page number of the book.


Here is an example on how this works:  

| Maximum Page#| Category |
|:------------:|:--------:|
| 24           | 1-50     |
| 51           | 51-100   |
| 99           | 51-100   |
| 545          | 500-600  |

To see all the categories possible through this program please check [this category link](https://ta.wikisource.org/s/9yyr)  

I have written a library in Tamil language to write code in Tamil wikisource language itself and not in English language, which makes it easier to understand the coder as well as future reader/maintainer of the code.  
The library is uploaded in this repo named, `பைவிக்கிமூலம்00.py`

Kindly feel free to [mail me](mailto:infofarmer2015@gmail.com).
