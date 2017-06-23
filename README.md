# What are the differences between null and undefined?


### Undefined

```javascript
 var TestVar;
 alert(TestVar); //shows undefined
 alert(typeof TestVar); //shows undefined
```

### null

null is a special keyword that indicates an absence of value.

* "suresh" is string,
* true is boolean ,
* 1234 is number,
* null is undefined.

```null``` doesn't represent a string that has no value - empty string-

<b>Like</b>

```javascript
var a = ''; 
console.log(typeof a); // string 
console.log(a == null); //false 
console.log(a == undefined); // false 
```

<b>Now if</b>

```javascript
var a;
console.log(a == null); //true
console.log(a == undefined); //true 
```

<b>But</b>

```javascript
var a; 
console.log(a === null); //false 
console.log(a === undefined); // true
```

```undefined``` use it to compare the variable data type

```null``` use it to empty a value of a variable
