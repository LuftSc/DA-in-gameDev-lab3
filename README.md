# DA-in-gameDev-lab3
Отчет по лабораторной работе #3 выполнил(а):
- Бердышев Артём Александрович
- РИ210942
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | # | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Познакомиться с программными средствами для создания системы машинного обучения и ее интеграции в Unity.

## Задание 1
Реализовать систему машинного обучения в связке Python - Google-Sheets – Unity.

- Создайте новый пустой 3D проект на Unity.
![изображение](https://user-images.githubusercontent.com/104849066/197459610-6679cbe6-cf1a-4c47-9549-45d80fcdd11b.png)

- Скачайте папку с ML агентом.
![изображение](https://user-images.githubusercontent.com/104849066/197460145-301a2fbb-26ea-4713-b0f8-62f3528a43e8.png)

- В созданный проект добавьте ML Agent, выбрав Window - Package Manager - Add Package from disk.
![изображение](https://user-images.githubusercontent.com/104849066/197460571-041e5441-e921-48a9-92d1-ea73e2416d73.png)
![изображение](https://user-images.githubusercontent.com/104849066/197461010-71d3c2e0-0244-41af-b0d0-6735ba624ddf.png)

- Если все сделано правильно, то во вкладке с компонентами (Components) внутри Unity вы увидите строку ML Agent.
![изображение](https://user-images.githubusercontent.com/104849066/197461188-589c13c2-b764-494e-97bf-45fa317634f1.png)

- Далее запускаем Anaconda Prompt для возможности запуска команд через консоль.
![изображение](https://user-images.githubusercontent.com/104849066/197466269-491750d4-893e-41b1-b5b5-58a460310faa.png)
![изображение](https://user-images.githubusercontent.com/104849066/197466565-c0dcd004-6334-4029-9da4-111487ae46ec.png)

- Далее пишем серию команд для создания и активации нового ML-агента, а также для скачивания необходимых библиотек:
![изображение](https://user-images.githubusercontent.com/104849066/197467179-ceeb785e-9a8f-4611-afed-f888088df7ff.png)
![изображение](https://user-images.githubusercontent.com/104849066/197472443-60c230de-bc40-4b6d-86db-b3e44662cd52.png)

- Создайте на сцене плоскость, куб и сферу так, как показано на рисунке ниже. Создайте простой C# скрипт-файл и подключите его к сфере:
![изображение](https://user-images.githubusercontent.com/104849066/197475132-586fe01c-ab36-48d6-af34-434b71b84875.png)

- В скрипт-файл RollerAgent.cs добавьте код, опубликованный в материалах лабораторных работ
![изображение](https://user-images.githubusercontent.com/104849066/197477258-e87c93ca-cd09-4f79-8568-484ee5b1803f.png)

- Объекту «сфера» добавить компоненты Rigidbody, Decision Requester, Behavior Parameters и настройте их 
![изображение](https://user-images.githubusercontent.com/104849066/197479528-14289000-68b5-41b1-853b-6c9df8a8a541.png)

- В корень проекта добавьте файл конфигурации нейронной сети
![изображение](https://user-images.githubusercontent.com/104849066/197492097-87c5a102-958e-49d4-83bb-04d68bc6a23e.png)

- Запустите работу ml-агента
![изображение](https://user-images.githubusercontent.com/104849066/197494646-6c52f4ee-ee4f-4bb9-9211-ea3e9421b672.png)

- Вернитесь в проект Unity, запустите сцену, проверьте работу ML-Agent’a.
![изображение](https://user-images.githubusercontent.com/104849066/197501001-372f3d47-4589-41d9-b4ec-e010ca796c1d.png)

- Сделайте 9 копий модели «Плоскость-Сфера-Куб», запустите симуляцию сцены и наблюдайте за результатом обучения модели.
![изображение](https://user-images.githubusercontent.com/104849066/197503002-1a006c06-ce7a-4422-ae33-fbaff86c3ac4.png)

- Сделайте 36 копий модели «Плоскость-Сфера-Куб», запустите симуляцию сцены и наблюдайте за результатом обучения модели.
![изображение](https://user-images.githubusercontent.com/104849066/197503835-0d85b753-ff5b-49e3-84c7-a97d4d358d12.png)

- После завершения обучения проверьте работу модели.
![изображение](https://user-images.githubusercontent.com/104849066/197505896-dbd39cec-e303-4b26-a922-5ea7191a510e.png)

## Выводы
В ходе выполнения этой лабораторной работы мы обучали сферу катиться в сторону кубика, я впервые попробовал использовать машинное обучение (MLAgent).
В результате выполнения 1 задания я получил работающую модель машинного обучения и небольшой опыт в ее создании. Мне это очень понравилось, я думаю, что 
в дальнейшем точно буду использовать такую технологию.



