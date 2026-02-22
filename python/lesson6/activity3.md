### @explicitHints true
### @hideIteration true 
# Завдання 3 - Пройти крізь.

```python
agent.detect(AgentDetection.BLOCK, FORWARD) 
agent.turn(LEFT_TURN)
agent.move(FORWARD, 5)
for i in range(2):
      pass
if True:
      pass
```

## Крок 1
Напишіть код, щоб Агент виявляв і оминав випадково розміщені блоки під час проходження через трасу. Для цього використовуйте умову
`||logic:if else||` з умовою **elif** посередині. Для умови **if** використовуйте дві команди `||agent:agent detect||`
з оператором **and not** між ними. Для умови **elif** використовуйте дві команди `||agent:agent detect||`
з оператором **and** між ними. Приклад двох умов з оператором **and not**:
```python
agent.detect(AgentDetection.BLOCK, DIRECTION) and not agent.detect(AgentDetection.BLOCK, DIRECTION)
```

### ~ tutorialhint 
Коли використовується більше однієї умови разом, можна використовувати **and** або **and not** для перевірки кількох станів.

```template
//Replace the lines below with your code #    
//for loop set to 23                                            
//if else conditional with two Agent detect commands, seperated by an and not operator
agent.move(LEFT, 1)                              
//elif conditional with two Agent detect commands, seperated by an and operator
agent.move(RIGHT, 2)
//else part of the else if conditional             
agent.move(FORWARD, 1)                                   
//End of loop                                       
```
