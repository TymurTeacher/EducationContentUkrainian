### @explicitHints true
### @hideIteration true

# Засліплюючі вогні.

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
Змуси Агента розміщувати лампи з червоного каменю зі свого інвентарю на блоки з червоним каменем під час руху вперед по доріжці до золотого блоку.

### ~ tutorialhint
Спробуй використати цикл.

