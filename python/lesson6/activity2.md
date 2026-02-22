### @explicitHints true
 
# Завдання 2 - Ліворуч чи праворуч?

```python
agent.inspect(AgentInspection.BLOCK, FORWARD)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 5)
for i in range(2):
      pass
if True:
      pass
```

## Крок 1
**Частина 1:** Напишіть код, використовуючи умову `||logic:if else||`, щоб Агент повертав ліворуч, коли досягає знаку, і
потім рухався вперед на золотий блок. Використовуйте команду `||agent:agent inspect||` як умову та порівняйте її зі змінною **left**.
Команда `||agent:agent inspect||` виглядає так:
```python
agent.inspect(AgentInspection.BLOCK, FORWARD)
```
Використовуйте змінні, вже надані у вашому коді: left = BLUE_GLAZED_TERRACOTTA, right = PINK_GLAZED_TERRACOTTA
### ~ tutorialhint 
Щоб перевірити, чи рівні два значення, використовуйте **==**.

## Крок 2
**Частина 2:** Відредагуйте код так, щоб Агент повертав в обидва боки, поки не досягне золотого блоку. Зробіть це, додавши умову **elif**
між частинами **if** та **else**.
### ~ tutorialhint 
Використовуйте умову **elif** з командою `||agent:agent inspect||`
як умову та порівняйте її зі змінною **right**.

```template
left = BLUE_GLAZED_TERRACOTTA
right = PINK_GLAZED_TERRACOTTA
//Replace the lines below with your code #
//Change value of loop below from 9 to 21                     |Part 2
//for loop set to 9                                   |Part 1
//if else conditional with an Agent inspect condition |Part 1
agent.turn(LEFT_TURN)
//elif conditional with an Agent inspect condition            |Part 2
//Make the agent turn right                                   |Part 2
//else part of the if else conditional                |Part 1
//Make the agent move forward                         |Part 1
//End of loop                                         |Part 1
```
