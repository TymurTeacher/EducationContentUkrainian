### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @hideIteration true 
### @flyoutOnly 1
### @explicitHints 1


# Запрограмуйте Агента, щоб він рухався вгору до золотої платформи!

## Крок 1
Використовуйте команди ``||player:при команді чату||`` та ``||agent:агент - переміститися||``, щоб запрограмувати Агента рухатися до золотої платформи. Ви можете запрограмувати Агента, щоб він рухався **вгору**. Коли закінчите, натисніть кнопку **Play**, щоб скомпілювати код. Перейдіть до Minecraft і запустіть ваш код у грі.



```ghost
player.onChat("up", function () {
    agent.move(FORWARD, 1)
    agent.turn(LEFT_TURN)
})

```  
