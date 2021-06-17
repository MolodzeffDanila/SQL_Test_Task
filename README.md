# SQL_Test_Task
Выполнение тестового задания по построению модели тариф/клиент.

## Задание:
### Требование к процедуре выполнения задания:

    1. Предложить на уровне объектной модели\ER диаграммы оптимальную модель сущности «Тариф» по требованиям пункта 2.
    
    2. Для обеспечения целостности и наглядности модели можно использовать сущности, не заявленные в требованиях.
    
    3. Моделирование может быть выполнено в любом редакторе. 
    
### Описание требований:

Система обеспечивает передачу SMS трафика от Клиентов к SMSC (цент обработки коротких сообщений) операторов. Для каждого клиента на уровне Тарифа устанавливается плата за услугу доставки SMS. Цена сообщения определяется на основании хранимого тарифа. Тарифный план — это набор правил тарификации трафика клиентов в системе. Параметры тарифа:

    1. Тариф может быть применен глобально, к клиенту или к лицевому счёту клиента. Параметры глобального тарифа могут быть переопределены тарифом на клиенте или лицевом счёте (лицевых счетов может быть более одного).   
    
    2. Тариф применяется к конкретному направлению МТ-трафика или к МО-трафику;
    
    3. Тариф может содержать правила для случаев отнесения получателя к тому или иному оператору моб. связи;
    
    4. Тариф может содержать правила формирования цены для диапазона количества сообщений в месяц на уровне лицевого счёта;
    
    5. На уровне тарифа может применяться скидка в % по трафику в зависимости от достижения клиентом минимального количества сообщений. Из подсчёта количества могут быть исключены сообщения на определённого оператора;
    
    6. На уровне тарифа устанавливается фиксированное периодическое начисление;
    
    7. В системе должна быть предусмотрена возможность расширения правил задания цены для тарифа без необходимости изменения модели данных. 

## Выполнение
### Скриншот ER-диаграммы:
![alt text](screenshots/model.PNG "Описание будет тут")
