## Sample Data 
```js
const userData = [
   {
      "_id": "627c9d182a377d5c100f298d",
      "index": 0,
      "guid": "dc63db26-a9a0-461c-9176-3a83d0c11f93",
      "isActive": false,
      "balance": "$2,503.18",
      "picture": "http://placehold.it/32x32",
      "age": 39,
      "eyeColor": "green",
      "name": "Lang Williamson",
      "gender": "male",
      "company": "OTHERWAY",
      "email": "langwilliamson@otherway.com",
      "phone": "+1 (943) 541-3804",
      "address": "865 Adams Street, Crayne, Missouri, 4895",
      "about": "Anim exercitation pariatur pariatur ad Lorem duis reprehenderit excepteur dolore incididunt do et. Esse labore do anim veniam tempor pariatur quis nulla sit dolor nisi aliquip mollit. Voluptate quis Lorem dolor deserunt. Consequat enim nostrud consectetur laboris cillum irure amet deserunt sunt nisi aute ipsum ad. Culpa culpa deserunt ea amet labore consectetur commodo culpa. Aliquip sunt cupidatat veniam laborum velit eu pariatur esse reprehenderit ullamco ad quis dolor excepteur.\r\n",
      "registered": "2022-03-19T03:24:04 -05:00",
      "latitude": -74.042151,
      "longitude": 84.463323,
      "tags": [
         "veniam",
         "ea",
         "aliqua",
         "fugiat",
         "eiusmod",
         "nostrud",
         "mollit"
      ],
      "friends": [
         {
            "id": 0,
            "name": "Berg Mckinney"
         },
         {
            "id": 1,
            "name": "Penny Pierce"
         },
         {
            "id": 2,
            "name": "Kasey Keller"
         }
      ],
      "greeting": "Hello, Lang Williamson! You have 9 unread messages.",
      "favoriteFruit": "apple"
   },
   {
      "_id": "627c9d1860789111b6c218bc",
      "index": 1,
      "guid": "a4ace5f7-2408-4407-a967-ea77c5151cd9",
      "isActive": false,
      "balance": "$1,006.24",
      "picture": "http://placehold.it/32x32",
      "age": 37,
      "eyeColor": "green",
      "name": "Burke Conrad",
      "gender": "male",
      "company": "TELPOD",
      "email": "burkeconrad@telpod.com",
      "phone": "+1 (986) 541-2662",
      "address": "876 Jackson Place, Caron, Arizona, 431",
      "about": "Culpa ut aliqua ipsum aute et. Ea aute duis nisi et eu. Incididunt nostrud amet aute velit aliqua eiusmod laborum excepteur tempor minim Lorem Lorem do. Ut nostrud aliquip labore incididunt dolor minim in. Do ea nulla laboris consectetur labore consectetur mollit dolore. Est in ipsum sint laborum tempor.\r\n",
      "registered": "2016-02-27T11:24:21 -05:00",
      "latitude": 51.01239,
      "longitude": 13.597732,
      "tags": [
         "esse",
         "ut",
         "consequat",
         "eiusmod",
         "commodo",
         "dolore",
         "incididunt"
      ],
      "friends": [
         {
            "id": 0,
            "name": "Deidre Briggs"
         },
         {
            "id": 1,
            "name": "Woods Ortega"
         },
         {
            "id": 2,
            "name": "Elvira Castaneda"
         }
      ],
      "greeting": "Hello, Burke Conrad! You have 2 unread messages.",
      "favoriteFruit": "strawberry"
   },
   {
      "_id": "627c9d1814c4aaa04a0fea27",
      "index": 2,
      "guid": "4be3883b-a9eb-4594-942c-0acbbbdcf87d",
      "isActive": false,
      "balance": "$2,712.66",
      "picture": "http://placehold.it/32x32",
      "age": 34,
      "eyeColor": "green",
      "name": "Irwin Miles",
      "gender": "male",
      "company": "LOCAZONE",
      "email": "irwinmiles@locazone.com",
      "phone": "+1 (988) 436-3978",
      "address": "918 Opal Court, Escondida, New Mexico, 8775",
      "about": "Et mollit Lorem nostrud quis sint nulla elit fugiat et. Pariatur officia laboris ex nisi eu amet voluptate. Amet aliqua sunt Lorem labore elit pariatur. Eiusmod Lorem adipisicing aliqua mollit quis ipsum deserunt et do. Pariatur non mollit magna ea commodo Lorem.\r\n",
      "registered": "2019-05-01T04:50:09 -05:00",
      "latitude": -50.066213,
      "longitude": 31.641433,
      "tags": [
         "officia",
         "sint",
         "tempor",
         "id",
         "commodo",
         "ad",
         "magna"
      ],
      "friends": [
         {
            "id": 0,
            "name": "Ochoa Ochoa"
         },
         {
            "id": 1,
            "name": "Phillips Norman"
         },
         {
            "id": 2,
            "name": "Kerry Sargent"
         }
      ],
      "greeting": "Hello, Irwin Miles! You have 8 unread messages.",
      "favoriteFruit": "apple"
   },
   {
      "_id": "627c9d18ea31cd5f924b4093",
      "index": 3,
      "guid": "908500e4-8c11-4741-947a-c191a6168891",
      "isActive": true,
      "balance": "$2,519.60",
      "picture": "http://placehold.it/32x32",
      "age": 26,
      "eyeColor": "brown",
      "name": "Foley Potts",
      "gender": "male",
      "company": "VORATAK",
      "email": "foleypotts@voratak.com",
      "phone": "+1 (896) 425-3415",
      "address": "588 Bryant Street, Libertytown, North Carolina, 5749",
      "about": "Elit consectetur voluptate cupidatat minim eu ut Lorem et. Et Lorem proident sint nulla eu est. Deserunt in reprehenderit incididunt ad laboris sit enim. Culpa dolore ex culpa do adipisicing sint velit.\r\n",
      "registered": "2015-03-27T12:41:48 -05:00",
      "latitude": 69.821149,
      "longitude": -164.251312,
      "tags": [
         "ad",
         "adipisicing",
         "adipisicing",
         "est",
         "occaecat",
         "dolore",
         "dolor"
      ],
      "friends": [
         {
            "id": 0,
            "name": "Penelope Griffin"
         },
         {
            "id": 1,
            "name": "Bowers Dejesus"
         },
         {
            "id": 2,
            "name": "Krystal Payne"
         }
      ],
      "greeting": "Hello, Foley Potts! You have 8 unread messages.",
      "favoriteFruit": "banana"
   },
   {
      "_id": "627c9d18cd9dcc1b6df33961",
      "index": 4,
      "guid": "bd35a059-25de-4f4e-82bd-39b4ae466914",
      "isActive": true,
      "balance": "$1,163.13",
      "picture": "http://placehold.it/32x32",
      "age": 23,
      "eyeColor": "blue",
      "name": "Dianna Shaffer",
      "gender": "female",
      "company": "MEMORA",
      "email": "diannashaffer@memora.com",
      "phone": "+1 (992) 509-3163",
      "address": "157 Grimes Road, Golconda, Nevada, 8419",
      "about": "Est mollit dolor adipisicing sunt consectetur. Exercitation consequat duis labore id dolor magna. Irure occaecat quis nostrud ad consectetur. Exercitation ea dolore voluptate commodo voluptate.\r\n",
      "registered": "2014-12-24T06:22:49 -05:00",
      "latitude": -84.738392,
      "longitude": 109.55664,
      "tags": [
         "sunt",
         "quis",
         "excepteur",
         "nulla",
         "eiusmod",
         "nostrud",
         "consequat"
      ],
      "friends": [
         {
            "id": 0,
            "name": "Maldonado Ellison"
         },
         {
            "id": 1,
            "name": "Lucas Beasley"
         },
         {
            "id": 2,
            "name": "Lancaster Soto"
         }
      ],
      "greeting": "Hello, Dianna Shaffer! You have 9 unread messages.",
      "favoriteFruit": "apple"
   }
]
```

Task
Make simple website
