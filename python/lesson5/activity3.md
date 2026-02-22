### @explicitHints true
# Завдання 3 - Прибирання.

```python
for i in range(2):
pass
agent.collect_all()
agent.move(FORWARD, 5)
agent.drop_all(FORWARD)
```

## Крок 1
**Частина 1:** Напишіть код, щоб Агент пройшов над кожним блоком маленького килиму та підібрав бруд.
### ~ tutorialhint 
Не забувайте, що в цьому випадку два цикли не повинні мати однакову назву змінної.

## Крок 2
**Частина 2:** Відредагуйте той самий код, щоб Агент зробив те саме, але для більшого килиму. Зробіть це, повторивши код **3** рази за допомогою циклу `||loops:for||`. Наприкінці спробуйте змусити Агента скинути весь бруд у смітник праворуч від нього.
### ~ tutorialhint 
Пам'ятайте, що вам потрібно буде використовувати подвійний відступ у своєму коді.

```template
//Replace the lines below with your code #    
//loop number 3                                 | Part 2
//loop number 1                        | Part 1
agent.collect_all()
agent.move(FORWARD, 1)
//end of loop 1
agent.move(RIGHT, 1)
//loop number 2                        | Part 1
//make the Agent collect all           | Part 1  
//make the Agent move back             | Part 1  
//end of loop 2
//make the Agent move right                     | Part 2
//end of loop 3  
//make the Agent drop all to the right          | Part 2  
```
