## [rsschool-cv](https://github.com/daniilalex/rsschool-cv)
___  
## Daniil Aleksejev
***
### Contacts:
* **CodePen:** @twofaceddan
* **Discord:** danalex#9159
* **LinkedIn:** [Dan Alex](https://www.linkedin.com/in/daniil-alex-5324bb64/)
* **GitHub:** [Dan Alex](https://github.com/daniilalex)
* **E-mail:** Daniil.alex1@gmail.com
* **Tel:** +37061115999 
* **Country:** Lithuania
* **City:** Vilnius

## About Me
*** 
I'd been working in the transport & logistic area, by transport top-manager since 2012. But now, I've decided to retrain as a programmer. I'm studying at CodeAcademy in Vilnius, watching courses from the udemy portal. I have read a few JS books and I'm going to study at RC school at the frontend developer. In my free time, I like to do a sport. Winter is snowboarding and sports gym. Summer is cycling, swimming, rest in the nature with family.

## My Code
---
``` JavaScript
function toCamelCase(str) {
    let newStr = '';//This is the variable the function will return as it will contain our transformed string to capture every dash and underscore in the string.
    if (str) {
        let wordArr = str.split(/[-_]/g);//We use the regular expression /[-_]/g as the argument for the split() method
        for (let i in wordArr) {//Next, we will loop through our wordArr array and capitalize all the words in the string except the first word. 
            if (i > 0) {
                newStr += wordArr[i].charAt(0).toUpperCase() + wordArr[i].slice(1);//all letters convert to the big instead of the first letter and + word without first letter
            } else {
                newStr += wordArr[i];
            }
        }
    } else {
        return newStr;//after looping return newStr value
    }
    return newStr;//return an empty string or newStr
}
console.log(toCamelCase("the_stealth_warrior"));
```
