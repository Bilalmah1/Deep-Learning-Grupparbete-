# Grupp 4: Batch size och epoker

Gruppinlämningsuppgift i Deep Learning.

Vi har byggt en CNN-modell som klassificerar bilder från datasetet Fashion MNIST. Projektet undersöker hur batch size och antal epoker påverkar modellens resultat, träningstid och overfitting.

## Gruppmedlemmar

- Bilal Mah
- Martin Westberg
- Tobias Uppenberg
- Hamed Rezaei
- Isac Reger

## Dataset

Vi använder Fashion MNIST från Keras.

Datasetet innehåller:
- 60 000 träningsbilder
- 10 000 testbilder
- 10 klasser
- bilder i storleken 28x28 pixlar

## Modell

Vi använder en CNN-modell med Conv2D, MaxPooling2D, Flatten, Dense och softmax-output.

## Miljö

- Python 3.13.7
- Paket finns i `requirements.txt`

## Kom igång

```bash
git clone https://github.com/Bilalmah1/Deep-Learning-Grupparbete-.git
cd Deep-Learning-Grupparbete-
python -m venv .venv
.venv\Scripts\activate
python -m pip install -r requirements.txt
jupyter notebook
```