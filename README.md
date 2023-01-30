# Проект 1. Анализ вакансий на hh.ru

## Оглаление
[1.  Описание проекта](https://github.com/ZhanarBaken/prediction_hotel_rating/tree/master/Project_1#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/ZhanarBaken/prediction_hotel_rating/tree/master/Project_1#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/ZhanarBaken/prediction_hotel_rating/tree/master/Project_1#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/ZhanarBaken/prediction_hotel_rating/tree/master/Project_1#Этапы-работы-над-проектом)  
[5. Выводы](https://github.com/ZhanarBaken/prediction_hotel_rating/tree/master/Project_1#Выводы)   


### Описание проекта 
# <p style="border:3px solid DodgerBlue;text-align:center;font-size:100%;">0. Introduction</p>
<div class="alert alert-info" role="alert">
    
<center> <img src="https://upload.wikimedia.org/wikipedia/commons/e/e3/Booking.com_logo2.png" style="width:368px;height:81px;"> 
    
  WHAT CASE DO WE DECIDE?   
   
Let’s say that we work as a data scientist at Booking. One of the problems of the company is the dishonest hotels that twist their ratings. One way to detect such hotels is to build a model that predicts the rating of the hotel. If the predictions of the model differ greatly from the actual result, then perhaps the hotel is being dishonest and worth checking out.
    
Let's look at the data that we have to work with.
    
    
<table >
   <tr>
    <th>Column</th>
    <th>Description</th>
  </tr>
  
   <tr>
    <td>hotel_address</td>
    <td>street, post code, city, country </td>
  </tr>
    
   <tr>
    <td>additional_number_of_scoring</td>
    <td>the number of hotel scores without review </td>
  </tr> 
    
  <tr>
    <td>review_date</td>
    <td>the day of review </td>
  </tr>

  <tr>
    <td>average_score</td>
    <td>the average rating of the hotel </td>
  </tr>
    
   <tr>
    <td>hotel_name</td>
    <td>the full name of hotel </td>
  </tr>
    
   <tr>
    <td>reviewer_nationality</td>
    <td>country from which the reviewer came </td>
  </tr>
    
   <tr>
    <td>negative_review </td>
    <td>text of negative review </td>
  </tr> 
   
   <tr>
    <td>review_total_negative_word_counts </td>
    <td>the total number words of negative review </td>
  </tr>  
    
   <tr>
    <td>total_number_of_reviews </td>
    <td>the total number of reviews that the hotel has </td>
  </tr>  
    
   <tr>
    <td>positive_review</td>
    <td>text of positive review </td>
  </tr> 

   </tr> 
    
   <tr>
    <td>review_total_positive_word_counts</td>
    <td>the total number words of positive review </td>
  </tr> 
    
  <tr>
    <td>total_number_of_reviews_reviewer_has_given</td>
    <td>the total number of reviews reviewer has given </td>
  </tr> 
    
   <tr>
    <td>reviewer_score</td>
    <td>the number of reviewer score </td>
  </tr> 
    
   <tr>
    <td>tags</td>
    <td>tags that describe purpose of trip,type of room, count of nights of reviewer </td>
  </tr> 
    
   <tr>
    <td>days_since_review</td>
    <td>a difference in the number of days between review date and scrape date</td>
  </tr> 
    
   <tr>
    <td>lat</td>
    <td>latitude coordinate of hotel location </td>
  </tr> 
    
   <tr>
    <td>lng</td>
    <td>longitude coordinate of hotel location </td>
  </tr> 
      
</table>
    
</div>
:arrow_up:[к оглавлению](https://github.com/ZhanarBaken/prediction_hotel_rating/tree/master/#Описание-проекта)  

### Какой кейс решаем?
Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Но, как вы знаете, прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить.

:arrow_up:[к оглавлению](https://github.com/ZhanarBaken/prediction_hotel_rating/tree/master/Project_1#Описание-проекта)


### Краткая информация о данных

Данные с резюме соискателей от hh.ru: https://drive.google.com/file/d/1P0xvmHWw0F51jYnsLKca3KoSOpgoVglu/view?usp=sharing
Данные о курсах различных валют от MDF.RU: https://drive.google.com/file/d/1GRf-yKly5vbfJTjLSc4wyfXkydmmfCO2/view?usp=sharing

:arrow_up:[к оглавлению](https://github.com/ZhanarBaken/data_science_zhanar/tree/main/Project_1#Оглаление)


### Этапы работы над проектом  

1. Базовый анализ структуры данных

2. Преобразование данных

3. Разведывательный анализ

4. Очистка данных

:arrow_up:[к оглавлению](https://github.com/ZhanarBaken/data_science_zhanar/tree/main/Project_1#Оглаление)


### Выводы
Учитывая информацию предоставленной  соискателями в резюме, можно спрогнозировать подходящую заработную плату, даже если она не указана. 

:arrow_up:[к оглавлению](https://github.com/ZhanarBaken/data_science_zhanar/tree/main/Project_1#Оглаление)