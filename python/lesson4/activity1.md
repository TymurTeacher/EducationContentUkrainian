### @explicitHints true
### @hideIteration true 
# Завдання 1 - Категоризація тварин.

```python
blocks.place()
mobs.spawn()
world(0, 0, 0)
```

## Крок 1
Напишіть код зі списком, названим **My_list**, з тваринами зліва направо у світі Minecraft. 
Розмістіть ще **4** команди `||mobs:spawn mob at position||` після тієї, що вже дана. Використовуйте інформацію з табличок 
на загонах для заповнення цих команд. 

### ~ tutorialhint 
Пам'ятайте, що позиції у списку починаються з нуля. 

```template 
location1 = world(-2, 40, -11)
location2 = world(-2, 40, -5)
location3 = world(-8, 40, -0)
location4 = world(-13, 40, -5)
location5 = world(-13, 40, -11)
//Replace the lines below with your code #   

//list of animals 

mobs.spawn(My_list[0], location1)
//spawn the third mob from the list at location2
//spawn the fifth mob from the list at location3
//spawn the second mob from the list at location4
//spawn the fourth mob from the list at location5
```
