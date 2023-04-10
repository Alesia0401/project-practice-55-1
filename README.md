## Наш проект:

<a alt="Link" href="https://alesia0401.github.io/project-practice-55-1/">Organic Fruit & Vegetables</a>

## Макет figma:

<a alt="Link" href="https://www.figma.com/file/YasVj3iKyhlHfL5pob9Pbo/organic-food-%2B-(Copy)?t=ziVN0v2mBLHddWVp-0">Organic Fruit & Vegetables</a>

## Использованные технологии:

<table align="left">
  <tr>
    <td align="center" width="96">
      <a href="#sssheina-tech">
        <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="48" height="48"/>
      </a>
      <br>HTML5
    </td>
    <td align="center" width="96">
      <a href="#sssheina-tech">
       <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="48" height="48"/>
      </a>
      <br>CSS3
    </td>
    <td align="center" width="96">
      <a href="#sssheina-tech">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" width="48" height="48"/>
      </a>
      <br>SASS
    </td>
    <td align="center"  width="96">
      <a href="#sssheina-tech">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg"  width="48" height="48"/>
      </a>
      <br>VSC
    </td>
    <td align="center" width="96">
      <a href="#sssheina-tech" >
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"  width="48" height="48"/>
      </a>
      <br>GIT
    </td>
    <td align="center" width="96"> 
      <a href="#sssheina-tech" >
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="48" height="48"/>
      </a>
      <br>GITHUB
    </td> 
    <td align="center"  width="96">
      <a href="#sssheina-tech">
        <img src="https://github.com/devicons/devicon/blob/master/icons/figma/figma-original.svg" title="Bootstrap" **alt="Figma"  width="48" height="48"/>
      </a>
      <br>FIGMA
    </td>
  </tr>
</table><br>



## Наша команда:

<table  align="left">
  <tr>
    <td align="center" width="110">
      <a href="https://github.com/Alesia0401">
    <img alt="Alesia" src="https://img.shields.io/badge/-Alesia-blue?style=for-the-badge&logo=github&logoColor=white" />
  </a>
    </td>
    <td align="center" width="110">
      <a href="https://github.com/Tatiana-Bessoltseva">
    <img alt="Tatiana" src="https://img.shields.io/badge/-Tatiana-red?style=for-the-badge&logo=github&logoColor=white" />
  </a>
    </td>
    <td align="center" width="110">
      <a href="https://github.com/o-kova">
    <img alt="Olga" src="https://img.shields.io/badge/-Olga-green?style=for-the-badge&logo=github&logoColor=white" />
  </a>
    </td>
    <td align="center" width="110">
      <a href="https://github.com/anna-7nova">
    <img alt="Anna" src="https://img.shields.io/badge/-Anna-yellow?style=for-the-badge&logo=github&logoColor=white" />
  </a>
    </td>
  </tr>
</table><br>


## Установка проекта
Чтобы клонировать проект на свое устройство, используйте комманду ниже:
```
git clone https://github.com/Alesia0401/project-practice-55-1
```
## Работа с проектом
В проекте активно используются **Sass**. Корневой файл с подключаемыми модулями находится в папке *assets/scss*  и называется *style.scss*.
Для работы с данным типом файлов используйте библиотеку Dart Sass, которую можно установить через npm. Для live верстки используется следующая команда:
```
npx sass .\assets\scss\style.scss .\assets\styles\style.min.css --watch
```
Убедитесь, что библиотека Sass установлена глобально.

## Структура сайта
1. Панель навигации
2. Блок заказа товара
3. Блок о наших преимуществах
4. Блок с эсклюзивными вещами
5. Блок с отзывами
6. Блок с мобильными приложениями
7. Контактная информация.

## Методы используемые для верстки сайта.
* В Header элементы позиционированы с помощью flex.
* В блоке Organic применены flex, grid, position.
* Во втором блоке использованы flex, grid, position.Для расположения элементов в контейнере services использовала flex и grid(только для расстояния между кругом и текстом). Для расположения картинок(line, man) применено позиционирование.
* В третьем блоке "explor" позиционирование flex. Блок разреден на 2 основные части: основной контент и описание (текст, ссылка, картинка-оформление).
* Четвертый блок разделен на две секции, в каждой из которых использована flex, grid - верстка. Для расположения картинок применено позиционирование.
При наведении на стрелки переключения отзывов - плавное изменение цвета.
При наведении на кнопку Download изменение курсора.
* В пятом блоке "footer" использовала flex.

Во всем проекте применена адаптивная верстка под 320px, 1280px, 5000px, что позволит удобно пользоваться сайтом на разных устройствах.
Для динамической прогрузки картинок применены различные атрибуты для работы с разными разрешениями.

## Контакты для связи
В случае обнаружения ошибок, предложений и запросов на изменения, связываться с куратором проекта в Slack @Alesia.
