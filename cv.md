Sergey Timashov
----------------

![](assets/img/avatar.jpg)

- e-mail: [sxtimx@gmail.com](mailto:sxtimx@gmial.com)
- telegram: [sergei_timashov](https://t.me/sergei_timashov)
- github: [sxtim](https://github.com/sxtim)
- phone: +7 999 99 99

---

### About Myself

Currently I work as an engineer.  
My goal is to become a Front-End developer.  
I want to gain knowledge and skills that will be enough to work in the company and I want to develop further.

---

### Skills
- JavaScript Basics
- HTML5, CSS3
- Java core
- Git, GitHub
- IntelliJ IDEA, Phpstorm
- Linux User, Gimp
- ---

### Code example:

Your task is to make a function that can take any non-negative integer as an argument and return it with its digits in descending order. Essentially, rearrange the digits to create the highest possible number.

    function descendingOrder(n){
     const arr = n.toString().split('');
     for (let i = 0; i < arr.length; i++) {
        let tmp = 0;
        for (let j = 0; j < arr.length; j++) {
            if (arr[i] > arr[j]){
                tmp = arr[j];
                arr[j] = arr[i];
                arr[i] = tmp;
            }
         }
      }
     return Number(arr.join(''));  
    }

---

### Courses

- HTML, CSS code-basics (complete)
- JavaScript Manual on learnjavascript.ru (in progress)
- RS Schools Course «JavaScript/Front-end. Stage 0» (complete)
- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
- English on learnamericanenglishonline.com (in progress)

---

### Languages:

- Russian (native)
- English (A1)