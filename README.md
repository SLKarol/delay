# delay

Возникают ситуации, когда для скриптов на node.js необходимо поставить задержку на некоторое время, например перед отправкой сообщений в телеграм или запросов к ресурсу. Для этих целей сделана функция delay - она создаёт промис с задержкой.

## Install

npm install @stanislavkarol/delay -S

## Example

```js
const delay = require("@stanislavkarol/delay");

console.log("a");
delay().then(() => console.log("b"));
console.log("c");
```
