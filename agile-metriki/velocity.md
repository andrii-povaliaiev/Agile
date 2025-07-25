# Velocity

### Velocity: вимірювання швидкості команди

#### Як визначити velocity

**Velocity** (швидкість команди) — це показник, який відображає кількість Story Points (або задач), які команда змогла завершити за один спринт. Це один із ключових індикаторів у Scrum та інших Agile-підходах, який дозволяє командам вимірювати власну продуктивність, а також використовувати ці дані для подальшого планування.

<figure><img src="https://github.com/Mykhailo-Andreiev/Agile_GitBook/raw/main/assets/velocity.jpg" alt=""><figcaption></figcaption></figure>

Velocity визначається за простою формулою:

> **Velocity = Сума завершених Story Points за один спринт**

Наприклад, якщо за два тижні команда реалізувала 5 задач, оцінених у 3, 5, 2, 8 та 3 Story Points, то velocity спринту буде **21**.

Важливо враховувати лише ті задачі, які були завершені повністю (тобто мають статус “Done” або пройшли Definition of Done). Незавершені задачі не входять у velocity, навіть якщо виконано більшу їх частину.

#### Як використовувати velocity для прогнозування



Velocity є основою для **емпіричного прогнозування** — процесу, в якому команда оцінює, скільки роботи зможе виконати в майбутньому, виходячи з фактичних результатів попередніх спринтів.

**Як це працює:**



1. **Середнє значення velocity** обчислюється на основі кількох останніх спринтів (рекомендується брати 3–5).
2. Це середнє значення використовується для оцінки кількості Story Points, яку команда зможе реалізувати в наступних ітераціях.
3. На основі цього можна:
   * Розрахувати приблизну кількість спринтів, необхідну для завершення певного обсягу роботи.
   * Побудувати **burnup/burndown графіки**, що відображають прогрес і залишок задач до завершення проєкту.
   * Прогнозувати **дату релізу** або **розмір MVP**, який буде готовий до певної дати.

**Приклад:** Якщо команда має середнє velocity 20 Story Points, а в беклозі залишилося 100 оцінених задач, то команда зможе завершити їх приблизно за 5 спринтів.

> Velocity ≠ ефективність команди. Це не KPI, а лише інструмент для планування.

#### Приклади з життя команди (з графіками або табличками)



**Приклад таблиці velocity за 5 спринтів:**

| Спринт | Story Points |
| ------ | ------------ |
| 1      | 18           |
| 2      | 22           |
| 3      | 19           |
| 4      | 20           |
| 5      | 21           |

**Середнє velocity = (18 + 22 + 19 + 20 + 21) / 5 = 20**

**Графік burndown (згоряння задач):**

* Вісь X — дні спринту
* Вісь Y — кількість Story Points, що залишилися
* Лінія ідеального темпу: рівномірне зменшення задач
* Фактична лінія: показує реальний прогрес

Графік допомагає виявити проблеми з продуктивністю, затримки або перевищення обсягу робіт.

#### Від чого залежить стабільність velocity



Стабільність velocity означає, що команда зберігає подібний рівень продуктивності з ітерації в ітерацію. Це дозволяє точніше планувати та прогнозувати. Однак, стабільність залежить від багатьох факторів:

* **Склад команди** — зміни в команді (прихід новачків або звільнення досвідчених членів) впливають на швидкість.
* **Розмір спринтів** — різна тривалість спринтів не дозволяє прямо порівнювати velocity.
* **Якість беклогу** — якщо задачі нечітко сформульовані або не мають Definition of Ready, це гальмує виконання.
* **Зовнішні чинники** — відпустки, технічні проблеми, релізи, залежності від інших команд.
* **Недооцінка складності** — якщо команда систематично недооцінює задачі, velocity буде коливатися.
* **Рівень взаємодії** — низька синхронізація в команді зменшує продуктивність.

Тому стабільність velocity — це не лише технічне питання, а й показник командної зрілості, якості планування та внутрішніх процесів.
