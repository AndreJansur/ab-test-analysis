# A/B Test Analysis (Paywall Conversion)

**Мета:** порівняти конверсію між групами A/B і перевірити статистичну значущість (χ²), показати 95% Wilson CI та динаміку CR by day.

## 🔧 Стек
- Python: pandas, numpy, scipy, matplotlib, seaborn
- Jupyter
- Дані: `data/ab_test_data.csv` 

## 📓 Ноутбук
[▶️ Відкрити в Colab](https://colab.research.google.com/github/AndreJansur/ab-test-analysis/blob/main/notebooks/ab.ipynb)

## 📂 Структура
notebooks/ab_test_analysis.ipynb
data/ab_test_data.csv 
requirements.txt
README.md

## 🧪 Що робиться в ноутбуку
1. Завантаження та підготовка даних до рівня користувача
2. Розрахунок CR по групах
3. χ²-тест (scipy.stats.chi2_contingency)
4. 95% Wilson CI для CR
5. Графіки: стовпчики CR з CI, лінія CR by day
6. Підсумкові висновки (p-value, ефект, інтервали)

## ⚠️ Примітки
- Без персональних даних і секретів (API keys).
- Великі або приватні датасети не завантажуються в репозиторій.
