# vue3-stepper

Дан JS объект steps содержащий в себе этапы прохождения курса. В формате: title - название этапа, text - описание этапа.

Необходимо вывести текст этапа в элементе steps-content а так же номер этапа и его название в виде баблов в элементе steps-list.

Необходимо реализовать переключение по этапам с помощью кнопок Назад и Вперёд или при клике на пункт с этапом.

Пройденные этапы должны пометиться классом done. Текущий этап классом active.

Если указатель стоит на первом этапе, кнопка Назад должна отключиться

Если указатель стит на последнем этапе кнопка Вперёд должна изменить текст на Завершить.

Если нажата кнопка Завершить, необходимоскрыть кнопки Вперёд и Назад и показать кнопку Начать заново.

Если нажата кнопка Начать заново, необходимо вернуть указатель на первый этап показать кнопки Назад и Вперёд 
с преждним функционалом и скрыть кнопку Начать заново.