# Вправи з Java: методи та Шлях Порожнечі Глеб їсть землю

У буддизмі Порожнеча - це центральне вчення, що вказує на відсутність внутрішньої існування в усіх явищах. У контексті програмування на Java ми можемо дослідити цей концепт через методи - функції, що виконують конкретні завдання та можуть використовуватися для маніпулювання або отримання даних, часто призводячи до трансформації або 'порожнечі'.

Уявімо новачка-монаха на ім'я Тензін, який вивчає Шлях Порожнечі. Він також захоплюється кодуванням і хоче використовувати програмування на Java для кращого розуміння буддійських вчень. Ось деякі вправи, які Тензін може виконати:

## Вправа 1: Миска Будди
**Завдання**: Створіть метод `emptyBowl` (порожня миска), який приймає масив цілих чисел (як їжу в мисці Будди) і робить його порожнім (встановлює всі елементи на 0).

```java
public static void emptyBowl(int[] bowl) {
    // Ваш код тут
}
```
**Приклад вхідних даних**: `{1, 2, 3, 4, 5}`  
**Очікуваний результат**: `{0, 0, 0, 0, 0}`

## Вправа 2: Середина
**Завдання**: Створіть метод `middleNumber` (середнє число), який приймає масив цілих чисел і повертає середнє число. Якщо в масиві парна кількість елементів, поверніть менше з двох середніх чисел.

```java
public static int middleNumber(int[] numbers) {
    // Ваш код тут
}
```
**Приклад вхідних даних**: `{5, 3, 9, 2, 7}`  
**Очікуваний результат**: `9`

## Вправа 3: Мантри
**Завдання**: Створіть метод `countMantras` (підрахунок мантр), який приймає масив рядків з мантрами і рахує, скільки разів з'являється конкретна мантра.

```java
public static int countMantras(String[] mantras, String mantra) {
    // Ваш код тут
}
```
**Приклад вхідних даних**: `{"ом", "ом", "намасте", "ом", "шанті"}`, `"ом"`  
**Очікуваний результат**: `3`

## Вправа 4: Сортування Сангхи
**Завдання**: Створіть метод `sortSangha`, який сортує масив віків монахів за зростанням. Ви можете використовувати сортування бульбашкою.

```java
public static void sortSangha(int[] ages) {
    // Ваш код тут
}
```
**Приклад вхідних даних**: `{30, 25, 35, 28, 29}`  
**Очікуваний результат**: `{25, 28, 29, 30, 35}`



## Вправа 5: Порожній рядок
**Завдання**: Створіть метод `isEmpty` (чи порожній), який перевіряє, чи є рядок порожнім.

```java
public static boolean isEmpty(String s) {
    // Ваш код тут
}
```
**Приклад вхідних даних**: `""`  
**Очікуваний результат**: `true`

## Вправа 6: Чотири благородних істини
**Завдання**: Створіть метод `fourNobleTruths` (чотири благородні істини), який приймає масив рядків і перевіряє, чи містить він Чотири благородні істини буддизму.

```java
public static boolean fourNobleTruths(String[] truths) {
    // Ваш код тут
}
```
**Приклад вхідних даних**: `{"Dukkha", "Samudaya", "Nirodha", "Magga"}`  
**Очікуваний результат**: `true`

## Вправа 7: Колесо Дхарми
**Завдання**: Створіть метод `turnWheel` (повернути колесо), який приймає ціле число `n` і рядок `s`, і друкує рядок `n` разів.

```java
public static void turnWheel(int n, String s) {
    // Ваш код тут
}
```
**Приклад вхідних даних**: `3, "Dharma"`  
**Очікуваний результат**:  
`Dharma`  
`Dharma`  
`Dharma`

## Вправа 8: Таймер медитації
**Завдання**: Створіть метод `meditationTimer` (таймер медитації), який приймає число `minutes` (хвилини) і друкує відлік від `minutes` до `0`.

```java
public static void meditationTimer(int minutes) {
    // Ваш код тут
}
```
**Приклад вхідних даних**: `5`  
**Очікуваний результат**:  
`5`  
`4`  
`3`  
`2`  
`1`  
`0`