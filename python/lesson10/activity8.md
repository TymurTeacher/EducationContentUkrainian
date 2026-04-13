### @explicitHints true
### @hideIteration true
# Алмазний ривок.

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
Видали лапки (**'**) з початку та кінця кожного рядка.
Доповни код так, щоб Агент рухався до золотого блоку та рахував кожен блок діаманту, який він проходить.
Наприкінці, коли Агент досягне золотого блоку, він повинен розмістити кількість блоків діаманту, що він порахував, перед собою, один за одним. Ці блоки будуть автоматично складатися поршнем.
```template
'diamond = 0'
'for index in range(11):'
'    agent.move(FORWARD, 1)'
'for index2 in range(diamond):'
'    agent.place(FORWARD)'
'    loops.pause(500)'
```
