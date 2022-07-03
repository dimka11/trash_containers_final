# Оптимизация работы коммунальных служб


Задача «Оптимизация работы коммунальных служб»

Качество снимков имеет три категории:

● неудовлетворительного качества;

● с отсутствующими мусорными баками;

● соответствующие всем необходимым условиям.


По загруженной фотографии необходимо определить, к какой категории относится снимок.


Веса для инференса:

https://drive.google.com/file/d/11OOHWWhYF0tn_X8_5q4IbTY2pOl-kVZT/view?usp=sharing

Блокнот обучения, инференс:

trash-containers-cls-swin-final.ipynb

Только инференс:

TBA

Сменить пути к папкам: в

train_csv = pd.read_csv('../input/trash-containers/train_dataset_train/train.csv')

* ConfigDataTransform

* Config. ...

* if ConfigDataTransform.remove_dirty_labels or ConfigDataTransform.replace_dirty_labels:

Тренировка, валидация включаются в Config (train, val параметры)

По всем вопросам в tg: @dimkoss11



