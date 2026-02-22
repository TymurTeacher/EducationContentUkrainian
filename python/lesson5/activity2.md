### @explicitHints true
# Завдання 2 - Цикл прання.

```python
for i in range(2):
pass
agent.collect_all()
agent.move(FORWARD, 5)
agent.drop_all(FORWARD)
agent.turn(LEFT)

```

## Крок 1
**Частина 1:** Напишіть код, щоб Агент підняв брудну білизну, перемістився **вперед** у машину, повернув ліворуч **20** разів, а потім вийшов з машини та поклав чисту білизну з іншого боку від того місця, де лежала брудна.

## Крок 2
**Частина 2:** Відредагуйте той самий код, щоб Агент зробив те саме, але для **3** завантажень білизни. Зробіть це, використовуючи цикл `||loops: for||` перед усім іншим кодом.

### ~ tutorialhint 
Не забувайте, що в цьому випадку два цикли не повинні мати однакову назву змінної, тому перейменуйте другий цикл.
Щоб зробити відступ для великого фрагменту коду, виділіть увесь код, який потрібно відступити, і натисніть клавішу **Tab**.

```template
//Replace the lines below with your code #    
//loop number 2 set to 3                              | Part 2
agent.collect_all()
agent.move(FORWARD, 7)
agent.drop_all(FORWARD)
//loop number 1                              | Part 1
//make the Agent turn left 20 times          | Part 1 
//end of loop 1
//make the Agent collect all                 | Part 1          
//make the Agent move back                   | Part 1
//make the Agent drop everything to the left | Part 1
//end of loop 2
```
