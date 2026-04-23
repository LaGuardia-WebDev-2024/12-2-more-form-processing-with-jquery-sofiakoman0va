[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23694418)
# 12-2-More-form-processing-with-jQuery

## Video

[Video](https://youtu.be/DeEAsYwhVdY) <-- Make sure to watch this video first<br>

## Directions

### Step #1 - Process the form <br>
This webpage displays a form for ordering donuts We've already set up the basic form processing handler for you AND added images for a glazed, jelly and boston cream donut.
<br><br>
In this step, you're going to change the processing logic to get the value of the selected drop down item, and add a corresponding image to the body.
<br><br>
_Hint:_<br> 
```
var $donutType = $(this).find("[name=type]"); 
var donutType = XXXXX.YYYYY;
var $img = $("ZZZZZ");
$img.width(100);
$img.attr("src", AAAAA);
$img.appendTo("body");
```
<br><br>
### Step #2 - Extra - Add a *new* donut type <br>
_Do this step only if you have extra time_<br><br>
Add another donut type to the ordering system. 
