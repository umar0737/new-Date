# Дар JavaScript мо конструтори new Date() дорем.
## ВАЛЕ new date() чист?
### Дар JavaScript, объектҳои сана бо new Date() сохта мешаванд. new Date() объекти санаро бо санаи дар компютерамон буда месозад ва онро бар мегардонад.
## new date аз 1 январи соли 1970 сар мешавад.
### вақте ки мо ин тавр new date - ро месозем (new Date())  - ба мо ба мо санаро бар мегардонад. Ва агар мо дар дарунаш параметр рои кнем у мисли милисекунд қабул мешавад, ва чиқадар милисекунд  рои кнем он қадар миллисекунд ба санаи 1 январи соли 1970 ҷамъ карда мешавад. Ва агар мо параметрҳоро бо string нависем 
```JS
let date = new Date('2024-11-14')
console.log(date);
```
### Онро бо чихели ҳаст қабул мекунад
![alt](https://miro.medium.com/v2/resize:fit:988/1*viUjG5XikbmLP3FSBcRLOA.png)

## Ва инчунин new date() барои худ методҳо дорад
![alt](https://learningpenguin.net/wp-content/uploads/2017/07/JavaScript_Add_Days_To_Date.jpg)

## 1.Методи getFullYear().
### Методи getFullYear() ба мо соле дар компютери мо бударо  ба мо бармегардонад.
![alt](https://pbs.twimg.com/media/GGg2FVKWQAAOO96.jpg)
## 2.Методи geMonth().
### getMonth() моҳоро ба мо бармегардонад. Ва он аз руи индекс меравад (яъне 0 то 11). январ =0, феврал = 1 ва дигарон.
![alt](https://www.w3resource.com/w3r_images/js-date-object-getmonth.gif)
## 2.Методи geDate().
### Методи getDate() рӯзи моҳро (1 то 31) санаро бармегардонад.
![alt](https://www.w3resource.com/w3r_images/js-date-object-getdate.gif)

## 3.Методи getDay().
### Методи getDay() барои баргардонидани рӯзи ҳафта  аз объекти додашудаи Date истифода мешавад.Ва ин хам бо индекс бармегардонад(0 то 6). Синтаксис: DateObj.getDay() 

![alt](https://linuxhint.com/wp-content/uploads/2022/12/Returns-Wrong-Day-in-JavaScript-1.png)
## 4.Методи getHours().
###  getHours() соати (0 то 23) санаро бармегардонад.
![alt](https://www.w3resource.com/w3r_images/js-date-object-getutchours.gif)

## 5.Методи getMinutes().
### getMinutes() дақиқаҳои (0 то 59) санаро бармегардонад.
![alt](https://www.w3resource.com/w3r_images/js-date-object-getminutes.gif)

## 6.Методи getSeconds().
### JavaScript Date getSeconds()getSeconds() сонияҳои (0 то 59) санаро бармегардонад.
![alt](https://www.w3resource.com/w3r_images/js-date-object-getseconds.gif)

## 7.Методи setDate().
### Ин мисли настройки аст, аммо мо танҳо ба ҷои get set менависем ва баъд методҳое, ки ҳамаашон ҳастанд. Қиматҳои додаҳо метавонанд ба монанди солҳо, моҳҳо, рӯзҳо, соатҳо, дақиқаҳо, сонияҳо ва миллисонияҳо барои Объекти санаро мо метавонем дигар кунем. 
![alt](https://flaviocopes.com/images/how-to-add-days-date-javascript/Screen_Shot_2022-04-09_at_14.16.14.png)

## 8. Методи setMonth()
### Методи setMonth() барои иваз кардани мох мебошад. 
![alt](https://www.w3resource.com/w3r_images/js-date-object-setmonth.gif)
## 9. Методи setFullYears()
### Методи setFullYears() барои иваз кардани сол мебошад. Инчуни метавонад мох ва рузро иваз кунад.
![alt](https://www.w3resource.com/w3r_images/js-date-object-setfullyear.gif)

## setHours() - барои бо соат кор кардан ва иваз  кардани он лозим аст.
![alt](./image/code.png)
## setMilliseconds()  - барои иваз кардани милисикунд мебошад.
![alt](./image/millisecond.png)
## setMinutes() - барои иваз кардани минут мебошад
![alt](./image/minutes.png)
## setSecond() - барои аваз кардани сония мебошад.
![alt](./image/secongs.png)


# NEW MAP()

## new Map() - ин як колексия элементҳое мебошад ки аз ключ ва значенияҳо иборат аст.
## new Map() - ба мо барои он лозим аст ки мо массивҳоро ба мисли объект кунем.
![alt](./image/map.png) 
## new Map() - ба худ методҳо дорад.
## методи set() - барои илова кардани элементи бо ключ ва значения лозим аст.
![alt](./image/set.png)
## get() - барои гирифтани ягон элемент лозим аст.
![alt](./image/get.png)
## delete - барои удалит кардани ягон элемент аз map лозим аст

![alt](./image/delete.png)
## has - ин барои санҷидан ҳаст ки ягон элемент дар объект ҳаст ё не ва дар ҷавоб true false бар мегардонад.
![alt](./image/рфҷ.png)
