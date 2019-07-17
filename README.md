# IE9-1C
Адаптивное меню для IE9 с выборкой данных из 1С

@DmitriyBurmistrov
DmitriyBurmistrov Start

Запросы на выборку данных:

id - номер по пункту

name - название пункта меню (Окна ПВХ, Двери ПВХ и другие элементы 2 уровня)

isGroup - имеет значение (Да/нет) 

idParent - номер родителя (из пункта 1 - id )


Сейчас 

<ul>
  <li>Меню1</li>
  <li>Меню2</li>
  <li>Меню3
    <li>ДочМеню3</li>
    <li>ДочМеню3</li>
    <li>ДочМеню3</li>
  </li>     
</ul>

Нужно чтобы дочек заворачивал в <ul class="sub">

 <code>
  <ul>
  <li>Меню1</li>
  <li>Меню2</li>
  <li>Меню3
    <ul class="sub">
     <li>ДочМеню3</li>
     <li>ДочМеню3</li>
     <li>ДочМеню3</li>
    <ul>
  </li>    
</ul>
  </code>
