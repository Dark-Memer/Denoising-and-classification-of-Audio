# Denoising-and-classification-of-Audio
Denoising and classification of Audio dataset (mel-spectograms) using Unet

Первое задание = First_task

Задача Denoising и classification решалась на двумя способами:

1) Без использования pythorch lightning
2) С использованием pytorch lightning

Обе задачи решались на сонове Unet

Чтобы протестировать тот или иной результат нужно загрузить необходимые веса, папку с данными и meta-файл и прописать их путь в ноутбуках с названием "Test..." в соответсвующих местах.

Основные этапы задач:

1) Подгрузка датасета (с гугл диска)
2) Создание meta-файла на основе данных
3) Создание класса для данных
4) Разделение датасета на тренировочную (80%) и валидационную (20%) выборки
5) Тренировка
6) Тест

Гиперпараметры:

 model_encoder: resnet18
 learning_rate: 0.0001
 batch_size: 32
 epochs: 50
