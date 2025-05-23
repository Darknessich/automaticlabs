# Автоматизированные лабораторные работы с элементами соревнования

Проект включает в себя две основные части:

1. Система турнира по упрощенным шахматам 5×5
2. Библиотека для управления роботом

## Шахматы 5×5

### Особенности

- Доска размером 5×5
- Фигуры: пешки, ладьи, слоны, король
- Победа достигается путем съедения короля
- При одновременном нападении на королей победа присуждается атакующему (кто сделал ход)
- Запрещены рокировка и взятие на проходе
- Пешка превращается в ладью при достижении последней горизонтали

### Функция оценки позиции

- Контроль центра
- Продвижение пешек
- Материальное преимущество

## Библиотека управления роботом

### Основные команды

- `forward()` - движение вперед на одну клетку
- `backward()` - движение назад на одну клетку
- `turn_left()` - поворот на 90° влево
- `turn_right()` - поворот на 90° вправо
- `is_wall_*()` - проверка наличия стены в указанном направлении
- `fill_area()` - заливка текущей клетки

### Особенности

- Автоматическая проверка границ поля
- Оптимизированный алгоритм заливки области
- Визуализация состояния робота и поля

## Установка и запуск

1. Клонируйте репозиторий
2. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```
3. Запустите тесты:
   ```bash
   python -m pytest
   ```

## Участие в разработке

1. Создайте форк репозитория
2. Создайте ветку для новой функции
3. Внесите изменения
4. Отправьте pull request

