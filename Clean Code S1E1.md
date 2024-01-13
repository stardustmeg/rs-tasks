# Clean Code S1E1 Suggestions

1. Check if the Cross check form and the task description have the same requirements + decide which should have penalties (i.e. incorrect link?)

_Например: в [ТЗ](https://github.com/rolling-scopes-school/tasks/blob/master/stage1/modules/clean-code/clean-code-s1e1.md#application-functionality) у нас указано, что должна быть засабмичена верная ссылка, и что при невыполнении хоть одного из этих пунктов, студент "может" (см. п. 10) выставить 0 баллов, но в кросс-чек форме этого штрафа нет. Сделано ли это специально? Или нужно сделать форму идентичной ТЗ и прописать штраф именно по пунктам ТЗ?_
_Так же и с остальными пунктами ТЗ и формы._

2. Must the PR be still open? (What will happen if it's merged to main?)

_Нужно ли дополнительно уточнить, что ПР должен быть открыт? Или что ветка `main` не должна в себе ничего содержать лишнего?_

3. Specify which link must be submitted (deploy, PR, repo) + penalty?

_(см. п. 1)_

4. Specify the requirements to commit names? (not recommendation)

_Нужно ли указать хоть какие-то обязательные составляющие коммита? Сейчас получается, что коммит может не содержать пункт правил, а только описание изменений, что сильно затруднит проверку. Например, сделать формат не рекомендацией, а внести как пункт ТЗ? Или уточнить обязательное указание пункта правил и документа (basic/advanced)?_

5. PR description penalty (separate points of self-check or full score?) + penalty?

_Нужно ли снижать баллы за то, что в описании ПР нет проверки по пунктам? Стоит ли это уточнить в ТЗ? (т.к. кому-то за это снимали 45 баллов, как штраф за несоответствие описания ПР)._

6. Personal repo name if not forked (clean-code-s1e1)?

_Нужно ли уточнить, что при создании нового репо, а не форке, у него должно быть определенное имя (как таск?) или название репо может быть любым? Ннужен ли тут какой-то штраф?_

7. How many mistakes + penalties!

_предложение по количеству ошибок см. ниже_

8. Fonts in the picture of the app

_Некоторые снимали баллы "за несоответствие внешнего вида приложения" из-за отличающегося шрифта `fantasy`. Стоит ли отдельно уточнить, что если в девтулсах мы видим шрифт `fantasy`, то всё верно (независимо от того, как он выглядит)? Заменить его на другой шрифт? Сделать ещё картинку для соответствия mac и win? Или сделать деплой приложения в оригинальном репо, чтобы можно было свериться?_

9. Functionality description ([app](https://github.com/rolling-scopes-school/clean-code-s1e1), [task](https://github.com/rolling-scopes-school/tasks/blob/master/stage1/modules/clean-code/clean-code-s1e1.md#application-functionality))

_В одном списке 8 пунктов, во втором 9 (+ `The appearance of the application has not been changed.`) Сопоставить и сделать одинаковыми_

10. Check the modal verbs throughout the [description](https://github.com/rolling-scopes-school/tasks/blob/master/stage1/modules/clean-code/clean-code-s1e1.md)and Cross-check form and Cross-check form (`should`, `can` => `must`)

_Стоит ли заменить глаголы на `must` вместо `can`? (см. п. 1) Обязательно ли применять штрафы? Если нет, то что считать некачественной проверкой? Если да, то стоит заменить на `must`._

11. Remove `<br>` before [app](https://github.com/rolling-scopes-school/clean-code-s1e1) in Cross-check form

_Чуток пофиксить форму, т.к. перенос всё равно не отображается_

12. Are code formatters allowed (like Prettier)?

_Стоит ли отдельно запретить форматтеры? Работа с ними всё равно попадёт под пенальти про несколько несвязанных изменений, но отдельный штраф за наличие таких конфигов мог бы упростить проверку (особенно если как-то менять систему штрафов)._

13. Why this phrase? `Learn and apply all code refactoring tools that your IDE has.` [Recommendations](https://github.com/rolling-scopes-school/tasks/blob/master/stage1/modules/clean-code/clean-code-s1e1.md#recommendations)
14. Check the [description](https://github.com/rolling-scopes-school/tasks/blob/master/stage1/modules/clean-code/clean-code-s1e1.md#evaluation-criteria) (`loyally`)
15. Why this happened? English?
16. Ordered list [Requirements](https://github.com/rolling-scopes-school/tasks/blob/master/stage1/modules/clean-code/clean-code-s1e1.md#implementation-requirements)
17. Specify `alt=""` must be present for all elements? + Functionality (`Complete functionality must be kept for all elements (including new items).`) + penalty
18. Commit `init:` to start a project

Idea: Three strikes and you're out!

Each penalty - 15 points
or
One penalty - 5 points
The rest - 20 points

Получили баллы: 1046 / 1886 (55.46% )

    Баллы: 1 - 10, Кол-во: 11 (1.05%)
    Баллы: 11 - 21, Кол-во: 49 (4.68%)
    Баллы: 22 - 26, Кол-во: 40 (3.82%)
    Баллы: 27 - 30, Кол-во: 55 (5.26%)
    Баллы: 31 - 35, Кол-во: 43 (4.11%)
    Баллы: 36 - 39, Кол-во: 90 (8.60%)
    Баллы: 40 - 41, Кол-во: 71 (6.79%)
    Баллы: 42 - 43, Кол-во: 152 (14.53%)
    Баллы: 44 - 44, Кол-во: 133 (12.72%)
    Баллы: 45, Кол-во: 402 (38.43%)

Получили 0 баллов за задание: 15
