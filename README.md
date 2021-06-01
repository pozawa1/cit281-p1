# Objectives
1. Gain experience accessing your operating system's command line interface (CLI)
2. Gain experience working with CLI commands
3. Gain experience working with Visual Studio Code (VSCode)
4. Gain experience writing and executing non-web server Node.js JavaScript code

# Technologies Used
- Terminal
- VSCode

# Part 1
Complete [Lab 1](https://pozawa1.github.io/cit281-lab1/)

# Part 2
Use command line commands to create a folder structure. 

![p1-folders](https://user-images.githubusercontent.com/83732149/120233199-199b4600-c20a-11eb-8cdb-e12416d18eb5.png)

# Part 3
Use the ping utility to learn how to break out of a command line operation that appears to be non-functional.

![p1-break](https://user-images.githubusercontent.com/83732149/120233317-62eb9580-c20a-11eb-9f6a-052e535a0fc8.png)

Ping a domain that will respond.

![p1-ping](https://user-images.githubusercontent.com/83732149/120233293-55361000-c20a-11eb-87da-a3b482d40e8f.png)

# Part 4
Create a JavaScript program that outputs to the console the day of the week of the current day.
```
function getDay() {
let daysOfWeek = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"]
let date = new Date();
let weekday = date.getDay();
return (daysOfWeek[weekday]);
}
console.log(getDay());
```

# Part 5
Create a Javascript Program that outputs to the console a string of random length between 5 - 25 characters (range inclusive) in length, that consists of all random lowercase letters from the English alphabet.
```
function randomString() {
    let result = "";
    let alphabet = 'abcdefghijklmnopqrstuvwxyz';

    function getRandomInteger() {
        let min = 5;
        let max = 25;
        return randomInt = Math.floor(Math.random() * (max - min) + min);
    }    

    for ( let i = 0; i < getRandomInteger(); i++ ) {
        result += alphabet.charAt(randomInt);
    }

    return result;
}
```

[Source Code](https://github.com/pozawa1/cit281-p1/blob/main/source-code-p1)

[Return to Homepage](https://pozawa1.github.io/)
