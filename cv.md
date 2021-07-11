1. **Stankevich Vitaly**
2. **Contact Info:**
    - Email: stankevichvitaly@gmail.com
    - Skype: stankevichvitaly
3. **Summary:**
My goal is to become a professional web developer. I am a purposeful and highly motivated person, who is always ready to study and constantly improve skills and knowledge.
4. **Skills:**
    * HTML5;
    * CSS3;
    * JavaScript(ES5 and ES6(in the process of studying));
    * Git (basics);
    * Soft: Visual Studio Code.
5. **Example of my code:**
    ```javascript
   function makeExchange(amount) {
    var money = {
      H: 50,
      Q: 25,
      D: 10,
      N: 5,
      P: 1
    };
    for (var key in money) {
      if (amount >= money[key]) {
        var a = amount % money[key];
        money[key] = Math.floor(amount / money[key]);
        amount = a;
      } else {
        delete money[key];
      }
    }
    return money;
    }
    ```