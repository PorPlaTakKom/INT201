# Basic JavaScript

## What is JavaScript ?

JavaScript is high-level programming language often used to implement dynamic features on web pages.

**Why to learn JavaScript ?**

![](https://s3-torquehhvm-wpengine.netdna-ssl.com/uploads/2022/02/stackoverflow-developer-survey-2021-most-popular-technologies-1024x395.png)

**What to use JavaScript for ?**

* Web (frontend , backend)
* Mobile Application
* Application

**Applications that use JavaScript**

* Facebook
* Instagram
* Netflix
* Uber
* Microsoft Team
* etc.

## Variables

Variables are used to store data values in computer memory. They can be referred by using their names.

**Variables for JavaScript**

* <mark style="color:red;">var (not recommended to use)</mark>
* <mark style="color:blue;">let</mark>
* <mark style="color:blue;">const</mark>

**How to use**

{% hint style="danger" %}
Name for variable can't start with number and can't use special character.
{% endhint %}

```javascript
// myName and MyAge is name for variable 
let myName = 'Alice'
// const can't edit value in variable
const myAge = 20

console.log(myName)
console.log(myAge)

myName = 'Bolb'
myAge = 18

//Result
Alice
20
Blob
Error
```
