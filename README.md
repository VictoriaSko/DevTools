# Использование Chrome DevTools - анализ открытия сайта.

## 1) Network 
### 1.1) Профиль загрузки ресурсов при открытии страницы - [www.gd.ru.har](https://github.com/VictoriaSko/DevTools/blob/main/Network/www.gd.ru.har)

### 1.2) Неоптимальные места
** 1.2.1) Дублирование ресурсов**

** 1.2.2) Лишний размер ресурса**

** 1.2.3) Медленно загружающиеся ресурсы**

** 1.2.4) Ресурсы, блокирующие загрузку**

## 2) Performance
### 2.1) Профиль загрузки страницы - [Trace.json](https://github.com/VictoriaSko/DevTools/blob/main/Performance/Trace-20230613T232829.json)

### 2.2) Время в мс от начала навигации до событий:
**First Paint - 485.9 ms**
**First Contentful Paint - 485.9 ms**
**Largest Contentful Paint - 901.4 ms**
**DOMContentLoaded Event - 813 ms**
**Onload Event (Load) - 31159.4 ms**

### 2.3) DOM-элементе, на котором происходит LCP 
`<img loading="lazy" src="/images/branding/10/imageTop_1628667062.7856.jpg" data-url="/images/branding/10/imageTop_1628667062.7856.jpg" alt="-">`

### 2.4) Времени в миллисекундах, которое тратится на разные этапы обработки документа
**Loading - 24 ms**
**Scripting - 796 ms**
**Rendering - 256 ms**
**Painting - 24 ms**

![](https://github.com/VictoriaSko/DevTools/blob/main/Performance/Page%20Loading.png)

## 3) Coverage
### 3.1) Скриншот вкладки после загрузки страницы - [Coverage.png](https://github.com/VictoriaSko/DevTools/blob/main/Coverage/Coverage.png)

### 3.2) Объём неиспользованного CSS в ходе загрузки страницы в килобайтах
**Unused CSS - 572 kB**

### 3.2) Объём неиспользованного JS в ходе загрузки страницы в килобайтах
**Unused JS - 2700 kB**