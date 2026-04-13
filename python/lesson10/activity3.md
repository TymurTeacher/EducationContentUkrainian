### @explicitHints true
### @hideIteration true

# Діамант чи бруд?

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
Напиши код для обчислення відповідей до цих чотирьох виразів. Тобі потрібно довести Агента до золотого блоку — зроби це, розміщуючи блок діаманту або блок бруду зі скрині залежно від відповіді виразу. Зліва направо: якщо відповідь дорівнює 1 — розміщуй блок діаманту, якщо 0 — блок бруду.
```python
1. 10000 / 10000 + 64.64 + 64.64 - 72 - 57.28
2. 64 / 4 + 64 / 64 - 128 / 8 - 1
3. 19283746 / 19283746 - 1 + 1000 / 100 - 9
4. 8 - 9 + 7 + 32 * 2 - 64 / 2 - 38
```
```template
//Обчисли вираз: 10000 / 10000 + 64.64 + 64.64 - 72 - 57.28
//
//Обчисли вираз: 64 / 4 + 64 / 64 - 128 / 8 - 1
//
//Обчисли вираз: 19283746 / 19283746 - 1 + 1000 / 100 - 9
//
//Обчисли вираз: 8 - 9 + 7 + 32 * 2 - 64 / 2 - 38
```

