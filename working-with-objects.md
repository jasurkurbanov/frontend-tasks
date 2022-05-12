# Working With Objects
## Tutorial

```js
const data = {
    "id": 1,
    "first_name": "Fletcher",
    "last_name": "Brownlie",
    "email": "fbrownlie0@nationalgeographic.com",
    "gender": "Agender",
    "friendInfo": {
      "id": 39,
      "first_name": "Robina",
      "last_name": "Leadstone",
      "email": "rleadstone12@bigcartel.com",
      "gender": "Female",
      "ip_address": "59.127.253.209"
    },
    "ip_address": "212.182.198.124"
  };
```

###  Different ways of accessing object values 
    - dot notation
    - bracket notation
    - destructoring

## Self Study

### Sample Data
```js
const userInfo = {
      id: 29,
      phoneNumber: "998 99 998 99 20"
  } 

let husbandInfo = userInfo

const neighborInfo =  {
    "id": 44,
    "first_name": "Tuckie",
    "last_name": "Costy",
    "email": "tcosty17@admin.ch",
    "gender": "Bigender",
    "ip_address": "80.108.160.178",
    "grandMotherInfo": {
        "id": 41,
        "first_name": "Jerad",
        "last_name": "Hadlington",
        "email": "jhadlington14@netvibes.com",
        "gender": "Male",
        "ip_address": "170.160.137.203",
        "husbandInfo": { phoneNumber: "998 99 998 99 21", husbandInfo}
      }
  }


const testData = {
        "id": 50,
        "first_name": "Molly",
        "last_name": "Pantling",
        "email": "mpantling1d@skype.com",
        "gender": "Female",
        "ip_address": "145.188.2.41",
        "friendInfo":  {
            "id": 48,
            "first_name": "Bianca",
            "last_name": "Cuffin",
            "email": "bcuffin1b@hexun.com",
            "gender": "Female",
            "ip_address": "7.51.67.94",
            "neighborInfo": neighborInfo
          }
  }
```



### Tasks

Before starting tasks, make sure that you should access to whatever information starting from `testData`. If you should show neighbor name. You should not access to it `neighborInfo.name`. But instead do it like this `testData.friendInfo.neighborInfo.name`.

1) 
```js
function printName(){
   // TODO: print Molly
}
```

2)
```js
function printGender(){
   // TODO: print Molly's gender
}
```

3)

```js
function printFriendEmail(){
   // TODO: print Molly's friend email
}
```

4)

```js
function printFriendIpAddress(){
  // TODO: print Biance's IP Adress
}
```

5)

```js
function printNeighborId(){
  // TODO: print Biance's Neighbor Id
}
```

Now based on example above, you should create functions for printing following information

6) Print Biance's neighbor email
7) Print grandmother's husband phone number
8) Print user's phone number
9) Print grandmother's name
10) Print user's ID

Once you finished task, submit it to your Github with repository name `working-with-objects` and send link to me.
