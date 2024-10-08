Проект в области компьютерного зрения. Цель – обучение нейросети ResNet предсказывать возраст человека на фотографии.

Модель ResNet50 показала высокую эффективность в задаче классификации возраста по фотографиям людей. Достигнутое значение MAE равное 7.3 на тестовой выборке подтверждает успешность обучения модели. Это значение значительно ниже целевого порога в 8, что говорит о способности модели точно предсказывать возраст человека на основе его фотографии.

Оптимизация процесса обучения с использованием Adam с низким значением learning rate (0.0001) и применение аугментации данных в виде случайных поворотов на 10 градусов и горизонтальных отражений, а также изменение размера изображений до 150x150 пикселей, позволили улучшить обобщающую способность модели и повысить её устойчивость к изменениям в данных.

Ограничение в 7 эпох обучения может быть связано с необходимостью дальнейшего анализа и оптимизации гиперпараметров модели для достижения ещё более точных результатов. Однако уже достигнутые результаты являются многообещающими и открывают перспективы для дальнейших исследований в области распознавания возраста по фотографиям.
