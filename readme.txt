﻿Плата BVP_04. 
Cделана в OrCAD 16.6.
Предназначена для работы в аппаратах Р400/Р400м/РЗСК/К400/ОПТИКА как со старыми
панелями, так и с новыми.

>>> v4
Сигналы RxBSP и TxBSP поменяны друг с другом.
На схеме найдена ошибка, сигнал управления МКУ закорочен на землю - т.е. речи нет и не будет.
Работает с платой KVP_03v3.
При работе с платой KVP_03v2 не будет работать ЦС.

>>> v3
Добавлена цифровая ретрансляция.
На схеме найдена ошибка, перепутаны местами сигналы RxBSP и TxBSP. 
Не использовать.
Работает с платой KVP_03v3.
При работе с платой KVP_03v2 не будет работать ЦС.

>>> v2 - СЕРИЯ
Входы управления подключены к 24В вместо земли.
Изменена подтяжка на +5В сигнала речи для варианта К400 (в варианте с речью, 
подтяжка идет к +5ВА).
Неиспользуемые входы микросхемы DD2 подтянуты к земле через резистор 10кОм.
Сделана возможность использования платы для Р400.
Немного передвинуты линии сигнализаций в верхней части.

>>> v1
Первая версия платы. 
На схеме имеются ошибки. 
Не использовать.