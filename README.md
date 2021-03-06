# <span role="image" aria-label="🥘" style="font-family: &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, NotoColorEmoji, &quot;Noto Color Emoji&quot;, &quot;Segoe UI Symbol&quot;, &quot;Android Emoji&quot;, EmojiSymbols; line-height: 1em;">🥘</span> Not-a-Potluck Back End Product Overview

A event organization app where users can create an event, invite guests, and add food items which guest can then claim!

## User Stories
1. As an `organizer` I can create an upcoming `potluck` and invite my friends to attend

2. As an `organizer` I can adjust `date`s, `time`s and `location`s of the potluck

3. As an `organizer` I can use the list feature in my app to add food `items` that we'd like to see at the potluck

4. As a `guest` to a potluck I want to be able to confirm that I'm going to the upcoming `event`

5. As a `guest` I'd like to be able to select which `item`s I'd like to be responsible for bringing

## Base URL
- https://lre-notapotluck.herokuapp.com/

## Contributors

| [Harry Gebel](https://github.com/HarryHenryGebel)                                                                                                                     | [Josh Glantz](https://github.com/Jahteo)                                                                                                                     | [Lauren Emick](https://github.com/laurenemick)                                                                                                                     | [Ava Wingfield](https://github.com/avawing)                                                                                                                     |  
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [<img src="https://avatars3.githubusercontent.com/u/1482486?s=460&u=7d08f54ec0a05764e016399e3a404b3831c08331&v=4" width = "200" />](https://github.com/HarryHenryGebel) | [<img src="https://avatars3.githubusercontent.com/u/65362632?s=460&u=d3fe1f25d6d736abb735bfaaa07bdc19bc0e850d&v=4" width = "200" />](https://github.com/Jahteo) | [<img src="https://avatars0.githubusercontent.com/u/64444915?s=460&u=a9c3af2aa4f156e00677aef2e7fd2b210898c311&v=4" width = "200" />](https://github.com/laurenemick) | [<img src="https://avatars1.githubusercontent.com/u/64428775?s=460&u=b978293f3ab12800a3f6d3caf917e22fe4de55a1&v=4" width = "200" />](https://github.com/avawing) |
|                                   React II Engineer    [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/HarryHenryGebel)   [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/harryhenrygebel/)                                     |                          React I Engineer              [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/Jahteo)     [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/josh-glantzhucks/)                                     |                                 Back End Engineer      [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/laurenemick)   [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/laurenemick/)                                     |                                    React II Engineer   [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/avawing)   [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/avawingfield/)                                     |
                   

| [Virginia Scirrotto](https://github.com/c0d3-vp)                                                                                                                     | [Fatima Rizvi](https://github.com/fatima-rizvi)                                                                                                                     | [Samantha Dutcher](https://github.com/Samantha-Dutcher1986)                                                                                                                     |  
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [<img src="https://avatars3.githubusercontent.com/u/42188072?s=460&u=2ada381430d55b71c5edd97770e4c8e61f7eedc1&v=4" width = "200" />](https://github.com/c0d3-vp) | [<img src="https://avatars2.githubusercontent.com/u/68958153?s=460&u=df691c22c18efbffeabb1a3cae329d3b08e6d768&v=4" width = "200" />](https://github.com/fatima-rizvi)                | [<img src="https://avatars2.githubusercontent.com/u/68967583?s=460&u=ccb7bbd7643ed7994f0d2882eca812a9968968b1&v=4" width = "200" />](https://github.com/Samantha-Dutcher1986) |
|                                Front End Engineer       [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/c0d3-vp)   [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/virginia-a-scirrotto-60b072163/)                                     |                               Front End Engineer        [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/fatima-rizvi)  [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/fatima-rizvi/)                                        |                                   Front End Engineer    [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/Samantha-Dutcher1986)     [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/samantha-dutcher-1580951b4/)                                  |
      
<br>

## Tech Stack
- Java
- Spring Boot
- JUnit 4
- PostgreSQL
- OAuth2
- Swagger
- Maven

## APIs

#### [Front End](https://not-a-potluck.gebel.tech/) deployed via netlify

#### [Back End](https://lre-notapotluck.herokuapp.com/) deployed via Heroku

## Endpoints

#### GET

<details>
<summary>http://localhost:2019/users/user/2</summary>
  
```JSON

{
    "userid": 2,
    "username": "laurenemick",
    "primaryemail": "lauren@lauren.com",
    "imageurl": null,
    "potlucks": [
        {
            "potluckid": 3,
            "eventname": "Lunch at Gasworks",
            "date": "09/01/2020",
            "time": "11:30am",
            "location": "Gasworks park",
            "description": "North side, look for red umbrella",
            "foods": [
                {
                    "foodid": 4,
                    "foodname": "pizza"
                },
                {
                    "foodid": 5,
                    "foodname": "salad"
                }
            ],
            "guests": [
                {
                    "guestid": 6,
                    "fname": "Alex",
                    "lname": "Thilen",
                    "primaryemail": "alex@alex.com",
                    "responded": false,
                    "attending": false
                },
                {
                    "guestid": 7,
                    "fname": "Adrienne",
                    "lname": "Emick",
                    "primaryemail": "adj@adj.com",
                    "responded": false,
                    "attending": false
                }
            ]
        }
    ],
    "roles": [
        {
            "role": {
                "roleid": 1,
                "name": "USER"
            }
        }
    ]
}
```

</details>

<details>
<summary>http://localhost:2019/potlucks/potlucks</summary>
  
```JSON
[
    {
        "potluckid": 3,
        "eventname": "Lunch at Gasworks",
        "date": "09/01/2020",
        "time": "11:30am",
        "location": "Gasworks park",
        "description": "North side, look for red umbrella",
        "user": {
            "userid": 2,
            "username": "laurenemick",
            "primaryemail": "lauren@lauren.com",
            "imageurl": null,
            "roles": [
                {
                    "role": {
                        "roleid": 1,
                        "name": "USER"
                    }
                }
            ]
        },
        "foods": [
            {
                "foodid": 4,
                "foodname": "pizza"
            },
            {
                "foodid": 5,
                "foodname": "salad"
            }
        ],
        "guests": [
            {
                "guestid": 6,
                "fname": "Alex",
                "lname": "Thilen",
                "primaryemail": "alex@alex.com",
                "responded": false,
                "attending": false
            },
            {
                "guestid": 7,
                "fname": "Adrienne",
                "lname": "Emick",
                "primaryemail": "adj@adj.com",
                "responded": false,
                "attending": false
            }
        ]
    },
    {
        "potluckid": 9,
        "eventname": "Halloween Party",
        "date": "10/31/2020",
        "time": "4:00pm",
        "location": "1111 90th pl ne, Seattle WA",
        "description": "Black and orange balloons by gate",
        "user": {
            "userid": 8,
            "username": "hannah",
            "primaryemail": "hannah@hannah.com",
            "imageurl": null,
            "roles": [
                {
                    "role": {
                        "roleid": 1,
                        "name": "USER"
                    }
                }
            ]
        },
        "foods": [
            {
                "foodid": 10,
                "foodname": "burgers"
            },
            {
                "foodid": 11,
                "foodname": "salad"
            }
        ],
        "guests": [
            {
                "guestid": 12,
                "fname": "harry",
                "lname": "harry",
                "primaryemail": "harry@harry.com",
                "responded": false,
                "attending": false
            },
            {
                "guestid": 13,
                "fname": "fatima",
                "lname": "fatima",
                "primaryemail": "fatima@fatima.com",
                "responded": false,
                "attending": false
            }
        ]
    }
]
```

</details>

<details>
<summary>http://localhost:2019/guests/guests</summary>
  
```JSON

[
    {
        "guestid": 6,
        "fname": "Alex",
        "lname": "Thilen",
        "primaryemail": "alex@alex.com",
        "responded": false,
        "attending": false,
        "potluck": {
            "potluckid": 3,
            "eventname": "Lunch at Gasworks",
            "date": "09/01/2020",
            "time": "11:30am",
            "location": "Gasworks park",
            "description": "North side, look for red umbrella",
            "user": {
                "userid": 2,
                "username": "laurenemick",
                "primaryemail": "lauren@lauren.com",
                "imageurl": null,
                "roles": [
                    {
                        "role": {
                            "roleid": 1,
                            "name": "USER"
                        }
                    }
                ]
            },
            "foods": [
                {
                    "foodid": 4,
                    "foodname": "pizza"
                },
                {
                    "foodid": 5,
                    "foodname": "salad"
                }
            ],
            "guests": [
                {
                    "guestid": 6,
                    "fname": "Alex",
                    "lname": "Thilen",
                    "primaryemail": "alex@alex.com",
                    "responded": false,
                    "attending": false
                },
                {
                    "guestid": 7,
                    "fname": "Adrienne",
                    "lname": "Emick",
                    "primaryemail": "adj@adj.com",
                    "responded": false,
                    "attending": false
                }
            ]
        }
    },
    {
        "guestid": 7,
        "fname": "Adrienne",
        "lname": "Emick",
        "primaryemail": "adj@adj.com",
        "responded": false,
        "attending": false,
        "potluck": {
            "potluckid": 3,
            "eventname": "Lunch at Gasworks",
            "date": "09/01/2020",
            "time": "11:30am",
            "location": "Gasworks park",
            "description": "North side, look for red umbrella",
            "user": {
                "userid": 2,
                "username": "laurenemick",
                "primaryemail": "lauren@lauren.com",
                "imageurl": null,
                "roles": [
                    {
                        "role": {
                            "roleid": 1,
                            "name": "USER"
                        }
                    }
                ]
            },
            "foods": [
                {
                    "foodid": 4,
                    "foodname": "pizza"
                },
                {
                    "foodid": 5,
                    "foodname": "salad"
                }
            ],
            "guests": [
                {
                    "guestid": 6,
                    "fname": "Alex",
                    "lname": "Thilen",
                    "primaryemail": "alex@alex.com",
                    "responded": false,
                    "attending": false
                },
                {
                    "guestid": 7,
                    "fname": "Adrienne",
                    "lname": "Emick",
                    "primaryemail": "adj@adj.com",
                    "responded": false,
                    "attending": false
                }
            ]
        }
    },
    {
        "guestid": 12,
        "fname": "harry",
        "lname": "harry",
        "primaryemail": "harry@harry.com",
        "responded": false,
        "attending": false,
        "potluck": {
            "potluckid": 9,
            "eventname": "Halloween Party",
            "date": "10/31/2020",
            "time": "4:00pm",
            "location": "1111 90th pl ne, Seattle WA",
            "description": "Black and orange balloons by gate",
            "user": {
                "userid": 8,
                "username": "hannah",
                "primaryemail": "hannah@hannah.com",
                "imageurl": null,
                "roles": [
                    {
                        "role": {
                            "roleid": 1,
                            "name": "USER"
                        }
                    }
                ]
            },
            "foods": [
                {
                    "foodid": 10,
                    "foodname": "burgers"
                },
                {
                    "foodid": 11,
                    "foodname": "salad"
                }
            ],
            "guests": [
                {
                    "guestid": 12,
                    "fname": "harry",
                    "lname": "harry",
                    "primaryemail": "harry@harry.com",
                    "responded": false,
                    "attending": false
                },
                {
                    "guestid": 13,
                    "fname": "fatima",
                    "lname": "fatima",
                    "primaryemail": "fatima@fatima.com",
                    "responded": false,
                    "attending": false
                }
            ]
        }
    },
    {
        "guestid": 13,
        "fname": "fatima",
        "lname": "fatima",
        "primaryemail": "fatima@fatima.com",
        "responded": false,
        "attending": false,
        "potluck": {
            "potluckid": 9,
            "eventname": "Halloween Party",
            "date": "10/31/2020",
            "time": "4:00pm",
            "location": "1111 90th pl ne, Seattle WA",
            "description": "Black and orange balloons by gate",
            "user": {
                "userid": 8,
                "username": "hannah",
                "primaryemail": "hannah@hannah.com",
                "imageurl": null,
                "roles": [
                    {
                        "role": {
                            "roleid": 1,
                            "name": "USER"
                        }
                    }
                ]
            },
            "foods": [
                {
                    "foodid": 10,
                    "foodname": "burgers"
                },
                {
                    "foodid": 11,
                    "foodname": "salad"
                }
            ],
            "guests": [
                {
                    "guestid": 12,
                    "fname": "harry",
                    "lname": "harry",
                    "primaryemail": "harry@harry.com",
                    "responded": false,
                    "attending": false
                },
                {
                    "guestid": 13,
                    "fname": "fatima",
                    "lname": "fatima",
                    "primaryemail": "fatima@fatima.com",
                    "responded": false,
                    "attending": false
                }
            ]
        }
    }
]
```

</details>

<details>
<summary>http://localhost:2019/foods/foods</summary>
  
```JSON
[
    {
        "foodid": 4,
        "foodname": "pizza",
        "potluck": {
            "potluckid": 3,
            "eventname": "Lunch at Gasworks",
            "date": "09/01/2020",
            "time": "11:30am",
            "location": "Gasworks park",
            "description": "North side, look for red umbrella",
            "user": {
                "userid": 2,
                "username": "laurenemick",
                "primaryemail": "lauren@lauren.com",
                "imageurl": null,
                "roles": [
                    {
                        "role": {
                            "roleid": 1,
                            "name": "USER"
                        }
                    }
                ]
            },
            "foods": [
                {
                    "foodid": 4,
                    "foodname": "pizza"
                },
                {
                    "foodid": 5,
                    "foodname": "salad"
                }
            ],
            "guests": [
                {
                    "guestid": 6,
                    "fname": "Alex",
                    "lname": "Thilen",
                    "primaryemail": "alex@alex.com",
                    "responded": false,
                    "attending": false
                },
                {
                    "guestid": 7,
                    "fname": "Adrienne",
                    "lname": "Emick",
                    "primaryemail": "adj@adj.com",
                    "responded": false,
                    "attending": false
                }
            ]
        }
    },
    {
        "foodid": 5,
        "foodname": "salad",
        "potluck": {
            "potluckid": 3,
            "eventname": "Lunch at Gasworks",
            "date": "09/01/2020",
            "time": "11:30am",
            "location": "Gasworks park",
            "description": "North side, look for red umbrella",
            "user": {
                "userid": 2,
                "username": "laurenemick",
                "primaryemail": "lauren@lauren.com",
                "imageurl": null,
                "roles": [
                    {
                        "role": {
                            "roleid": 1,
                            "name": "USER"
                        }
                    }
                ]
            },
            "foods": [
                {
                    "foodid": 4,
                    "foodname": "pizza"
                },
                {
                    "foodid": 5,
                    "foodname": "salad"
                }
            ],
            "guests": [
                {
                    "guestid": 6,
                    "fname": "Alex",
                    "lname": "Thilen",
                    "primaryemail": "alex@alex.com",
                    "responded": false,
                    "attending": false
                },
                {
                    "guestid": 7,
                    "fname": "Adrienne",
                    "lname": "Emick",
                    "primaryemail": "adj@adj.com",
                    "responded": false,
                    "attending": false
                }
            ]
        }
    },
    {
        "foodid": 10,
        "foodname": "burgers",
        "potluck": {
            "potluckid": 9,
            "eventname": "Halloween Party",
            "date": "10/31/2020",
            "time": "4:00pm",
            "location": "1111 90th pl ne, Seattle WA",
            "description": "Black and orange balloons by gate",
            "user": {
                "userid": 8,
                "username": "hannah",
                "primaryemail": "hannah@hannah.com",
                "imageurl": null,
                "roles": [
                    {
                        "role": {
                            "roleid": 1,
                            "name": "USER"
                        }
                    }
                ]
            },
            "foods": [
                {
                    "foodid": 10,
                    "foodname": "burgers"
                },
                {
                    "foodid": 11,
                    "foodname": "salad"
                }
            ],
            "guests": [
                {
                    "guestid": 12,
                    "fname": "harry",
                    "lname": "harry",
                    "primaryemail": "harry@harry.com",
                    "responded": false,
                    "attending": false
                },
                {
                    "guestid": 13,
                    "fname": "fatima",
                    "lname": "fatima",
                    "primaryemail": "fatima@fatima.com",
                    "responded": false,
                    "attending": false
                }
            ]
        }
    },
    {
        "foodid": 11,
        "foodname": "salad",
        "potluck": {
            "potluckid": 9,
            "eventname": "Halloween Party",
            "date": "10/31/2020",
            "time": "4:00pm",
            "location": "1111 90th pl ne, Seattle WA",
            "description": "Black and orange balloons by gate",
            "user": {
                "userid": 8,
                "username": "hannah",
                "primaryemail": "hannah@hannah.com",
                "imageurl": null,
                "roles": [
                    {
                        "role": {
                            "roleid": 1,
                            "name": "USER"
                        }
                    }
                ]
            },
            "foods": [
                {
                    "foodid": 10,
                    "foodname": "burgers"
                },
                {
                    "foodid": 11,
                    "foodname": "salad"
                }
            ],
            "guests": [
                {
                    "guestid": 12,
                    "fname": "harry",
                    "lname": "harry",
                    "primaryemail": "harry@harry.com",
                    "responded": false,
                    "attending": false
                },
                {
                    "guestid": 13,
                    "fname": "fatima",
                    "lname": "fatima",
                    "primaryemail": "fatima@fatima.com",
                    "responded": false,
                    "attending": false
                }
            ]
        }
    }
]
```

</details>

#### POST

<details>
<summary>http://localhost:2019/createnewuser</summary>
  
```JSON
{
  "username": "ava",
  "password": "password",
  "primaryemail": "ava@ava.com",
  "imageurl": "https://avatars1.githubusercontent.com/u/64428775?s=460&u=b978293f3ab12800a3f6d3caf917e22fe4de55a1&v=4"
}
```

</details>

<details>
<summary>http://localhost:2019/potlucks/user/2/potluck</summary>
  
```JSON
{
  "user": {"userid": 2},
  "eventname": "test",
  "date": "09/01/2020",
  "time": "11:30am",
  "location": "test",
  "description": "test"
}
```

</details>

<details>
<summary>http://localhost:2019/foods/potluck/9/food/test</summary>
  
```JSON
{
  "potluck": {"potluckid": 9},
  "foodname":"test"
}
```

</details>

<details>
<summary>http://localhost:2019/guests/potluck/9/guest/test/test/test@test.com</summary>
  
```JSON
{
"potluck": {"potluckid": 9},
"fname": "test",
"lname": "test",
"primaryemail": "test@test.com"
}
```

</details>

#### PUT

<details>
<summary>http://localhost:2019/users/user/2</summary>
  
```JSON
{
    "username": "laurenemick",
    "password": "password",
    "primaryemail": "lauren@emick.com",
    "imageurl": null
}
```

</details>

#### DELETE

<details>
<summary>http://localhost:2019/potlucks/potluck/9</summary>
  
```JSON
No Body Data

Status OK
```

</details>

<details>
<summary>http://localhost:2019/guests/guest/13</summary>
  
```JSON
No Body Data

Status OK
```

</details>
