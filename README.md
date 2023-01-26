
# Random Poker Card Generator

An extremely simple Fake API that returns a random playing card with a minimalist design, can be used by discord bots for example

## Request Exemples

### JS
```js
var type = Math.floor(Math.random() * 4);
var card = Math.floor(Math.random() * 13) + 1;
var result = `https://mini-kraken.github.io/random-poker-card/files/${type}/${card}.png`
console.log(result)
```
### python
```py
import random
type = random.randint(0,3)
card = random.randint(1,13)
result = f"https://mini-kraken.github.io/random-poker-card/files/{type}/{card}.png"
print(result)
```
### c#
```c#
using System;

Random rand = new Random();
int type = rand.Next(0, 4);
int card = rand.Next(1, 14);
string result = "https://mini-kraken.github.io/random-poker-card/files/" + type + "/" + card + ".png";
Console.WriteLine(result);
```


## Cards Design Screenshots

![App Screenshot](https://mini-kraken.github.io/random-poker-card/files/1/13.png)

![App Screenshot](https://mini-kraken.github.io/random-poker-card/files/3/12.png)

![App Screenshot](https://mini-kraken.github.io/random-poker-card/files/0/1.png)

