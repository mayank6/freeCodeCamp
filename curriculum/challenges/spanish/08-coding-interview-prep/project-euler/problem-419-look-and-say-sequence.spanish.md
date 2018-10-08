---
id: 5
localeTitle: 5900f5101000cf542c510022
challengeType: 5
title: 'Problem 419: Look and say sequence'
---

## Description
<section id='description'> 
La secuencia de buscar y decir va 1, 11, 21, 1211, 111221, 312211, 13112221, 1113213211, ... 
La secuencia comienza con 1 y todos los demás miembros se obtienen describiendo el miembro anterior en términos de dígitos consecutivos. 
Ayuda hacer esto en voz alta: 
1 es &#39;uno uno&#39; → 11 
11 es &#39;dos ​​unos&#39; → 21 
21 es &#39;uno dos y uno uno&#39; → 1211 
1211 es &#39;uno uno, uno dos y dos ones &#39;→ 111221 
111221 es&#39; tres one, two twos and one &#39;→ 312211 
... 


Defina A (n), B (n) y C (n) como el número de unidades, twos y threes en el elemento n &#39;n de la secuencia respectivamente. 
Se puede verificar que A (40) = 31254, B (40) = 20259 y C (40) = 11625. 


Encuentre A (n), B (n) y C (n) para n = 1012. 
Da tu respuesta módulo 230 y separa tus valores para A, B y C con una coma. 
Ej. Para n = 40 la respuesta sería 31254,20259,11625 
</section>

## Instructions
<section id='instructions'> 

</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: &#39; <code>euler419()</code> debe devolver 998567458, 1046245404, 43363922.&#39;
    testString: 'assert.strictEqual(euler419(), 998567458, 1046245404, 43363922, "<code>euler419()</code> should return 998567458, 1046245404, 43363922.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler419() {
  // Good luck!
  return true;
}

euler419();
```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>