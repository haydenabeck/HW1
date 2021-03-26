# HW1 for Northwestern coding bootcamp

The goal of this project was to remove bloated code in a prefabricated website. I did so and provided examples of my changes in the readme here.

[Link to the completed page](https://haydenabeck.github.io/HW1/)

1. My fist step in this assignment was commenting what exactly the code was doing. I commented in the functionality and purpose of each section of code. You can find my comments on both the html and css files now, previously there were none.

2. My second step was consolidating the css code. You can find my consolidated code on lines 54-76, 79-97, and 101-123

54-76
`.hero {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("../images/digital-marketing-meeting.jpg");
    background-size: cover;
    background-position: center;
}

.content h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.center-page {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', 'Calibri', 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}`

79-97
`.float-left {
    float: left;
    margin-right: 25px;
}

.float-right {
    float: right;
    margin-left: 25px;
}

.content {
    width: 75%;
    display: inline-block;
    margin-left: 20px;
}

.content img {
    max-height: 200px;
}`

101-123
`.benefits {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', 'Calibri', 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
    color: #ffffff;
}

.benefits h3 {
    margin-top: 20px;
    margin-bottom: 10px;
    text-align: center;
}

.benefits img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}`

3. Added a screenshot of the completed project for reference
![Completed page](Screenshot(9).png)