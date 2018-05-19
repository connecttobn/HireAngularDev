# `AnuglarJS ToDos`


### Instructions

Use any setup : either local or [plnkr](https://plnkr.co/edit) OR [jsfiddle](https://www.jsfiddle.net) OR [jsbin](https://www.jsbin.com)

**You should build this app using AngularJS 1.x**.

For CSS, if needed you can use Bootstrap/Foundation

### Tasks

1. Fetch data in files [```users.json``` and ```todos.json``` under **resource** folder]
 
    And show the total records in UI using AJAX call.

    **Expected result:**  Records in  Users : \<COUNT> | Records in Todos : \<COUNT>

2. Display Todos for selected User.
    a. UI should have simple drop down to select User
    b. Should show only that user's todos in a table sorted by name.

    Use ```id``` from users to connect with todos ```userId```


3. Show total of todos for each user

Parse data in ```todos``` and show total todos per each user

    **Expected result:**
    User wise data in a table format

    | User          | Todos     |
    | ------------- |----------:|
    | Leanne Graham | 12        |
    | Sigulha       | 1         |
    | ...           |      ...  |


4. Build a simpe client side search for Users
It should search based on ```name```,```username```, ```email```

5.  Using D3 Charts, build bar chart Users(x-axis) vs Todos count(y-axis)