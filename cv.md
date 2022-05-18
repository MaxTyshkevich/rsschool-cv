## Maksim Tyshkevich

### Info:

- **City** : Minsk, Belarus.
- **Phone number** : +375(25) 656 88 52
- **Email** : [2842778@gmail.com](http://2842778@gmail.com)
- **Discord** : MaxPayne#9870
- **Git** : <https://github.com/MaxTyshkevich>

### Skills:

- **Web technology** : - HTML. - CSS. - SCSS.
- **Programming language** : - JavaScript. - TypeScript.
- **Library** : React . (React Redux Toolkit, React Routing v6)
- **Version control system** : - Git.

### Code examples:

**Task :** [I Promise Not To Optimize](https://www.codewars.com/kata/58d014421c694f71630000bc)

```
function antiOptimizeAsync(task) {
  console.log("task",task);
  let start = Date.now();
  return Promise.resolve(task()).then(res => new Promise(resolve => {
    setTimeout(()=> resolve(res), 11300 - (Date.now() - start))
  }) )
}
```

**Task :** [Function Composition](https://www.codewars.com/kata/5421c6a2dda52688f6000af8)

```
function compose(...func) {
  return (...args) => {
    return func.reduceRight((result,fn) => {
      result = fn(...result)
      return [result];
    },args);
  }
}
```

### Education:

Secondary special, profession: **mechatronics**.
Solving algorithms [Profile codewars](https://www.codewars.com/users/Max%20Tyshkevich)

### English:

Basic User.

Upgrade skills in applications. **Duolingo** and **Polyglot**
