### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @hideIteration true 
### @flyoutOnly 1
### @explicitHints 1


# Запрограмуйте Агента, щоб він рухався до золотої платформи!

## Крок 1
Виберіть команду ``||player:on chat||`` і перейменуйте її з **run** на **1**. Виберіть блок ``||agent: agent move forward||`` і перетягніть його всередину команди ``||player:on chat||``. Змініть **кількість** кроків, на які рухається Агент, на **3**, щоб Агент міг дістатися до золотої платформи. Коли закінчите, натисніть кнопку **Play**, щоб скомпілювати код, потім перейдіть до Minecraft, натисніть **t** і введіть **1**.

#### ~ tutorialhint 
Ви можете змінити кількість кроків, на які буде рухатися ваш Агент, змінивши число всередину блоку ``||agent: agent move||``. Ви також можете використовувати блок ``||agent: agent turn||``, щоб повернути Агента вліво або вправо.



```ghost
player.onChat("1", function () {
    agent.move(FORWARD, 1)
    agent.turn(LEFT_TURN)
})

``` 
