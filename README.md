# Ex-06-Book-Cover-Design

# Step 1:
Create a new Django project and app.

# Step 2:
Create a static file directory and mention the changes in settings.

# Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

# Step 4:
Write down the code for book cover using HTML and CSS.

# Step 5:
Add images and other contents using CSS record a screenshot of it.

# code HTML
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Book Cover Page</title>
    </head>
    <link rel="stylesheet" href="style.css">
    <meta name="viewport" 
    content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Caveat&family=Dancing+Script:wght@600&family=Ephesis&family=PT+Serif:wght@700&family=Preahvihear&family=Roboto+Mono:ital,wght@1,700&family=Rubik+Doodle+Shadow&family=Vina+Sans&display=swap" rel="stylesheet">

    <body>
        <div class="book_page">
            <div class="name">
                G U R U M U R T H Y . S
                
            </div>
            <div class="title1">
                <h1>DO ONE THING EVERY DAY THAT SCARES YOU</h1>
            </div>
            <duv>
                <h6 class="tips">If you set your goals ridiculously high and it's a failure, you will fail above everyone else's success.</h6>
            </duv>
            <div class="image">
                <img src="c:\Users\admin\Pictures\Screenshots\guru.jpg" width="100px" height="150px">
            </div>
            <div>
                <hr>
            </div>

        </div>
    </body>
</html>
```
# code CSS

```css
.book_page{
            
            width: 400px;
            height: 600px;
            background-color: antiquewhite;
            color: bisque;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            background-image:url(book_cover.png);
            background-size: cover;
        }
.name{
            color : rgb(216, 216, 144);
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; 
            position: relative;
            text-align: center;
            text-shadow: 2px 2px rgb(129, 77, 29);
        }
.title1{
            display: grid;
            grid-template-columns: 1fr;
            grid-template-rows: 1fr;
            position: relative;
            text-align: center;
            font-size: 2px;
            margin: solid none;
            text-wrap: wrap;
            text-shadow: 5px 3px rgb(66, 34, 4);
            padding: 10px;
            color: rgb(215, 190, 168);
            font-size: 25px;
            font-family: Afacad;
            ;
        }
.tips{
    font-size: 15px;
    color: rgb(214, 161, 92);
    text-align: center;
    top: 255px;
    text-shadow: 2px 2px rgb(112, 77, 27);

}
.image{
    position: relative;
    top: 1px;
    left:270px;
    width:100px;
    height: 150px;
    background-size: cover;
    border: 3px solid rgb(26, 21, 21);
}

```
# output

![book_cover_page](https://github.com/GURUMUR/Ex-06-Book-Cover-Design/assets/144895197/5d65fba0-b3be-4455-9a2c-7b3b8733a099)
