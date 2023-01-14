Вы находитесь в репозитории учебной дисциплины "Контейнеризация и оркестрация приложений" реализующейся преподавателями [факультета инфокоммуникационных технологий](https://fict.itmo.ru) Университета ИТМО. При разработке учебной программы мы постарались учесть опыт коллег занимающихся исследованиями а данной области, а также применить свой опыт при изучении данных технологий.

> Преподаватели тоже учатся, хорошие преподаватели учатся всю свою жизнь.

По этому постарайтесь отнестись к этой учебной дисциплине ответственно, мы в свою очередь постараемся дать все самые новые и интересные технологии которые помогут вам в вашей будущей карьере. Не бойтесь спрашивать и искать интересные решения в рабочих заданиях, а мы постараемся вам помочь и ответить на все вопросы в рамках тем учебной дисциплины. 
Дерзайте! 

## Обнаружение багов и предложения по улучшению

Если вы нашли баг в этой документации или хотели бы предложить улучшения, откройте [Issue или сделайте PR](https://docs.github.com/desktop/contributing-and-collaborating-using-github-desktop/creating-an-issue-or-pull-request).

### Правила создания Issue

Не забывайте об общих правилах, когда создаете Issue:

1. Обратите внимание, в том ли репозитории вы публикуете обращение.

2. Если вы сообщаете о баге, убедитесь, что подобного Issue ещё нет.

3. Заполняйте заголовок и описание как можно точнее.

4. Желательно включать в заголовок Issue следующие флаги: [BUG], [PROPOSAL], [QUESTION].


## Создание PR

Данная документация может быть изменена посредством [PR (Pull Request)](https://docs.github.com/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) любым участником сообщества. Пожалуйста, не забудьте о простых правилах контрибуции.

### Правила констрибуции в репозиториях

1. Если вы хотели бы предложить небольшие изменения, например такие, как правки опечаток, форматирования, то предпочительнее PR.

2. Понятно опишите проблему и её решение, которое вы предлагаете. При необходимости, можете указать номер Issue.

3. Прежде чем править форматирование, убедитесь, что это действительно нужно.

4. Пожалуйста, постарайтесь придерживаться преобладающего стиля оформления кода и разметки Markdown.

## Локальное развертывание проекта
### Развертывание проекта в Docker контейнере

Command for local deploy in docker container
```
git clone https://github.com/itmo-ict-faculty/application-containerization-and-orchestration
cd application-containerization-and-orchestration
docker pull squidfunk/mkdocs-material
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```