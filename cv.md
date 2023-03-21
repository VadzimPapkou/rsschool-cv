# Vadim Popkov
_Frontend Software developer, Belarus_ <br>
_English level - **B1**_

[Email](mailto:playvarian@gmail.com) / [LinkedIn](https://www.linkedin.com/in/vadim-popkov-8a6749207/) / [GitHub](https://github.com/VadzimPapkou)

## 🖥️ My stack

* **JavaScript**, **TypeScript**
* **Git**, **DevTools** 
* **Webstorm**, VSCode
* **React**, Angular
* **Mobx**, **Redux**
* **Nodejs**, **Mongodb**, PostgreSQL
* **Ubuntu**, **Windows**

## 👨🏻‍💻 Technical Experience

**Frontend Developer** @ [YumaSoft](https://www.yumasoft.com/) _(June 2022 - December 2022)_<br>
Outsource company

* Worked on FrontEnd part of Shop management software
* Mostly worked on old backbone code and new react code
* Sometimes worked on ruby on rails code

## 📌 Open Source

**Projects**

- [VK attachment photos](https://github.com/TrueShadowGuard/vk_attachment_photos) -
   Program for downloading all nested photos of vk message

- [Presentation downloader](https://github.com/TrueShadowGuard/moodle_download_presentation) -
  Script for downloading presentations from my university moodle system


- [Accelerator](https://github.com/TrueShadowGuard/accelerator-front) -
  Frontend of web application for processing protein structures

## 🧑‍💻 Code examples

### [Does my number look big in this?](https://www.codewars.com/kata/5287e858c6b5a9678200083c)

* A Narcissistic Number (or Armstrong Number) is a positive number which is the sum of its own digits, each raised to the power of the number of digits in a given base. In this Kata, we will restrict ourselves to decimal (base 10).
* For example, take 153 (3 digits), which is narcissistic:

  ```1^3 + 5^3 + 3^3 = 1 + 125 + 27 = 153```
* The Challenge: <br>Your code must return true or false (not 'true' and 'false') depending upon whether the given number is a Narcissistic number in base 10.

#### My solution:
```
export function narcissistic(value: number): boolean {
    const digits = String(value).split("").map(Number);
    const sum = digits.reduce((a,b) => a + b ** digits.length, 0);
    return sum === value;
}
```

## 👨🏻‍🎓 Education

**Pharmacist**

Belarusian State medical university(2020 - 2025)