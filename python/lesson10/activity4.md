### @explicitHints true
### @hideIteration true

# Прихід весни

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
for index in range(10):
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
У вікні кодування тобі надано код, який не працює. Видали лапки (**'**) з початку та кінця кожного рядка.
Цей код повинен садити квіти на кожен блок трави, переміщуючи Агента через зону ряд за рядом.
Чи можеш ти завершити код, додавши умовну конструкцію та налагодивши головний цикл?
```template
'for index in range(4):'
'   for index2 in range(8):'
'        if agent.inspect(AgentInspection.BLOCK, DOWN) == GRASS:'
'            agent.place(DOWN)'
'        agent.move(FORWARD, 1)'
'   agent.turn(RIGHT_TURN)'
'   agent.move(FORWARD, 1)'
'   agent.turn(RIGHT_TURN)'
'   for index3 in range(8):'
'       if True:'
'           agent.place(DOWN)'
'       agent.move(FORWARD, 1)'
'   agent.turn(LEFT_TURN)'
'   agent.move(FORWARD, 1)'
'   agent.turn(LEFT_TURN)'
```

