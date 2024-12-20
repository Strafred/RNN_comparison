# RNN Comparison

## Описание проекта
В этом проекте исследуется эффективность различных архитектур рекуррентных нейронных сетей (RNN) для посимвольной генерации текста. Основное внимание уделяется сравнению стандартных RNN, LSTM и GRU моделей.

## Содержание
- [1. Введение](#1-введение)
- [2. Подготовка данных](#2-подготовка-данных)
- [3. Модели](#3-модели)
- [4. Эксперименты](#4-эксперименты)

## 1. Введение
Рекуррентные нейронные сети (RNN) являются мощным инструментом для работы с последовательными данными. В данном проекте мы сравниваем три типа RNN: стандартные RNN, LSTM (Long Short-Term Memory) и GRU (Gated Recurrent Unit) для генерации текста.

## 2. Подготовка данных
Для генерации текста используется набор данных, состоящий из текста различных произведений. Данные предварительно обрабатываются для создания последовательностей фиксированной длины. Каждая последовательность делится на входные и целевые последовательности.

## 3. Модели
В проекте реализованы следующие архитектуры:
- **Стандартная RNN**: Простая модель с рекуррентными связями.
- **LSTM**: Модель с механизмом памяти, позволяющая справляться с долгосрочными зависимостями.
- **GRU**: Упрощённая версия LSTM с меньшим количеством параметров.

## 4. Эксперименты
В рамках экспериментов выполняются следующие шаги:
1. Генерация случайных последовательностей из входного текста.
2. Обучение моделей с различным количеством эпох и размером мини-батча.
3. Запись результатов генерации текстов для анализа.
