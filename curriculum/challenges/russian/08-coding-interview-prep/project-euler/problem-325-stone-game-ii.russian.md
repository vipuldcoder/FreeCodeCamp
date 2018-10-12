---
id: 5900f4b11000cf542c50ffc4
challengeType: 5
title: 'Problem 325: Stone Game II'
videoUrl: ''
localeTitle: 'Задача 325: Каменная игра II'
---

## Description
<section id="description"> В игру играют две груды камней и два игрока. В свою очередь игрок удаляет несколько камней из большей кучи. Количество камней, которые она удаляет, должно быть положительным, кратным количеству камней в меньшей куче. <p> Например, пусть упорядоченная пара (6,14) описывает конфигурацию с 6 камнями в меньшей куче и 14 камней в большей куче, тогда первый игрок может удалить 6 или 12 камней из большей кучи. </p><p> Игрок, берущий все камни из кучи, выигрывает игру. </p><p> Победившая конфигурация - это та, где первый игрок может заставить выиграть. Например, (1,5), (2,6) и (3,12) являются выигрышными конфигурациями, потому что первый игрок может сразу удалить все камни во второй куче. </p><p> Потерянная конфигурация - это та, где второй игрок может заставить победу, независимо от того, что делает первый игрок. Например, (2,3) и (3,4) теряют конфигурации: любой законный ход оставляет выигрышную конфигурацию для второго игрока. </p><p> Определим S (N) как сумму (xi + yi) для всех убывающих конфигураций (xi, yi), 0 &lt;xi &lt;yi ≤ N. Мы можем проверить, что S (10) = 211 и S (104) = 230312207313. </p><p> Найдите S (1016) mod 710. </p></section>

## Instructions
undefined

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>euler325()</code> должен вернуть 54672965.
    testString: 'assert.strictEqual(euler325(), 54672965, "<code>euler325()</code> should return 54672965.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler325() {
  // Good luck!
  return true;
}

euler325();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>