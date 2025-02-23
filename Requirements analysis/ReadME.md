
## Тест-кейси

### **Тест-кейс 1: Перехід по картці "Do Your Workout"**
- **ID:** TC_01
- **Передумови:** Користувач знаходиться на екрані **"Personal Plan"**
- **Кроки:**
  - Натиснути на картку **"Do Your Workout"**
- **Очікуваний результат:**
  - Користувач переходить у вкладку **"Workouts"**.
  - Відображається блок **"Today’s Activity"**.

### **Тест-кейс 2: Відображення "Today’s Activity" з однією активністю**
- **ID:** TC_02
- **Передумови:** Користувач вибрав 1 активність у налаштуваннях
- **Кроки:**
  - Відкрити вкладку **"Workouts"**
- **Очікуваний результат:**
  - Блок **"Today’s Activity"** містить заголовок "Recommended for you".
  - Підзаголовок: "Get daily workouts tailored to your goal and interest in [Chosen Activity #1]."

### **Тест-кейс 3: Відображення "Today’s Activity" з двома або трьома активностями**
- **ID:** TC_03
- **Передумови:** Користувач вибрав 2 або 3 активності у налаштуваннях
- **Кроки:**
  - Відкрити вкладку **"Workouts"**
- **Очікуваний результат:**
  - Блок **"Today’s Activity"** містить заголовок "Recommended for you".
  - Підзаголовок: "Get daily workouts tailored to your goal and interests in [Chosen Activity #1], [#2] and [#3]."

### **Тест-кейс 4: Виконання одного тренування**
- **ID:** TC_04
- **Передумови:** Користувач має доступне тренування у **"Today’s Activity"**
- **Кроки:**
  - Виконати одне тренування
- **Очікуваний результат:**
  - Підзаголовок змінюється на **"Great job! [N] more workout left"**.

### **Тест-кейс 5: Виконання всіх тренувань**
- **ID:** TC_05
- **Передумови:** Користувач має 2 або 3 активності у **Today’s Activity**
- **Кроки:**
  - Виконати всі тренування
- **Очікуваний результат:**
  - Підзаголовок змінюється на **"All workouts done! For an extra challenge, check out the workout library below"**.

### **Тест-кейс 6: Відображення виконаної картки "Do Your Workout"**
- **ID:** TC_06
- **Передумови:** Користувач виконав всі тренування у **Today’s Activity**
- **Кроки:**
  - Повернутися на екран **Personal Plan**
- **Очікуваний результат:**
  - Картка **Do Your Workout** відмічена як виконана.

### **Тест-кейс 7: Клікабельність картки "Do Your Workout"**
- **ID:** TC_07
- **Передумови:** Користувач знаходиться на екрані **Personal Plan**
- **Кроки:**
  - Натиснути в будь-якому місці картки **Do Your Workout**
- **Очікуваний результат:**
  - Відкривається екран **Workout Preview**.




