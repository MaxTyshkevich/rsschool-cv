## Maksim Tyshkevich

### Contact Info:

- **City** : Minsk, Belarus.
- **Phone number** : +375(25) 656 88 52
- **Email** : 2842778@gmail.com [2842778@gmail.com](http://2842778@gmail.com)
- **Discord** : MaxPayne#9870

### Summary

My goal is to get skills by taking courses from _ rs.school _.

### Skills:

- **Web technology** : - HTML. - CSS. - SCSS.
- **Programming language** : - JavaScript.
- **Version control system** : - Git.

### Code examples:

Web site: [Learn Javascript, subject "focus/blur"](https://learn.javascript.ru/focus-blur)

```javascript
let div = document.querySelector(".block");
       div.tabIndex = 0;
       div.onfocus = function(e) {
           let textarea = document.createElement("textarea");
           textarea.innerHTML = div.innerHTML;
           textarea.classList.add(`edit`);

           this.replaceWith(textarea);
           textarea.focus();

           textarea.onkeydown = function(e) {
               if (e.code == "Enter") textarea.blur();
           }
           textarea.onblur = function(e) {
               let value = textarea.value;
               div.innerHTML = value;
               textarea.replaceWith(div);
               textarea.onblur = null;
           }

       }
}
```

### Education:

Secondary special, profession: **mechatronics**.
Solving algorithms [Profile codewars](https://www.codewars.com/users/Max%20Tyshkevich)

### English:

Basic User.
