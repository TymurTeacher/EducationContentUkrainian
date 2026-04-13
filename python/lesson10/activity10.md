### @explicitHints true
### @hideIteration true

# Чи потрібно мені це перелічити?

```python
agent.move(FORWARD, 5)
pos(0, 0, 0)
player.say("Finished")
agent.place(LEFT)
agent.inspect(AgentInspection.BLOCK, DOWN)
agent.turn(RIGHT_TURN)
agent.destroy(BACK)
agent.drop_all(FORWARD)
agent.collect_all()
loops.pause(500)
for i in range(10):
    pass
if True:
    pass
else:
    pass
elif:
    pass
while True:
    pass
```

## Крок 1
Тобі надано список. Видали лапки (**'**) з початку та кінця кожного рядка. Щоб дізнатися, на якому типі блоку повинен стояти Агент, **відсортуй** список за алфавітом і візьми **другий** блок зі списку. Стань на правильний тип блоку та натисни кнопку, щоб телепортувати Агента туди.
Щоб дізнатися, на якому типі блоку повинен стояти твій гравець, **розгорни** список і **видали** **четвертий** блок зі списку.
Візьми **шостий** блок зі списку і стань на цей блок.

```template
'block_list = ["DIAMOND", "ICE", "EMERALD", "STONE", "WOOD", "GOLD", "QUARTZ"]'
```
