# Переменные

## Типы данных
- **String**

- **Number**

- **BigInt** В конце дописывается n.    1234567890123456789012345678901234567890**n** 

- **Boolean** 

- **Null**

- **Undefined**

- **Object**

- **Symbol** для уникальных идентификаторов



## Отличия VAR и LET
- let, в отличии от var, не создает свойства на глобальном объекте window

```javascript
let a = 10;
var b = 10;
console.log(window.a); // undefined
console.log(window.b); // 10
```

- При обращении к let до объявления будет ошибка в консоли
```javascript
console.log(a); //undefined
console.log(b); //error
var a;
let b;
```
