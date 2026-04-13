### @explicitHints true
### @hideIteration true
# Лабіринт Агента.

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
Проведи Агента через лабіринт. Напиши код, щоб використовувати кольорові блоки як напрямки керування — вперед, ліворуч і праворуч — для руху Агента.
Потім керуй Агентом до виходу з лабіринту, стоячи на кольорових блоках.

### ~ tutorialhint
Спробуй використати нескінченний цикл while.
