# Кронверкские псы

Для правильной работы юпитер ноутбуков нужно установить зависимости из requirements.txt, 
создать папки data/raw и data/processed, загрузить в папку data/raw 2 датасета и 
перенести файл russia.geojson.txt из корня проекта в data/raw.

Запускать все ноутбуки нужно последовательно для правильной работы:
    1_EDA.ipynb -> 2_Feature_Licvid.ipynb -> 3_Segmentation.ipynb -> RETRO.ipynb