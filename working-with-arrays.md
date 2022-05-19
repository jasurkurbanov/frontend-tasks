# Working With Arrays

Array indexes explained 
https://docs.google.com/presentation/d/1IR3WSeXJUKQqN7oB3K6YUvc1G8dSGH7msmtAwFWcm7E/edit#slide=id.g11bfd0e2ed5_0_1

### Creating arrays
```js
//array of numbers
const favoriteNumbers = [53, 23, 34, 63];
```

```js
//array of strings
const friendsName = ['Bobur', 'Amir', 'Ravshan', 'Bekzod'];
```

### Built-in array methods(.length)
1.Length of an array
```js
const friendsName = ['Bobur', 'Amir', 'Ravshan', 'Bekzod'];
console.log(friendsName.length);  // 4
```

### Accessing arrays

```js
const friendsName = ['Bobur', 'Amir', 'Ravshan', 'Bekzod'];
console.log("Hello", friendsName[1])
// Hello Amir
```

```js
//find last value from this array
const friendsName = [21,42,35,43,55,67,37,28,19,17];
console.log(friendsName[friendsName.length-1])
// 17
```


```js
//access to 28 from this array
const friendsName = [21,42,35,43,55,67,37,28,19,17];
console.log(friendsName[friendsName.length-2])
// 28
```

```js
//find middle value from this array
const friendsName = [21,42,35,43,55,67,37,28,19,10];
console.log(friendsName[friendsName.length/2])
// 67
```

#### Nested arrays
```js
//2x
const friendsName = ['Bobur', ['Amir', 'Damir'] , 'Ravshan', 'Bekzod'];
console.log("Hello", friendsName[1][1])
// Hello Damir
```

```js
//3x
const friendsName = ['Bobur', ['Amir', ['Toir', 'Ilyos']] , 'Ravshan', 'Bekzod'];
console.log("Hello", friendsName[1][1][0])
// Hello Toir
```

```js
//6x
const friendsInfo = ['Bobur', ['Amir', [[15, [43, 53, 219, [5243, 'Yalta']]], 'Ilyos']] , 'Ravshan', 'Bekzod'];
console.log("Hello", friendsInfo[1][1][0][1][3][1])
// Hello Yalta
```

### Modifying array 
```js
//array of strings
const friendsName = ['Bobur', 'Amir', 'Ravshan', 'Bekzod'];
friendsName[3] = "Jasur"
console.log(friendsName)
// ['Bobur', 'Amir', 'Ravshan', 'Jasur'];
```

### Adding value to arrray 
- push()
```js
const friends = ['Amir', 'Ravshan'];
friends.push('Eldor');
console.log(friends);
// ['Amir', 'Ravshan', 'Eldor'];
```

- unshift()
```js
const friends = ['Amir', 'Ravshan'];
friends.unshift('Eldor');
console.log(friends);
// ['Eldor', 'Amir', 'Ravshan';
```



