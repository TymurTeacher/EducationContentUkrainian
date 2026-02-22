### @explicitHints true

# Завдання 1 - Стій і йди.

```python
loops.pause(2000)
agent.move(FORWARD, 5)
for i in range(2):
      pass
if True:
      pass
agent.detect(AgentDetection.BLOCK, FORWARD)
```

## Крок 1
**Частина 1:** Напишіть код, щоб Агент рухався лише тоді, коли **є** блок з його лівого боку.
Використовуйте команду `||agent: agent detect||` як умову:
```python
agent.detect(AgentDetection.BLOCK, LEFT)
```

## Крок 2
**Частина 2:** Відредагуйте код так, щоб Агент рухався, коли блоку зліва **немає**.
Зробіть це, додавши оператор **not** перед умовою.

## Крок 3
**Частина 3:** Змусьте Агента рухатись знову після команди `||loops:pause||`, щоб досягти останнього золотого блоку.

### ~ tutorialhint
**1000** мс — це **1** секунда.

```template
//Replace the lines below with your code #    
//for loop set to 7                            |Part 1
//Add the operator NOT to the condition below          |Part 2 
//if conditional with an Agent detect condition|Part 1
//Make the Agent move forward                  |Part 1
//if conditional with an Agent detect condition                |Part 3
loops.pause(2000)
//Make the Agent move forward                                  |Part 3
//End of loop
```
