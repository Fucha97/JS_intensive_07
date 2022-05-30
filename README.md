#  Lesson 7.

## Contents

1. [Chapter I](#chapter-i) \
   1.1. [React](#react) \
   1.2 [Virtual DOM](#virtual-dom) \
   1.3 [Create react app](#create-react-app) \
2. [Chapter II](#chapter-ii) \
   2.1. [Классовые и функциональные компоненты](#классовые-и-функциональные-компоненты) \
   2.2  [Life циклы компонента](#life-циклы-компонента) \
   2.3. [JSX](#jsx) \
   2.4. [Props](#props) \
   2.5  [React hooks](#react-hooks) 
## Chapter I

В этой главне мы познакомимся с React. Узнаем немного подробностей о его происхождении и сценариях использования, настроим базовый набор инструментов на нашем локальном компьютере и в процессе узнаем немного о том, как React работает.
  
### React

React - это библиотека JavaScript, которая используется для создания пользовательского интерфейса. Первый релиз библиотеки увидел свет в марте 2013 года. Текущей версий на данный момент является версия React v18.0.

Основная цель React - минимизировать ошибки, возникающие при разработке пользовательских интерфейсов. Это достигается за счёт использования компонентов - автономных логических фрагментов кода, которые описывают часть пользовательского интерфейса. А уже эти компоненты объединяются для создания полноценного пользовательского интерфейса. React абстрагирует большую часть работы по визуализации, оставляя вам возможность сосредоточиться на дизайне.

### Virtual DOM

Для решения проблемы производительности React использует концепцию [виртуального DOM](./materials/VirtualDom.md).
### Create react app

[CRA](./materials/CRA.md) предназначен для быстрого создания шаблонных проектов React-приложений.
## Chapter II

### Классовые и функциональные компоненты

Раньше было всего два способа определения React-компонентов, первый — это React.createClass(), а второй — классы ES6.
Дальнейшая эволюция привнесла функциональные компоненты. И хоть состояний они не имели, но отлично подходили для более простых компонентов.
В итоге в версии 16.8 команда React ввела хуки, не только ставя функциональные компоненты вровень с классовыми, но также делая их более лёгкими в написании и даже потенциально превосходящими своих старших собратьев.
Подробнее [тут](./materials/Class_func_components.md)

### Life циклы компонента

[Жизненный цикл компонента в React](./materials/Life_cycles.md) — одна из наиболее важных концепций, которую следует знать. Почему? Потому что понимание жизненного цикла позволит вам правильно обрабатывать события в вашем приложении и обеспечивать корректную передачу данных между компонентами. Компоненты в React рождаются, решают какую-то задачу и прекращают свое существование.

### JSX

[JSX](./materials/JSX.md) - это надстройка на JavaScript, которая позволяет использовать XML-подобный синтаксис в JavaScript.

### Props

Можно передавать данные в компоненты с помощью так называемых [пропсов](./materials//Props.md).

### React hooks

Что же такое хуки?

Хуки — это функции, с помощью которых вы можете «подцепиться» к состоянию и методам жизненного цикла React из функциональных компонентов. Хуки не работают внутри классов — они дают вам возможность использовать React без классов.

Первыe хуки, который мы изучим, это функции [useState и useEffect](./materials/React_hooks.md).

