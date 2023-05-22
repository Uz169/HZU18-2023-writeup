# Netflix
***
Easy 
,1000 points
,27 solves

## Description
Help me to recover my "netflix" database. 
/netflix.zip

## Solve
Энэхүү даалгаварт дагалдаж ирсэн netflix.zip file -ыг нээж үзэхэд дотроос нь netflix.tar гэсэн file гарч ирнэ, tar file -ыг нээхэд password шаардах ба даалгаврын description хэсэгт "netflix" гэж тодотгосон байгааг анзаарах юм бол password нь гэдгийн ойлгоно,
password -ыг хийгээд тайлсаны дараа дотроос нь 

<p align="center">
  <img src="https://github.com/Uz169/HZU18-2023-writeup/blob/main/Misc/Netflix/img/1.JPG">
</p>

гэсэн олон file-ууд гарж ирнэ, энэ дундаас restore.sql file -г .txt болгоод дотроос нь HZU гэж find хийхэд

<p align="center">
  <img src="https://github.com/Uz169/HZU18-2023-writeup/blob/main/Misc/Netflix/img/2.JPG">
</p>
  
гарч ирнэ 

``` COPY public.hzu (flg) FROM '$$PATH$$/3607.dat'; ```
гэсэн хэсгээс санаачлан 3607.dat гэсэн file -г текстээр нээж үзэхэд
 
<p align="center">
  <img src="https://github.com/Uz169/HZU18-2023-writeup/blob/main/Misc/Netflix/img/3.JPG">
</p>

flag нь олдоно.  ``` HZU18{Wh@t_Is_YOUR_FavOrite_Ser1es_on_NETFLIX_???} ```

