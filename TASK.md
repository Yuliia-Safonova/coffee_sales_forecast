# ☕ Aufgabenstellung / Опис завдання

---

## 🇩🇪 Deutsch

# ☕ Verkaufsprognose mit Python
### Einfache Machine-Learning-Aufgabe (scikit-learn)

**Link zu den Daten:** `coffee_sales`
**Link zum Colab-Notebook:** `coffee_forecast.ipynb`

### Worum es in dieser Aufgabe geht

In diesem Projekt trainieren Sie Ihr erstes Machine-Learning-Modell — eines, das die zukünftigen Umsätze eines Cafés auf Basis vergangener Daten prognostiziert. Dabei verwenden Sie `scikit-learn`, das beliebteste ML-Tool in Python.

Sie müssen keine Programmiererin sein. Fast der gesamte Code ist bereits geschrieben. Sie müssen lediglich die Zellen der Reihe nach ausführen und 2–3 kleine Lücken ausfüllen. Der Schwerpunkt dieser Aufgabe liegt nicht auf dem Code, sondern auf der Fähigkeit, das Ergebnis in einfachen Worten zu erklären — so, wie es eine echte Analystin vor der Geschäftsführung tun würde.

> 💡 Das Modell, das Sie erstellen, heißt „lineare Regression". Dies ist die einfachste Form der Prognose: Das Modell zieht eine gerade Linie durch Ihre Daten und verlängert sie in die Zukunft. Einfach, aber sehr nützlich, um die Grundlagen zu verstehen.

### Die Ausgangssituation

Sie sind Analystin der Café-Kette **„CoffeeTime"**. Sie verfügen über Daten zum monatlichen Umsatz der letzten 3 Jahre (2022–2024) — 36 Monate. Der Direktor erstellt das Budget für das kommende Jahr und fragt Sie: **„Wie viel werden wir im ersten Halbjahr 2025 verdienen?"** Ihre Aufgabe ist es, eine Prognose zu erstellen und — am wichtigsten — dem Direktor ehrlich zu erklären, wie sehr dieser Prognose vertraut werden kann.

### Dateien

- `coffee_forecast.ipynb` — das Notebook mit der Aufgabe (in Google Colab öffnen)
- `coffee_sales.csv` — die Umsatzdaten (im selben Ordner wie das Notebook ablegen)

### Vorgehensweise

1. Öffnen Sie `coffee_forecast.ipynb` und lesen Sie die Erklärungen zu jedem Schritt.
2. Führen Sie die Zellen der Reihe nach von oben nach unten aus (Shift + Enter).
3. Füllen Sie an den mit `# ⬅️ ВАШ КОД` markierten Stellen die Lücke aus (jeweils buchstäblich eine Zeile).
4. Beantworten Sie die Interpretationsfragen (4 Pflichtfragen + 1 Bonusfrage) — das ist der wichtigste Teil. Schreiben Sie die Antworten direkt ins Notebook.

### Was Sie tun werden (8 Schritte)

- **Schritt 1–2:** Bibliotheken einbinden, Daten laden
- **Schritt 3:** Diagramm erstellen und die Daten visuell betrachten
- **Schritt 4–5:** Daten vorbereiten und Modell trainieren (Hauptlücke: Aufruf von `.fit()`)
- **Schritt 6:** prüfen, wie gut das Modell die Vergangenheit beschreibt
- **Schritt 7:** 🔮 Prognose für die nächsten 6 Monate erstellen
- **Schritt 8:** ⭐ Bonus — Prognose für einen einzelnen Monat

### Das Wichtigste: die Interpretationsfragen

Im Notebook gibt es 4 Pflichtfragen (plus Bonus). Sie sind das Herzstück der Aufgabe. Worum es dabei geht, damit Sie wissen, worauf Sie achten sollten:

- 🧠 **Frage 1** — das Diagramm lesen: welche Richtung hat der Trend, gibt es saisonale Schwankungen.
- 🧠 **Frage 2** — die Bedeutung der „Steigung": was die Steigungszahl für den Direktor in einfachen Worten bedeutet (um wie viel UAH der Umsatz monatlich steigt).
- 🧠 **Frage 3** — warum die Punkte nicht exakt auf der Linie liegen, und ob eine einfache Gerade ausreicht.
- 🧠 **Frage 4** (die wichtigste) — ob der Prognose vertraut werden kann, welche Grenzen sie hat, und warum eine „unendlich" fortgesetzte Gerade für ein Unternehmen gefährlich sein kann.

> 💡 Es gibt keine einzige „richtige" Antwort auf die Interpretationsfragen. Bewertet wird, ob Sie verstehen, was das Modell tut, und ob Sie seine Grenzen erkennen. Ein ehrliches „der Prognose kann nicht vollständig vertraut werden, weil..." ist wertvoller als ein naives „das Modell hat 31.539 UAH gesagt, also wird es so sein".

### Abgabe

- Das ausgefüllte Notebook `coffee_forecast.ipynb` mit allen ausgeführten Zellen (damit die Diagramme sichtbar sind) (Link zu Google Colab)
- Antworten auf alle 4 Fragen + Bonus, direkt im Notebook geschrieben

> 💡 Stellen Sie vor der Abgabe sicher, dass das Notebook von oben nach unten fehlerfrei ausgeführt werden kann. Die Diagramme müssen angezeigt werden.

### Bewertungskriterien

| Kriterium | Punkte |
|---|---|
| Code funktioniert (Lücken ausgefüllt, Notebook läuft) | 30 |
| Fragen 1–2: Diagramm lesen und Verständnis der „Steigung" | 20 |
| Frage 3: Verständnis, warum die Punkte von der Linie abweichen | 15 |
| Frage 4: Verständnis der Grenzen der Prognose (am wichtigsten) | 30 |
| Bonus: Prognose für einen einzelnen Monat + Begründung | 5 |

Viel Erfolg! Denken Sie daran: Eine Analystin, die die Grenzen des Modells versteht, ist wertvoller als jemand, der nur weiß, wie man einen Knopf drückt. ☕📈

---
---

## 🇺🇦 Українська

# ☕ Прогнозування продажів з Python
### Просте завдання з машинного навчання (scikit-learn)

**Посилання на дані:** `coffee_sales`
**Посилання на колаб:** `coffee_forecast.ipynb`

### Про що це завдання

У цьому проєкті ви навчите свою першу модель машинного навчання — таку, що прогнозує майбутні продажі кав'ярні на основі минулих даних. Ви скористаєтесь бібліотекою `scikit-learn`, найпопулярнішим інструментом ML у Python.

Не потрібно бути програмістом. Майже весь код уже написаний. Вам треба лише запускати клітинки по черзі та заповнити 2-3 маленькі пропуски. Головне у цьому завданні — не код, а вміння пояснити результат простими словами, як це робить справжній аналітик перед керівництвом.

> 💡 Модель, яку ви побудуєте, називається «лінійна регресія». Це найпростіший вид прогнозування: модель проводить пряму лінію крізь ваші дані й продовжує її в майбутнє. Проста, але дуже корисна для розуміння основ.

### Легенда

Ви — аналітик мережі кав'ярень **"CoffeeTime"**. У вас є дані про щомісячну виручку за 3 роки (2022–2024) — 36 місяців. Директор готує бюджет на наступний рік і питає вас: **"Скільки ми зароблятимемо в першій половині 2025 року?"** Ваше завдання — побудувати прогноз і, найголовніше, чесно пояснити директору, наскільки цьому прогнозу можна довіряти.

### Файли

- `coffee_forecast.ipynb` — ноутбук із завданням (відкрийте в Google Colab)
- `coffee_sales.csv` — дані про виручку (покладіть у ту саму папку, що й ноутбук)

### Як виконувати

1. Відкрийте `coffee_forecast.ipynb` і читайте пояснення до кожного кроку.
2. Запускайте клітинки по черзі, зверху вниз (Shift + Enter).
3. Там, де стоїть позначка `# ⬅️ ВАШ КОД`, заповніть пропуск (це буквально 1 рядок).
4. Відповідайте на питання на інтерпретацію (їх 4 + бонус) — це найважливіша частина. Пишіть відповіді прямо в ноутбуці.

### Що ви робитимете (8 кроків)

- **Крок 1-2:** підключаєте бібліотеки, завантажуєте дані
- **Крок 3:** будуєте графік і дивитесь на дані очима
- **Крок 4-5:** готуєте дані й навчаєте модель (тут головний пропуск — виклик `.fit()`)
- **Крок 6:** перевіряєте, як модель описує минуле
- **Крок 7:** 🔮 будуєте прогноз на 6 місяців уперед
- **Крок 8:** ⭐ бонус — прогноз на окремий місяць

### Головне: питання на інтерпретацію

У ноутбуці є 4 обов'язкові питання (плюс бонус). Вони — серце завдання. Ось про що вони, щоб ви знали, на що звертати увагу:

- 🧠 **Питання 1** — читання графіка: який напрямок тренду, чи є сезонні коливання.
- 🧠 **Питання 2** — сенс «нахилу»: що число нахилу означає для директора простими словами (на скільки грн зростає виручка щомісяця).
- 🧠 **Питання 3** — чому точки не лежать ідеально на лінії, і чи достатньо простої прямої.
- 🧠 **Питання 4** (найважливіше) — чи можна довіряти прогнозу, які його обмеження, і чому пряма лінія «в нескінченність» небезпечна для бізнесу.

> 💡 Не існує єдиної «правильної» відповіді на питання інтерпретації. Ми оцінюємо, чи ви розумієте, що робить модель, і чи бачите її обмеження. Чесне «прогнозу не можна повністю довіряти, бо...» цінніше за наївне «модель сказала 31 539 грн, значить так і буде».

### Що здати

- Заповнений ноутбук `coffee_forecast.ipynb` з усіма запущеними клітинками (щоб було видно графіки) (посилання на гугл колаб)
- Відповіді на всі 4 питання + бонус, написані прямо в ноутбуці

> 💡 Перед здачею переконайтесь, що ноутбук запускається зверху вниз без помилок. Графіки мають відображатись.

### Критерії оцінювання

| Критерій | Бали |
|---|---|
| Код працює (пропуски заповнено, ноутбук запускається) | 30 |
| Питання 1-2: читання графіка та розуміння «нахилу» | 20 |
| Питання 3: розуміння, чому точки відхиляються від лінії | 15 |
| Питання 4: розуміння обмежень прогнозу (найважливіше) | 30 |
| Бонус: прогноз на окремий місяць + міркування | 5 |

Успіху! Пам'ятайте: аналітик, який розуміє обмеження моделі, цінніший за того, хто просто вміє натиснути кнопку. ☕📈
