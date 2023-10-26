# Дашборд для благотворительного фонда “Арифметика добра”. Программа “Шанс”

Благотворительный фонд «Арифметика Добра» помогает детям-сиротам и приемным семьям в 35 регионах России. 
В фонде есть программы социализации и обучения детей-сирот, наставничества, поддержки приемных семей, содействия семейному устройству детей из детских домов.


## Задача

Задача проекта — разработать дашборд в DataLens, который поможет анализировать результаты работы фонда и отслеживать достижение целевых показателей по направлениям и программам помощи детям и семьям, а также принимать решения на основе этих данных.

В фонде есть несколько систем по сбору данных:

— 2 базы CRM, связанных между собой

— отчет в формате Excel

Требуется сделать Dashboard по аналогии с готовым отчётом в Excel, обогатив его аналитикой из отчетов, выгруженных из CRM “Шанса”.
В рамках проекта дашборд будет строиться на исторических данных, в дальнейшем планируется подключение к базе данных и обновление информации в режиме реального времени.

Стиль дашборда - бизнес-дашборд, сдержанное оформление.

## Данные

1. Копия отчета с показателями работы фонда "Арифметика Добра" 


2. Файлы выгрузок CRM для построения дашборда по программе “Шанс”:

- Ученики_id - список учеников, которые занимаются онлайн, общая статистика по урокам и тренингам, посещенных учеником по годам
- Учителя_id  - список учителей “Шанса”, общая статистика по количеству учеников и проведенных уроков
- Расписание_id -  расписание уроков
- Список_профи_id - список профессионалов - участников программы “Шанс”
- Тренинги_id - информация по проведенным тренингам
- Достижения - информация по начислениям за достижения по программе геймификации
- Встречи с профи - информация о встречах с профессионалами по программе профориентации


Особенности данных:

- Категории возраста детей: младше 10 лет, 10 - 18 лет, старше 18 лет;
- Москва и Московская область считаются одним регионом;
- Санкт-Петербург и Ленинградская область считаются одним регионом

## Инструменты
*DataLens*




