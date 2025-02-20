# Tesseract OCR

## Содержание
- [Установка](#установка)
- [Пример](#пример)

## Установка

Для работы модели необходимо установить приложение:

[Скачать Tesseract](https://github.com/UB-Mannheim/tesseract/releases/download/v5.4.0.20240606/tesseract-ocr-w64-setup-5.4.0.20240606.exe)

Эти пункты при установке нужно сделать обязательно:

1. В "Режиме установки" выбираем пункт "Установить для всех пользователей".

   ![image](https://github.com/user-attachments/assets/cacc5052-d739-45ed-80ac-7f3075a9d875)

2. В компоненты устанавливаемой программы выбираем дополнительный пункт "Additional language data (download)" - он нужен для добавления дополнительных языков. Для данной работы хватит добавить только русский язык. Английский язык устанавливается по умолчанию.

   ![image](https://github.com/user-attachments/assets/94bc6a66-1929-45b5-8592-f91f59930b5a)

## Пример

Пусть до tesseract по умолчанию: `C:\Program Files\Tesseract-OCR\tesseract.exe`

Изображение: [rexona.jpg](tessfiles/Tesseract/input.jpg)

Текст: [example.txt](tessfiles/OutputMessage/example.txt)
