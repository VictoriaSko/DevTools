# Использование Chrome DevTools - анализ открытия сайта.

### 1) Network 
**1.1) Профиль загрузки ресурсов при открытии страницы - [www.gd.ru.har](https://github.com/VictoriaSko/DevTools/blob/main/Network/www.gd.ru.har)**

**1.2) Неоптимальные места** <br />
1.2.1) Дублирование ресурсов

1.2.2) Лишний размер ресурса

1.2.3) Медленно загружающиеся ресурсы

1.2.4) Ресурсы, блокирующие загрузку


### 2) Performance
**2.1) Профиль загрузки страницы - [Trace.json](https://github.com/VictoriaSko/DevTools/blob/main/Performance/Trace.json)**

**2.2) Время в мс от начала навигации до событий:**
- **First Paint - 566.6 ms** <br />
<img src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/First%20Paint.png" data-canonical-src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/First%20Paint.png" width="200"/>

- **First Contentful Paint - 485.9 ms** <br />
<img src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/First%20Contentful%20Paint.png" data-canonical-src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/First%20Contentful%20Paint.png" width="200"/>

- **Largest Contentful Paint - 901.4 ms** <br />
<img src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/LCP.png" data-canonical-src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/LCP.png" width="200"/>

- **DOMContentLoaded Event - 813 ms** <br />
<img src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/DOMContentLoaded%20Event.png" data-canonical-src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/DOMContentLoaded%20Event.png" width="200"/>

- **Onload Event (Load) - 31159.4 ms** <br />
<img src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/Onload%20Event.png" data-canonical-src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/Onload%20Event.png" width="200"/>

**2.3) DOM-элементе, на котором происходит LCP** <br />
`<img loading="lazy" src="/images/branding/10/imageTop_1628667062.7856.jpg" data-url="/images/branding/10/imageTop_1628667062.7856.jpg" alt="-">`

<img src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/LCP%20DOM%20Component.png" data-canonical-src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/LCP%20DOM%20Component.png" width="500"/>

**2.4) Времени в миллисекундах, которое тратится на разные этапы обработки документа**
- **Loading - 21 ms** <br />
- **Scripting - 768 ms** <br />
- **Rendering - 224 ms** <br />
- **Painting - 19 ms**

<img src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/Page%20Loading.png" data-canonical-src="https://github.com/VictoriaSko/DevTools/blob/main/Performance/Page%20Loading.png" width="200"/>


### 3) Coverage
**3.1) Скриншот вкладки после загрузки страницы - [Coverage.png](https://github.com/VictoriaSko/DevTools/blob/main/Coverage/Coverage.png)**

**3.2) Объём неиспользованного CSS в ходе загрузки страницы в килобайтах** <br />
- **Unused CSS - 572 kB**
<img src="https://github.com/VictoriaSko/DevTools/blob/main/Coverage/Unused%20CSS.png" data-canonical-src="https://github.com/VictoriaSko/DevTools/blob/main/Coverage/Unused%20CSS.png" width="500"/>

**3.2) Объём неиспользованного JS в ходе загрузки страницы в килобайтах** <br />
- **Unused JS - 2700 kB**
<img src="https://github.com/VictoriaSko/DevTools/blob/main/Coverage/Unused%20JS.png" data-canonical-src="https://github.com/VictoriaSko/DevTools/blob/main/Coverage/Unused%20JS.png" width="500"/>
