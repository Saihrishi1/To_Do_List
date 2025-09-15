# Ex03 To-Do List using JavaScript
## Date: 15-09-2025

## AIM
To create a To-do Application with all features using JavaScript.

## ALGORITHM
### STEP 1
Build the HTML structure (index.html).

### STEP 2
Style the App (style.css).

### STEP 3
Plan the features the To-Do App should have.

### STEP 4
Create a To-do application using Javascript.

### STEP 5
Add functionalities.

### STEP 6
Test the App.

### STEP 7
Open the HTML file in a browser to check layout and functionality.

### STEP 8
Fix styling issues and refine content placement.

### STEP 9
Deploy the website.

### STEP 10
Upload to GitHub Pages for free hosting.

## PROGRAM

### Developed By : Sai Hrishi M
### Register No : 212224240140

HTML File
```html

<html>
    <head>
        <script>
            function add()
            {
                var item=document.getElementById("item")
                var list=document.getElementById("list")
                var li=document.createElement("li")
                li.setAttribute('id',item.value)
                li.appendChild(document.createTextNode(item.value))
                list.appendChild(li)
            }
            function remove()
            {
                var list=document.getElementById("list")
                var r=list.lastElementChild
                list.removeChild(r)
            }
        </script>
        <link rel=stylesheet href="exp3.css">
        </head>
    <body>
        <div id="flx">
            <div id="tasktitle">
            <h1>
                To-Do List
            </h1>
            </div>
            <div id="task">
                <ul id="list"></ul>
                <input type="text" id="item" placeholder="Enter a Task">
            </div>
            <button id="add" onclick="add()">Add Task</button>
            <button id="remove" onclick="remove()">Remove Last task</button>
        </div>
        
    </body>
</html>

```

CSS File
```css

body {
    margin: 0;
    padding: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;    
    background-color: #f4f4f4;
    font-family: Arial, sans-serif;
}

#flx {
    text-align: center;
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.2);
}

#task {
    margin: 15px 0;
}

#item {
    padding: 8px;
    width: 200px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

button {
    margin: 5px;
    padding: 8px 15px;
    border: none;
    border-radius: 5px;
    background: #007BFF;
    color: white;
    cursor: pointer;
}

button:hover {
    background: #0056b3;
}


```
## OUTPUT

<img width="1919" height="1137" alt="Screenshot 2025-09-15 113746" src="https://github.com/user-attachments/assets/34a3dea9-b75f-4e0d-8e20-b99c67bc6d4d" />

## RESULT
The program for creating To-do list using JavaScript is executed successfully.
