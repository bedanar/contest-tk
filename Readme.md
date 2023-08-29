# Изучение датасета
### Что такое image captioning?
Image captioning - это задача "описания" содержания изображения, которое максимально точно передает контекст изображения.
### Почему над этим работают?
Image captioning берет на себя несколько важных задач:
1. Описание изображения для людей с ограниченными возможностями
2. Индексация и поиск изображений в Интернете и других ресурсах
3. Помощь в анализе медицинских изображений
4. Индивидуальный подбор и фильтрация контента в социальных сетях
5. Создание описаний для роботов и автономных систем
### Как формаулируется задача?
Задача генерации текста, где модель обучается на большом датасете из изображений и их описания. Во время обучения модель изучает важные компоненты изображения и сопоставляет их с текстовым смыслом. Поставновка задачи: 
```Дано: Изображение Х. Задача: Создать текстовое описание D, которое максимально точно и подробно описывает содержание изображения Х.```