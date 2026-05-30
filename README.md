# sparse
Simulation of Strategic Pooling for Autonomous Risk-Sharing Entities
_______________________________
ENGLISH


# SPARSE: Strategic Pooling for Autonomous Risk-Sharing Entities

## English

### Description
This project implements the SPARSE protocol, a simulation model for strategic pooling of autonomous risk-sharing entities. Agents with different risk profiles (Risk-Averse, Risk-Neutral, Risk-Seeking) can form pools to reduce systemic risk and improve overall efficiency. The simulation uses real financial data from the S&P 500 loaded via `yfinance`.

### Key Features
- Real S&P 500 stock data (30 stocks, 2 years)
- Three agent types with different risk aversion levels
- Comparison of three modes: No Pooling, Random Pooling, SPARSE
- Market shock simulation at iteration 40
- Comprehensive metrics: efficiency, systemic risk, stability, diversification benefit

### Technologies
- Python 3.12
- numpy, pandas
- matplotlib, seaborn
- yfinance

### Installation
```bash
git clone https://github.com/YOUR_USERNAME/sparse.git
cd sparse
pip install -r requirements.txt
jupyter notebook sparse.ipynb

_______________________________
RUSSIAN


Описание
Проект реализует протокол SPARSE — имитационную модель стратегического пулинга для автономных сущностей, разделяющих риски. Агенты с разными профилями риска (избегающие риска, нейтральные, склонные к риску) могут объединяться в пулы для снижения системного риска и повышения общей эффективности. Симуляция использует реальные финансовые данные S&P 500, загружаемые через yfinance.

Ключевые особенности
Реальные данные акций S&P 500 (30 акций, 2 года)

Три типа агентов с разными уровнями неприятия риска

Сравнение трёх режимов: без пулинга, случайный пулинг, SPARSE

Симуляция рыночного шока на итерации 40

Комплексные метрики: эффективность, системный риск, стабильность, выгода от диверсификации

Технологии
Python 3.12

numpy, pandas

matplotlib, seaborn

yfinance

Установка
bash
git clone https://github.com/YOUR_USERNAME/sparse.git
cd sparse
pip install -r requirements.txt
jupyter notebook sparse.ipynb
Результаты
SPARSE превосходит случайный пулинг и работу без пулинга по ряду метрик, демонстрируя значительные улучшения в эффективности и снижении риска.
