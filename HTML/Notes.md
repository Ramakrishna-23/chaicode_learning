==>This is the place to jot down all of my things ==>
-->this helps a lot to keep the track of the things<--


web flow high level 

user -> website -> ISP -> DNS -> ISP response with (with IP address) -> finds the target website -> get the connection to the user -> user.


------>HTML Section<----

1) Tags -> acts as container 
2) <h1> </h1> -> this is also container 
3) browser really understand the html everywhere it is the same
4) a) <head> meta data 
    - title , favicon , viewport
5) b) <body> this contains the content  
    - h1 , div , li 
6) 


---documentation----
how to go through the document 


<---block level and inline --->
block level elements takes full from left to right 
inline element take just the small section of the screen

<------- The Exercises of the html--------->
The below are the learnings of the exercises
1.I learnt that there is a progress bar
=> just use <progress></progress> to make rotating or loading thing.
2.Never put label as parent of the input thing 
    <label></label> => label naem : Username
    <input></input> => input password : password **** 

    Never make the <input> tag as the child of <label> tag.
3.Use of form is the good keep that in the mind 
4. <form> is used to collect user input and send it to a server.
5. Form = inputs with name → browser → request → server reads name=value
6. Tables are similar to forms but in more of the tabular style with major 2 sections
    table
 ├── thead        (table header section)
 │    └── tr      (row)
 │         └── th (header cell)
 │
 ├── tbody        (table body section)
 │    └── tr      (row)
 │         └── td (data cell)
 │
 └── tfoot        (optional footer section)
      └── tr
           └── td

7. Multimedia and ARIA tags are also kind of tags but not used much nice to remember.



<---------- Cheat Sheet for FORM's in HTML------------>
<!-- ================= HTML FORM CHEAT SHEET ================= -->

<form action="/submit" method="post" enctype="multipart/form-data"
      target="_self" autocomplete="on" novalidate>

  <!-- LABEL ↔ INPUT CONNECTION -->
  <!-- rule: label.for === input.id -->
  <label for="username">Username</label>
  <input type="text" id="username" name="username" required>

  <label for="password">Password</label>
  <input type="password" id="password" name="password" required>

  <!-- EMAIL + NUMBER -->
  <input type="email" name="email">
  <input type="number" name="age" min="18">

  <!-- TEXTAREA -->
  <textarea name="bio"></textarea>

  <!-- SELECT -->
  <select name="country">
    <option value="in">India</option>
    <option value="us">USA</option>
  </select>

  <!-- RADIO (same name = one choice) -->
  <input type="radio" name="gender" value="male"> Male
  <input type="radio" name="gender" value="female"> Female

  <!-- CHECKBOX (same name = multiple values) -->
  <input type="checkbox" name="skills" value="html"> HTML
  <input type="checkbox" name="skills" value="css"> CSS

  <!-- FILE UPLOAD (needs enctype) -->
  <input type="file" name="resume">

  <!-- HIDDEN DATA -->
  <input type="hidden" name="userId" value="123">

  <!-- MULTIPLE SUBMIT BUTTONS -->
  <button type="submit" name="action" value="save">Save</button>
  <button type="submit" name="action" value="publish">Publish</button>

</form>

<!-- ================= KEY RULES =================
1. Only inputs with `name` are submitted
2. label.for talks ONLY to input.id
3. GET → URL | POST → request body
4. enctype="multipart/form-data" required for files
5. Radio = same name | Checkbox = same name
6. Default: action=current page, method=GET
================================================ -->


<-----------------Tables in HTML------------------------->
below the example for it 
<table border="1">

  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Rama</td>
      <td>25</td>
    </tr>
    <tr>
      <td>Krishna</td>
      <td>30</td>
    </tr>
  </tbody>

</table>
