### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @hideIteration true 
### @flyoutOnly 1
### @explicitHints 1


# Запрограмуйте Агента, щоб він рухався вгору до золотої платформи!

## Крок 1
Запрограмуйте Агента, щоб він дістався до золотої платформи. Ви повинні залишатися на своїй золотій платформі, а Агент повинен залишатися на іншій. Коли закінчите, натисніть кнопку **Play**, щоб скомпілювати код. Перейдіть до Minecraft і запустіть ваш код.


```ghost
player.onChat("last", function () {
    agent.move(FORWARD, 1)
    agent.turn(LEFT_TURN)
})
```  
