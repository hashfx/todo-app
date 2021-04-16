# ToDo App (web-based)

Created using Flask and MongoDB

 ## TODO App 
 ### Developer: Harsh Soni
 ### Contributors: Harsh Soni
 ## Directories in todo-app
+ app.py
+ requirements.txt
+ Procfile (for Heroku deployment)
+ dir\todo
  + dir\static
    + dir\assets
      + emoji.css
      + emoji.js
      + style.js
      + twemoji.min.js
    + dir\images
      + favicon.png (16x16)
      + no.png (25x25)
      + yes.png (25x25)
  + dir\templates
    + index.html
    + searchlist.html
    + update.html

### Libraries used: 
```
pip install flask
pip install bson
pip install pymongo
pip install gunicorn
```

## Interface
### First Interface of the app running on localhost:port5000:status200
![01](https://user-images.githubusercontent.com/69109482/114984080-fd885300-9eae-11eb-860d-22fc5b9a6f16.png)

### Get all tasks here:
![02](https://user-images.githubusercontent.com/69109482/114984087-feb98000-9eae-11eb-8d6b-7d22abe3d543.png)
### All Completed tasks:

![03](https://user-images.githubusercontent.com/69109482/114984089-ffeaad00-9eae-11eb-95d3-399c32dd551a.png)
### Create a task:
  #### Click on: **Add a Task** __>>__ **Create**

![04](https://user-images.githubusercontent.com/69109482/114984095-00834380-9eaf-11eb-9fe7-7cffbea54d59.png)
### Your newly added task has been added to the **All Tasks List**
![05](https://user-images.githubusercontent.com/69109482/114984099-01b47080-9eaf-11eb-9051-93c659990aff.png)

### Click on **Cross** :x: to mark a task complete
![06](https://user-images.githubusercontent.com/69109482/114984103-024d0700-9eaf-11eb-82a2-d2fd6951520c.png)

### Your task has been added :heavy_check_mark: to **Completed Section**
![07](https://user-images.githubusercontent.com/69109482/114984106-02e59d80-9eaf-11eb-9835-e52bf59a19e1.png)

### Update a Task:
![08](https://user-images.githubusercontent.com/69109482/114984109-0416ca80-9eaf-11eb-9e74-1bb86c1febd0.png)

#### Click: Edit icon :memo: __>>__ Update task to the following interface __>>__ Update Task :rocket:
![09](https://user-images.githubusercontent.com/69109482/114984113-04af6100-9eaf-11eb-905f-f20477f0ad91.png)

### Task has been Updated Successfully :rocket: :white_check_mark:
![10](https://user-images.githubusercontent.com/69109482/114984116-05e08e00-9eaf-11eb-9b3c-7a49396c3dcb.png)

### Delete a Task
#### Click on **Delete** button :wastebasket: to delete a task :heavy_check_mark:
![11](https://user-images.githubusercontent.com/69109482/114984123-06792480-9eaf-11eb-9893-5c9924fd3f25.png)
### Task Search Queries
#### Under Search Reference ![🔍](data:image/png;base64,R0lGODlhDwAPALMPAGKTntz5+wYKCpLIysDAi0xwcW/A3BknJjxZWaXX2I6OYCkpGn7Q86/m5TE9NgAAACH5BAEAAA8ALAAAAAAPAA8AAARX8EkhzhEya1EAMACCaY/geUMyFOPUfYYxzM4GFAaTpk2hHR7ZjBEIAFqH2G5ANNpUzGYDQULMEsUi4EASWLGBBmChIEkcL5FAQTBPNOS2mxSf09l2uCMCADs=) section: __Select__ **Query**  
![13](https://user-images.githubusercontent.com/69109482/114984126-0711bb00-9eaf-11eb-9ae5-1115c36ebe25.png)

#### __After selecting Query >>__ **Type Query Description**
![14](https://user-images.githubusercontent.com/69109482/114984129-07aa5180-9eaf-11eb-94d6-684685f14d5b.png)

#### Your Selected Task is shown as under
![15](https://user-images.githubusercontent.com/69109482/114984130-0842e800-9eaf-11eb-9346-0c7c945acfc1.png)

#### If searched query doesn't exist:

![17](https://user-images.githubusercontent.com/69109482/114984072-fbbe8f80-9eae-11eb-9f62-62578d43f8d4.png)

## Contribution
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[Unlicense](https://choosealicense.com/licenses/unlicense/)

# Thanks <ins>[**Code Blooded Creatures!+!**](https://hashfx.github.io/harshfx/)</ins>
