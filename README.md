# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font


SOLUTION
HTML FILE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <header>
        <h1 class="head"> PLP ASSIGNMENT 3</h1>
        <P id="Objective">Link an external CSS file to an HTML document. Apply basic styling using selectors. Use colors, fonts, and spacing effectively.</P>
    </header>

    <h2>Multimedia</h2>
    <img class="image" src="https://cubanvr.com/wp-content/uploads/2023/07/ai-image-generators.webp" alt="my image">
   
</body>
</html>

CSS FILES

body{
    background-color: black;
}
.head{
    text-align: center;
    color: darkblue;
    font: bold;
    font-size: 3rem;
    background-color: bisque;
}
#Objective{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    padding-left: 1rem;
    background-color: lightblue;
}

.image{
    border-radius: 1.3rem;
    margin-bottom: 20rem;
    width: 400px;
    height: 280px;

}


# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
