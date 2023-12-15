# DAinGD_Itog
Отчет по итоговой работе выполнил(а):
- Миронова Наталья Андреевна
- РИ220930
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 100 |


знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Начать обучать ml-agents: доходить до стены wall, не задевая при этом target.

## Ход работы
1. Создала проект Юнити.
2. Добавила ml-agent.
3. Добавила на сцену Cube, Ball и 4 Wall.
4. Создала скрипт RollerBall на основе Agent, используя необходимые методы, такие как OnActionReceived(), CollectObservations(), OnEpisodeBegin(). Также я добавила метод OnTriggerEnter(), чтобы настроить взаимодействие agent, target и wall.
5. Настроила rollerball_config.yaml.
6. С помощью Anaconda Prompt я начала обучение агента.
![image](https://github.com/knightalli/DAinGD_Itog/assets/127225486/bacb8def-04c5-419f-8db1-040459ff79a7)

7. Спустя некоторое время я прекратила тренировку. Результаты записаны в TensorBoard. По ним видно, что ml-agent начал обучаться, но не пока ещё не действует идеально.
![image](https://github.com/knightalli/DAinGD_Itog/assets/127225486/11509293-05ff-4744-b382-e1e2a6b8c6d2)

8. Все награды и процесс обучения также показаны в консоли.
![image](https://github.com/knightalli/DAinGD_Itog/assets/127225486/4225dfc3-7ee9-431b-a71f-45c4acbf7417)




## Выводы
В ходе проекта были успешно выполнены шаги по созданию и обучению агента ML-Agents в Unity. Работа включала подготовку среды, создание агента, настройку обучения, и анализ результатов. Важными выводами являются успешный старт обучения, контроль процесса через TensorBoard, и необходимость дальнейших настроек параметров для улучшения обучаемости и качества поведения агента.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
