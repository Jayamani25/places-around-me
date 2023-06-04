# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Create a new django project and app
### Step 2:
Add a new imagemap html file in templates and neede images in static folder and define it in settings.
### Step 3:
Type ur image map code in the html with coordinates and target file to redirect on click
### Step 4:
Define your components pages and create content in such a way that it gives information about place which is being clicked
### Step 5:
Include pictures and contents for your subpages and map them using urls and views
## Code:
### Index 
```html
<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Maps
        </title>
    </head>
    <body bgcolor="black">
        <h1 align="Center">
            Images Maps By Jayamani
        </h1>
        <h3 align="left" >
            Below Image shows various places around my home.<br>Click the locations and get information about it.
        </h3>
       <img id="Image-Maps-Com-image-maps-2023-06-03-055009" src="maps.png" border="0" width="1920" height="910" orgWidth="1920" orgHeight="910" usemap="#image-maps-2023-06-03-055009" alt="" />
<map name="image-maps-2023-06-03-055009" id="ImageMapsCom-image-maps-2023-06-03-055009">
<area  alt="" title="Home" href="Home.html" shape="rect" coords="882,418,932,468" style="outline:none;" target="_self"     />
<area  alt="" title="College" href="College.html" shape="rect" coords="1036,371,1086,421" style="outline:none;" target="_self"     />
<area  alt="" title="Hotel" href="Hotel.html" shape="rect" coords="1452,754,1502,804" style="outline:none;" target="_self"     />
<area  alt="" title="Bus" href="Bus.html" shape="rect" coords="601,142,651,192" style="outline:none;" target="_self"     />
<area  alt="" title="School" href="School.html" shape="rect" coords="1466,117,1516,167" style="outline:none;" target="_self"     />
<area shape="rect" coords="1918,908,1920,910" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
</map>

    </body>
</html>
```
### Bus Stop:
```html
<!DOCTYPE html>
<html>
    <head>
         <style>
        p{
            color: aliceblue;
        }
        </style>
        <title>
            Bus stop
        </title>
    </head>
    <body bgcolor="Black">
        <h1>Bus Stop</h1>
        <p>
            The Chennai Mofussil Bus Terminus (CMBT) is located in Koyambedu, Chennai on the 100 feet inner-ring road (Jawaharlal Nehru Road) between SAF Games Village and the Koyambedu Vegetable Market 1. It is one of Asia’s largest bus terminals and provides inter-state bus transport services 12. 
        </p>
    </body>
</html>
```
### College:
```html
<!DOCTYPE html>
<html>
    <head>
         <style>
        p{
            color: aliceblue;
        }
        </style>
        <title>
            College
        </title>
    </head>
    <body bgcolor="Black">
        <h1>College</h1>
        <p>
            College life is a unique experience that is different from school life. It is known as one of the most memorable years of one’s life 12. College life exposes us to new experiences and things that we were not familiar with earlier 2. It teaches us many things and builds our confidence to face the challenges and struggles in our future 1. Instead of just focusing on studies, it is important to participate in other activities and socialize as much as possible in college life as all these things help in the overall development of a person 1.
        </p>
    </body>
</html>
```
### Home:
```html
<!DOCTYPE html>
<html>
    <head>
        <style>
        p{
            color: aliceblue;
        }
        </style>
        <title>
            Home
        </title>
    </head>
    <body bgcolor="Black">
        <h1>My Home</h1>
        <p>
            The word “home” can have different meanings depending on the context. It can refer to a physical place where someone lives or grew up, or it can be a metaphor for a feeling of comfort and belonging 12. For example, some people might describe home as a place where they feel safe and secure, while others might describe it as a place where they can be themselves and relax 3.
        </p>
    </body>
</html>
```
### Hotel:
```html
<!DOCTYPE html>
<html>
    <head>
         <style>
        p{
            color: aliceblue;
        }
        </style>
        <title>
            Hotel
        </title>
    </head>
    <body bgcolor="Black">
        <h1>Hotel</h1>
        <p>
        A hotel is an establishment that provides paid lodging on a short-term basis 1. Facilities provided inside a hotel room may range from a modest-quality mattress in a small room to large suites with bigger, higher-quality beds, a dresser, a refrigerator and other kitchen facilities, upholstered chairs, a flat screen television, and en-suite bathrooms 1. Most hotels list a variety of services, such as room service, laundry, and concierge 2.            
        </p>
    </body>
</html>
```
### School:
```html
<!DOCTYPE html>
<html>
    <head>
         <style>
        p{
            color: aliceblue;
        }
        </style>
        <title>
            School
        </title>
    </head>
    <body bgcolor="Black">
        <h1>School</h1>
        <p>
        A school is an educational institution designed to provide learning spaces and learning environments for the teaching of students under the direction of teachers 1. Most countries have systems of formal education, which is sometimes compulsory. In these systems, students progress through a series of schools 1.

Schools can be described in terms of their mission, history, reputation, ethics, structure, approach, facilities, staff, students, culture, general environment and results 2. It is common for school descriptions to include overused cliche vocabulary such as “excellence” and “enable” 2.
        </p>
    </body>
</html>
```
## Output:
![Op](https://github.com/Jayamani25/places-around-me/assets/85949888/69cba2dd-c731-447b-878a-a88d43c53e9f)
![SchoolOP](https://github.com/Jayamani25/places-around-me/assets/85949888/fbb5ce9f-c8f2-45cf-84f1-20b4b76cb606)
![busop](https://github.com/Jayamani25/places-around-me/assets/85949888/1fefeff0-2242-412c-b3a5-e898ebcaeaa6)
![validop](https://github.com/Jayamani25/places-around-me/assets/85949888/dd038531-2c1a-4cbd-88a9-ed66e07a6663)

## Result:
Thus a website is developed to display details about the places around my house.
