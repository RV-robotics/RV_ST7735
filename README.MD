# RV_ST7735
ИСПОЛЬЗОВАНИЕ БИБЛИОТЕКИ:
1. Создать проект STM32CubeMX и настроить 4 вывода в режиме GPIO Output, Output Push Pull, No pull-up and no pull-down (удобно присвоить им имена). SPI1 в режиме Half-Duplex Master
2. Сгенерировать проект
3. Добавить библиотеку в проект и прописать путь к папке
4. Изменить версию HAL в RV_ST7735.c для вашего семейства микроконтроллера (при необходимости #define выводов GPIO)
5. Добавить #include "RV_ST7735.h" в main.c
