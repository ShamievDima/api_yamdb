# ?????? "YaMDb"

>??????? ?????? ? ?????? ????? __Python-developer__ ?? ????????? __??????.?????????__

?????? __YaMDb__ ???????? ?????? (Review) ????????????? ? ????????????? (Titles).

### ? ???????:
???????????? ? ??????? ?? ????????.
?????? ?????????? ????? ??? ????????? ??????.

???????????? ????????? ?? ????????? (Category):   
???????, ????????, ????????.  

_?????? ?????????  ????? ???? ???????? ???????????????._

???????????? ????? ???? ???????? ???? (Genre) ?? ?????? ?????????????????:  
- ????????,
- ?????
- ?????????.

_????? ????? ????? ????????? ?????? ?????????????._

???????????? ????? ????????? ? ????????????? ????????? ?????? (Review) ?  
??????? ???????????? ?????? ? ????????? ?? ?????? ?? ?????? (????? ?????).

?? ???? ???????????? ???????????? ????? ???????? ?????? ???? ?????.

??? ?????????????? ???????????? JWT-??????.  
? ????????????????????? ????????????? ?????? ? API ?????? ?? ??????.  
??????????????????? ????????????? ????????? ????????, ????????? ? ???????? ?????? ??????;  
? ????????? ??????? ?????? ??????????????? ?????? ??? ??????.

### ??????????:
- django 2.2.16

??????: User, Category, Genre, Title, Review, Comment

## ??? ????????? ??????:

??????????? ??????????? ? ??????? ? ???? ? ????????? ??????:
```
git clone ?????? ?? ???????????
cd api_final_yatube
```

C?????? ? ???????????? ??????????? ?????????:
```
python3 -m venv venv
source venv/Scripts/activate
```

?????????? ??????????? ?? ????? requirements.txt:
```
pip install -r requirements.txt
```

??????? ? ??????? ? manage.py
```
cd yatube_api
```

????????? ????????:
```
python3 manage.py migrate
```

????????? ??????:
```
python3 manage.py runserver
```


### ???????. ????????? ??????? ???????? ? API.

?????? ?? ????????? ?????? ?????????:

```
http://api/v1/categories/
```

?????? ?? ????????? ?????? ??????
```
http://api/v1/genres/
```

### ???????????? ???????

???? ?????

??????? ??????

????? ????????
