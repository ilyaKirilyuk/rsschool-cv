# Ilya Kirilyuk
***
## Contacts:

* [Telegram](https://t.me/seriousink "Ссылка на мой Telegram")
* [Instagram](https://www.instagram.com/ilya.kirilyuk/ "Ссылка на мой instagram")
* Discord **seriousink #4909**, rs-school nickname ilya kirilyuk (@ilyaKirilyuk)

***
## About me:

I am 27 years old, I have been developing websites for about two years, I worked as a freelancer for about a year, now I work in a company. I want to become a Fron end developer, I hope thanks to you :)

***

## Skils:

* HTML
* CSS, SCSS
* JavaScript(basic)
* Boodstrap
* БЭМ
* Git, VSCode, PHPShtorm

***

## Code example:

Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.

```JavaScript


function createPhoneNumber(array) {
    let phoneNumberFirst = '';
    let phoneNumberSecond = '';
    let phoneNumberThird = '';
    let fullNumber = '';

    for (let i = 0; i < array.length; i++) {
        const element = array[i];

        if (i < 3) {
            let numberToString = String(element);
            phoneNumberFirst = phoneNumberFirst + numberToString;
        } else if (i > 2 && i < 6) {
            let numberToString = String(element);
            phoneNumberSecond = phoneNumberSecond + numberToString;
        } else {
            let numberToString = String(element);
            phoneNumberThird = phoneNumberThird + numberToString;
        }
    }

    fullNumber = '(' +  phoneNumberFirst + ')' + ' ' +  phoneNumberSecond + '-' + phoneNumberThird;
    
    return fullNumber;
}
```

***

## Work experience:

**HTML-developer**
* Freelance (1 year)
* Outsource (5 months)
* Company (1 year)

 ***

## Courses:

* Self-study
* Skillbox

***

## Languages:

* Russian - Native
* English - Basic