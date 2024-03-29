# Интернет програмирање на клиентска страна

Репозиториум со решени задачи по предметот Интернет програмирање на клиентска страна.

# Организација

Проектот е организиран во следните фолдери:

- [Вежби](вежби) - содржи задачи од аудиториски вежби организирани според темите кои се покриваат во предметот
- [Испитни](испитни) - содржи испитни задачи кои се паднале на претходните сесии

# Додавање на задачи

Задачи се додаваат на следниот начин:

1. Го клонирате проектот локално `git clone https://github.com/ivankitanovski/internet-programiranje.git`.
2. Инсталирате [pre-commit hooks](https://pre-commit.com/). Ова е потребно за стандардизирано форматирање на кодот. 
    - Откако ќе се инсталира. Потребно е во проектот да извршите `pre-commit install`.
3. Креирате нов branch.
4. Секоја задача ја додавате во темата која соодвествува во посебен фолдер. Пр. `Задача ХХ`, каде `XX` е наредниот слободен број за таа тема. Секоја задача треба да има `README.md` фајл каде задачата е поставена, како и решението. Решението треба да биде поставено и во `index.html` фајл, како и дополнитени фајлови, доколку има потреба, како `script.js`, `style.css` и сл. Доколку има слики, тие се ставаат во фолдер `img`.
    - Сликите и ресурсите кои се во проектот да се референцираат релативно.
    - Кодот треба да содржи коментари со кои се објаснува логиката.
    - Подолу е прикажана пример структура. 
```
вежби
│
└───Објекти
│   └───Задача 1
│   │   │   README.md
│   │   │   index.html
│   │   │   script.js
|   |   |   style.css
|   │   └───img
│   |   │   image1.png
│   |   │   image2.png
│   |   │
...
```
5. Правите `commit` и `push` на новите документи.
6. Отворатe `pull request` на проектот на GitHub.

# Кој може да предложи задачи?

Секој заинтересиран може слободно да предложи задачи и да ги додаде во проектот. Сите сугестии се добредојдени. 
