## Maksim Tyshkevich

### Info:

- **City** : Minsk, Belarus.
- **Phone number** : +375(25) 656 88 52
- **Email** : [2842778@gmail.com](http://2842778@gmail.com)
- **Discord** : MaxPayne#9870
- **Git** : <https://github.com/MaxTyshkevich>

### Skills:

- **Web technology** : - HTML. - CSS. - SCSS.
- **Programming language** : - JavaScript. - TypeScript.  - PHP(basic).  - Node JS(basic).
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
**2021q1**  Java Script/Front-end Score Points: 520.9 Completed Tasks:23/39
**2021q1**  Java Script/Pre-School Score Points: 282.9 Completed Tasks:18/27
**2021q1**  Java Script/Front-end Score Points: 520.9 Completed Tasks:23/39
**2021q3**  Java Script/Front-end 2021q3 Score Points: 2,133.7 Completed Tasks:49/62
**2021q3**  React / Front-end 2022q1 Score Points: 190 Completed Tasks:9/10
 **2022**   React / Front-end 2022q1 Score Points: 190 Completed Tasks:9/10
 **2022**   PHP Bacis
 **2022**   React с нуля для начинающих (Михаил Непомнящий)
 **2022**   На данный момент изучаю Node JS



Solving algorithms [Profile codewars](https://www.codewars.com/users/Max%20Tyshkevich)

### English:

Basic User.

Upgrade skills in applications. **Duolingo** and **Polyglot**
