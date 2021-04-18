# Игра "Экзамен"
В игре присутствует два типа различных юнитов: студенты и преподаватели.

Игрок играет за студента, который в начале игры выбирает предмет (создается конкретная фабрика, наследник класса `Factory`), потом проходит тесты на определения своего уровня знаний.

После этого происходит распределение по преподавателям в зависимости от уровня везения студенту попадает Easy, Middle или, соответственно, Hard (соответствующие методы getEasyProfessor(), getMiddleProfessor(), getHardProfessor() класса MathanFactory, AlgeomFactory, DMathFacrtory в зависимости от выбранного предмета).

Все юниты преподавателей - наследники публичного класса `Professor`.
