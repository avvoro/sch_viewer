Среда работы ГДМ* (Schedule manager)

ГДМ представляет собой набор ключевых слов разбитых по секциям. 
Schedule секция представляет собой чередование ключевых слов управления добычей и временных шагов (кл. слово DATES и TSTEP). Таким образом создается динамический контроль добычи в симуляторе. 

Для одной модели инициатива должна:
1. Давать возможность просматривать, редактировать и удалять все ключевые слова с фильтрацией по дате и типу ключевого слова (настроил фильтр, вызвал метод Удаление)
2. Иметь возможность добавлять ключевые слова в виде словаря {дата:текст ключевого слова}, (на этапе создания интерфейса из текстового формата/Excel формата/буфера обмена). В том числе для дат, не представленных в модели.
3. Для всех ключевых слов необходимо распознавать содержательную часть и комментарий вначале.
4. Для некоторых ключевых слов необходимо распознавать содержательную часть согласно правилу каждого ключевого слова давать дополнительную размерность для фильтрации (wconprod, wconhist, gconprod, wconprod, wefac, gefac, wpimult, wdfac, wvfpdp, nodeprop, branprop, compdat, compdatmd, gnetdp, wnetdp)