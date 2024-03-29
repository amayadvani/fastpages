--- 
title: Guide for Review 
author: Amay Advani
layout: base
description: Week 24 grade and cb
---

### 3)a)i)

The purpose of my feature is to help users be more productive by creatingI made a online notebook, in which the user can take notes while watching a video or listening to the teacher. This notebook makes it efficient for a student to recall useful information and keep it saved until they want to.

### 3)a)ii)

The user has access to 5 different pages, one per each subject in school. Each page in the notebook has the same function and has a text area with a save and delete function to respectively save and delete the users input.

### 3)a)iii)

The user inputs their notes into a text area in which they have the option to either save or deleted the previously saved request. The output is the result from the get request after being put or post. 

### 3)b)i) + 3)b)ii
```
   function del_data(){
      let mt = [];
      localStorage.setItem("x", JSON.stringify(mt))
      document.getElementById("input2").value = ""
   }
```

Stringifies inputed data and puts it into a list to iterate through. 


'''
<!--<button onclick="del_data()" id="delete" class="button">Delete All</button>-->
'''

### 3)b)iii)

Name of list: mt = []

### 3)b)iv)

The list, mt, represents the data that is used as a replacement of textarea input value after one of the buttons are pressed to activate a save or delete function.

### 3)b)v)

The use of this list manages complexity due to the quick and easy replacement of the user input by a blank space to delete what the user had previously inputed. Another way I would have done this is to iterate through the user input and check if any of the input is equal to another list with all of the letters in the alphabet. If this boolean is true, then delete the input.

### 3)c)i)

```
function save_data() {
      let data = document.getElementById("input2").value.split(" ");
      localStorage.setItem("c", JSON.stringify(data))
    } 
   document.getElementById("input2").value = JSON.parse(localStorage.getItem("c")).join(" ")

```

### 3)c)ii)

```
<button onclick="save_data()" id="save" class="button">Save</button>
```

### 3)c)iii)

This program contributes to the functionality of the whole feature because it allows for the user input to be saved locally by the click of a button.

### 3)c)iv)

The function save data starts off with creating a variable, data, that contains the data from the textarea input, separated by a space. Next, it stringifies the data using the JSON.stringify function in js, and saves it to local storage using a specific key. Finally, it parses the data to then join it back together and display it as it was. 

### 3)d)

First call:

Both functions, delete and save data are called through the onclick function in html. The save function saves user input into localstorage using a key and value. The delete function makes the user input equal to an empty list. 

```
<button onclick="save_data()" id="save" class="button">Save</button>
<button onclick="del_data()" id="del" class="button">Delete All</button>
```

Second Call:

I call another function, known as bad_words(), that only activates when a change has occured in the textbox, to make sure that there are no bad words in the note. If there is a bad word detected in the user input, it would essentially delete all of the user input. 

```
<textarea class="input" placeholder="Take some notes!" id="input2" onchange="bad_words()"></textarea>

```

### Grading

| Category                | Score | CB Score | Comments |
|------------------------|-------|----------|----------|
| Program Purpose and Function | 1 | 1  | valid purpose  with decent function  |
| Data Abstraction       | 1 | 1 | uses a list to show data abstraction     |
| Managing Complexity    | 1 | 1 | manages complexity     |
| Procedural Abstraction | 1 | 1 | develops procedure and functionality is described       |
| Algorithm Implementation| 1 | 1 | Describes so that it can be recreated.       |
| Testing                | 1 | 1 | Calls procedures and describes conditions      |
| Total                | 6/6 | 6/6 |    ->      |










