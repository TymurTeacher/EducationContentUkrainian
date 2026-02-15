### @explicitHints true

# Завдання 2 - Дієтичні вимоги.

```python
blocks.place()
```

## Крок 1
Дайте **першому** собаці все, що вже є у попередньо визначеному списку, змінивши значення перших **4** команд `||blocks:place block at position||`.
Щоб кожна з них розмістила по порядку один з елементів списку. Потім дайте їжу зі скрині собаці номер один.

### ~ tutorialhint 
Щоб скинути предмети з панелі швидкого доступу, натисніть клавішу [**Q**] на клавіатурі. 

## Крок 2
Дайте **другому** собаці все, що вже є у списку, з додатковими вітамінами. 
Зробіть це, використовуючи метод **append**, щоб додати змінну **Vitamins** в кінець списку.
Потім змініть значення останньої команди `||blocks: place block at position||`, щоб вона розмістила вітаміни в машині, і 
потім дайте їжу собаці номер два.

## Крок 3
Дайте **третьому** собаці все, що вже є у списку, але без **beef**. 
Зробіть це, використовуючи метод **pop**, щоб видалити змінну **Beef** зі списку.
Потім дайте їжу собаці номер три.

### ~ tutorialhint 
З методом **pop** ви повинні використовувати значення позиції у списку, а **не** його назву. 

```template
Bone = world(-21, 45, -31)
Beef = world(-21, 45, -29)
Chicken = world(-21, 45, -27)
Biscuit = world(-21, 45, -25)
Vitamins = world(-21, 45, -23)
// Replace the lines below with your code #   
Dog_Food=[Bone, Beef, Chicken, Biscuit]
//Add the variable Vitamins to the list using the append method | Step 2
//Remove the variable Beef using the pop method                          | Step 3

blocks.place(REDSTONE_BLOCK, Dog_Food[0]) 
//Change the numerical value of the list below         | Step 1
blocks.place(REDSTONE_BLOCK, Dog_Food[0])
//Change the numerical value of the list below         | Step 1
blocks.place(REDSTONE_BLOCK, Dog_Food[0]) 
//Change the numerical value of the list below         | Step 1
blocks.place(REDSTONE_BLOCK, Dog_Food[0])   
//Change the numerical value of the list below                  | Step 2
blocks.place(REDSTONE_BLOCK, Dog_Food[0]) 
```
