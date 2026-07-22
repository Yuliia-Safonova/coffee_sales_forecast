# ☕ Coffee Sales Forecast

---

## 🇩🇪 Deutsch

### 📌 Projektübersicht

Dieses Projekt zeigt den vollständigen Ablauf eines einfachen Machine-Learning-Projekts zur Prognose zukünftiger Verkaufszahlen eines Cafés.

Auf Grundlage historischer Monatsumsätze wird ein Modell der linearen Regression erstellt, um den Umsatz für die ersten sechs Monate des Jahres 2025 vorherzusagen.

Der Schwerpunkt liegt nicht nur auf der Erstellung des Modells, sondern auch auf der Interpretation der Ergebnisse und der Bewertung der Zuverlässigkeit der Prognose.

---

### 🎯 Projektziel

Das Management einer Café-Kette möchte den zukünftigen Umsatz besser einschätzen, um die Budgetplanung für das kommende Jahr zu unterstützen.

Mithilfe historischer Verkaufsdaten wird ein Machine-Learning-Modell trainiert, das zukünftige Monatsumsätze prognostiziert.

---

### 📊 Datensatz

Der Datensatz enthält die monatlichen Umsätze eines Cafés im Zeitraum von 2022 bis 2024 (36 Monate).

**Verwendete Variable**

- Monatlicher Umsatz

---

### 🛠️ Verwendete Technologien

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

### 🔍 Projektablauf

- Laden der Daten
- Explorative Datenanalyse (EDA)
- Visualisierung der Umsatzentwicklung
- Vorbereitung der Daten
- Training eines Linear-Regression-Modells
- Bewertung des Modells
- Umsatzprognose für zukünftige Monate
- Interpretation der Ergebnisse

---

### 📈 Ergebnisse

**Modellgüte**

Das trainierte Modell erklärt mit einem Bestimmtheitskoeffizienten von **R² = 0,93** rund 93 % der Umsatzschwankungen allein anhand der Monatsnummer — ein sehr guter Wert für ein derart einfaches lineares Modell. Der mittlere absolute Fehler liegt bei **MAE ≈ 1.079 UAH**, der quadratische Mittelwertfehler bei **RMSE ≈ 1.285 UAH**, was einer durchschnittlichen Abweichung von etwa **5–6 %** vom tatsächlichen Umsatz entspricht.

**Modellparameter**

- Steigung (Slope): **+459 UAH pro Monat** — der Umsatz wächst laut Modell durchschnittlich um diesen Betrag pro Monat
- Achsenabschnitt (Intercept): 12.247 UAH (ohne praktische betriebswirtschaftliche Bedeutung, da die Daten erst bei Monat 1 beginnen)

**Prognose für das 1. Halbjahr 2025 (Monat 37–42)**

| Monat | Prognostizierter Umsatz |
|---|---|
| 37 (Jan 2025) | ~29.242 UAH |
| 38 (Feb 2025) | ~29.701 UAH |
| 39 (Mär 2025) | ~30.161 UAH |
| 40 (Apr 2025) | ~30.620 UAH |
| 41 (Mai 2025) | ~31.079 UAH |
| 42 (Jun 2025) | ~31.539 UAH |

**Wichtigste Erkenntnis**

Das lineare Modell beschreibt den historischen Trend gut, geht jedoch von einem konstanten, unbegrenzten Wachstum aus. Saisonale Effekte, Marketingmaßnahmen, Wettbewerb, Preisänderungen oder eine mögliche Marktsättigung werden nicht berücksichtigt. Die Zuverlässigkeit der Prognose nimmt mit zunehmendem Zeithorizont ab — die Prognose sollte daher als grobe Orientierung für die Budgetplanung dienen, nicht als exakte Vorhersage.

---

### 📁 Repository-Struktur

```
coffee_sales_forecast/
│
├── data/
│   └── coffee_sales.csv
│
├── notebooks/
│   └── coffee_forecast.ipynb
│
├── README.md
└── TASK.md
```

---

### 🚀 Mögliche Erweiterungen

- Berücksichtigung saisonaler Effekte
- Vergleich mit weiteren Regressionsmodellen
- Hyperparameter-Optimierung
- Verwendung eines größeren Datensatzes

---

### 👩‍💻 Autorin

**Yuliia Safonova**

Data Analytics & Machine Learning Portfolio

---
---

## 🇺🇦 Українська

### 📌 Огляд проєкту

Цей проєкт демонструє повний цикл простого проєкту машинного навчання для прогнозування майбутніх продажів кав'ярні.

На основі історичних щомісячних даних про виручку побудовано модель лінійної регресії для прогнозування виручки на перші шість місяців 2025 року.

Акцент зроблено не лише на побудові моделі, а й на інтерпретації результатів та оцінці надійності прогнозу.

---

### 🎯 Мета проєкту

Керівництво мережі кав'ярень хоче краще оцінити майбутню виручку, щоб полегшити бюджетне планування на наступний рік.

За допомогою історичних даних про продажі навчається модель машинного навчання, яка прогнозує майбутню щомісячну виручку.

---

### 📊 Дані

Датасет містить щомісячну виручку кав'ярні за період з 2022 по 2024 рік (36 місяців).

**Використана змінна**

- Щомісячна виручка

---

### 🛠️ Використані технології

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

### 🔍 Хід проєкту

- Завантаження даних
- Розвідувальний аналіз даних (EDA)
- Візуалізація динаміки виручки
- Підготовка даних
- Навчання моделі лінійної регресії
- Оцінка якості моделі
- Прогноз виручки на майбутні місяці
- Інтерпретація результатів

---

### 📈 Результати

**Якість моделі**

Навчена модель має коефіцієнт детермінації **R² = 0,93**, тобто пояснює близько 93% варіації виручки, використовуючи лише номер місяця. Це дуже хороший показник для такої простої лінійної моделі. Середня абсолютна похибка становить **MAE ≈ 1 079 грн**, середньоквадратична похибка — **RMSE ≈ 1 285 грн**, що відповідає відхиленню приблизно на **5–6%** від фактичної виручки.

**Параметри моделі**

- Нахил (slope): **+459 грн на місяць** — саме на стільки в середньому щомісяця зростає виручка згідно з моделлю
- Перетин (intercept): 12 247 грн (не має практичного бізнес-сенсу, оскільки дані починаються з 1-го місяця)

**Прогноз на перше півріччя 2025 року (місяці 37–42)**

| Місяць | Прогнозована виручка |
|---|---|
| 37 (січ. 2025) | ~29 242 грн |
| 38 (лют. 2025) | ~29 701 грн |
| 39 (бер. 2025) | ~30 161 грн |
| 40 (кв. 2025) | ~30 620 грн |
| 41 (трав. 2025) | ~31 079 грн |
| 42 (черв. 2025) | ~31 539 грн |

**Головний висновок**

Лінійна модель добре описує історичний тренд, проте припускає постійне й необмежене зростання. Вона не враховує сезонність, маркетингові акції, конкуренцію, зміну цін чи можливе насичення ринку. Надійність прогнозу знижується зі збільшенням горизонту прогнозування — тому прогноз варто розглядати як орієнтовний для бюджетного планування, а не як точне передбачення.

---

### 📁 Структура репозиторію

```
coffee_sales_forecast/
│
├── data/
│   └── coffee_sales.csv
│
├── notebooks/
│   └── coffee_forecast.ipynb
│
├── README.md
└── TASK.md
```

---

### 🚀 Можливі розширення

- Урахування сезонних ефектів
- Порівняння з іншими регресійними моделями
- Оптимізація гіперпараметрів
- Використання більшого датасету

---

### 👩‍💻 Авторка

**Yuliia Safonova**

Data Analytics & Machine Learning Portfolio
