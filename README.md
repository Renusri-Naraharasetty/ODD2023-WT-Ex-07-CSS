# Ex-07-CSS
NAME : RENUSRI NARAHARASHETTY

DEPARTMENT : ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING

REGISTER NUMBER : 23009126
## 7-I-CSS
# AIM:
Using CSS media queries, modify the webpage's color scheme with the following requirements:

Default Color Scheme: Background color: Light gray (#f4f4f4) Text color: Dark gray (#333) Link color: Blue (#007bff) Small Screen Adaptation (Max-width: 600px):

Change the background color to dark gray (#333) Change the text color to light gray (#f4f4f4) Change the link color to light green (#28a745)

Dark Mode Preference:

If the user has set their device to dark mode, override the above styles with the following: Background color: Black (#000) Text color: White (#fff) Link color: Cyan (#17a2b8)

# PROCEDURE:
## STEP 1:
Start Define the document type as HTML.
## STEP 2:
Open the HTML structure with the necessary head and body sections. In the head section, set the title of the webpage and define the styles for the webpage. The styles include: 

i.Default color scheme for the webpage. 

ii.Adaptations for small screen sizes. 

iii.Adaptations for users who prefer a dark color scheme.
## STEP 3:
In the body section, create a division with the text “Saveetha Engineering College”. Also in the body section, create a list with links to the SEC Home Page with the description about the college about,vision and mission.
## STEP 4:
Run the program.

# CODE:
```<!DOCTYPE html>
<html>
<head>
    <title>7(i)</title>
    <style>
    /* Default Color Scheme */
    body {
            background-color: #f4f4f4;
            color: #333;
        }
        
        a {
            color: #007bff;
        }
        
        /* Small Screen Adaptation */
        @media (max-width: 600px) {
            body {
                background-color: #333;
                color: #f4f4f4;
            }
        
            a {
                color: #28a745;
            }
        }
        
        /* Dark Mode Preference */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: #000;
                color: #fff;
            }
        
            a {
                color: #17a2b8;
            }
        }

    </style>
</head>
<body>
    <div>
    Saveetha Engineering College
  </div>
  <ul>
    <li>Saveetha Engineering College (SEC) was established in 2001, by the Founder Chairman Dr. N. M. Veeraiyan, 
        a committed and dedicated Medical Professional.</li>
    <li>SEC has a total strength of 4349 students in 15 UG courses, 8 PG Courses including MBA, 
        MS by Research and Doctoral programs (PhD)  in five Departments.</li>
    <li>National Board of Accredition NBA has Accredited 5 UG courses.</li>
    <li>Ranked 96 by NIRF- National Institute Ranking Framework for the academic year 2017-18 among all IITs, 
        Central, State and Private Institutions in India. </li>
    <li>Awarded 'A' GRADE with a high score of 3.19 on a scale of 4 by the National Assessment and Accreditation 
        Council (NAAC) for 5 Years.</li>
    <li>SEC awarded AUTONOMOUS status by the UGC from the academic year 2019-2020. </li>
    <li>SEC is recognized as a Scientific and Industrial Research Organization (SIRO) by the Department of 
        Scientific and Industrial Research (DSIR), Government of India.
        Five Research Centres recognised by Anna University
        MoU's with Reputed Academic Institutions in India and Abroad </li>

    <Li>VISION</Li>
    <li>To be and to be recognized for setting the standard of excellence in engineering education and high 
        quality research in Science and Technology.</li>

    <li>MISSION</li>
    <li>To promote academic excellence; widen intellectual horizon; self-discipline and high ideals for the 
        total personality development of the individual.</li>

        <a href="https://www.saveetha.ac.in/">SEC Home Page</a>
  </ul>
  </body>
  </html>
  ```

  # OUTPUT:
  ![Alt text](<7-1 website.png>)

  ![Alt text](7-1.png)

  ![Alt text](<7-1 dark.png>)

  ## RESULT:
  Therefore the code has been successfully executed.



## 7-II-CSS
# AIM:
To use a media query in CSS to apply different styles to a webpage for mobile devices (with widths less than 600px) and desktop devices (with widths greater than or equal to 600px) by providing an example CSS snippet to demonstrate your answer.

# PROCEDURE:
## STEP 1:
Start the HTML document.
## STEP 2:
Inside the html document, create the element and include a style element for CSS rules.
## STEP 3:
Define CSS rules for desktop devices. Use a media query to define CSS rules for mobile devices.
## STEP 4:
Create the element inside , which will contain the webpage content.
## STEP 5:
Inside the html document, create head tag for the heading and an a tag for the list of hyperlinks.
## STEP 6:
End the HTML document by closing all open tags.


# CODE:
```<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    /* CSS rules for desktop devices */
    body {
        background-color: lightblue;
    }

    /* CSS rules for mobile devices */
    @media only screen and (max-width: 600px) {
        body {
            background-color: lightgreen;
        }
    }
</style>
</head>
<body>
    <div>
    Saveetha Engineering College
  </div>
  <ul>
    <li>Saveetha Engineering College (SEC) was established in 2001, by the Founder Chairman Dr. N. M. Veeraiyan, 
        a committed and dedicated Medical Professional.</li>
    <li>SEC has a total strength of 4349 students in 15 UG courses, 8 PG Courses including MBA, 
        MS by Research and Doctoral programs (PhD)  in five Departments.</li>
    <li>National Board of Accredition NBA has Accredited 5 UG courses.</li>
    <li>Ranked 96 by NIRF- National Institute Ranking Framework for the academic year 2017-18 among all IITs, 
        Central, State and Private Institutions in India. </li>
    <li>Awarded 'A' GRADE with a high score of 3.19 on a scale of 4 by the National Assessment and Accreditation 
        Council (NAAC) for 5 Years.</li>
    <li>SEC awarded AUTONOMOUS status by the UGC from the academic year 2019-2020. </li>
    <li>SEC is recognized as a Scientific and Industrial Research Organization (SIRO) by the Department of 
        Scientific and Industrial Research (DSIR), Government of India.
        Five Research Centres recognised by Anna University
        MoU's with Reputed Academic Institutions in India and Abroad </li>

    <Li>VISION</Li>
    <li>To be and to be recognized for setting the standard of excellence in engineering education and high 
        quality research in Science and Technology.</li>

    <li>MISSION</li>
    <li>To promote academic excellence; widen intellectual horizon; self-discipline and high ideals for the 
        total personality development of the individual.</li>

        <a href="https://www.saveetha.ac.in/">SEC Home Page</a>
  </ul>
  </body>
  </html>
  ```

# OUTPUT:
![Alt text](<7-2 wesite.png>)

![Alt text](7-2mobile.png)


  ## RESULT:
  Therefore the code has been successfully executed.



## 7-III-CSS ORIENTATION-BASED MEDIA QUERY
## AIM:
To explain how you can use CSS media queries to apply different styles based on the orientation (landscape or portrait) of the device. Provide a CSS example where you change the background color of the body based on the orientation.

## PROCEDURE:
# STEP 1:
Identify the section in your HTML file where you want to add the CSS. This is typically within the style tags in the section.
# STEP 2:
Define a CSS media query for each orientation. The syntax for a media query is @media (orientation: value), where value can be either portrait or landscape.
# STEP 3:
Within each media query, specify the CSS rules you want to apply. In this case, you want to change the background color of the body.
# STEP 4:
Close the media query with a }.
# STEP 5:
Repeat steps 2-4 for the other orientation.
# STEP 6:
Save your HTML file.
# STEP 7:
Open your HTML file in a web browser and change the orientation of your device to see the different styles applied.

## CODE:
```<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    @media (orientation: portrait) {
        body {
            background-color: rgb(228, 236, 192);
        }
    }

    @media (orientation: landscape) {
        body {
            background-color: rgb(235, 144, 238);
        }
    }
</style>
</head>
<body>
    <div>
    Saveetha Engineering College
  </div>
  <ul>
    <li>Saveetha Engineering College (SEC) was established in 2001, by the Founder Chairman Dr. N. M. Veeraiyan, 
        a committed and dedicated Medical Professional.</li>
    <li>SEC has a total strength of 4349 students in 15 UG courses, 8 PG Courses including MBA, 
        MS by Research and Doctoral programs (PhD)  in five Departments.</li>
    <li>National Board of Accredition NBA has Accredited 5 UG courses.</li>
    <li>Ranked 96 by NIRF- National Institute Ranking Framework for the academic year 2017-18 among all IITs, 
        Central, State and Private Institutions in India. </li>
    <li>Awarded 'A' GRADE with a high score of 3.19 on a scale of 4 by the National Assessment and Accreditation 
        Council (NAAC) for 5 Years.</li>
    <li>SEC awarded AUTONOMOUS status by the UGC from the academic year 2019-2020. </li>
    <li>SEC is recognized as a Scientific and Industrial Research Organization (SIRO) by the Department of 
        Scientific and Industrial Research (DSIR), Government of India.
        Five Research Centres recognised by Anna University
        MoU's with Reputed Academic Institutions in India and Abroad </li>

    <Li>VISION</Li>
    <li>To be and to be recognized for setting the standard of excellence in engineering education and high 
        quality research in Science and Technology.</li>

    <li>MISSION</li>
    <li>To promote academic excellence; widen intellectual horizon; self-discipline and high ideals for the 
        total personality development of the individual.</li>

        <a href="https://www.saveetha.ac.in/">SEC Home Page</a>
  </ul>
  </body>
  </html>
  ```

# OUTPUT:
![Alt text](7-3website.png)

![Alt text](7-3mobile.png)


  ## RESULT:
  Therefore the code has been successfully executed.



## 7-IV-CSS RESPONSIVE TYPOGRAPHY
## AIM:
To describe how you would use media queries to adjust typography (like font size and line spacing) on a website to improve readability across different device sizes, from mobile phones to large desktop monitors. Include a CSS code snippet in your explanation.

# PROCEDURE:
## STEP 1:
Identify the HTML elements you want to style. In your case, it’s the div and li elements.
## STEP 2:
Define the base styles for these elements. This will be the default styling that applies when no media queries match.
## STEP 3:
Use media queries to apply different styles for different device sizes. The @media rule is used in CSS to apply styles for specific media types/devices.
## STEP 4:
Inside the media queries, specify the device size for which the styles should apply. You can use min-width and max-width properties to target devices with widths within a certain range.
## STEP 5:
Adjust Typography: Inside each media query block, adjust the typography (like font size and line spacing) for the identified elements.
## STEP 6:
Test Your Styles.
## STEP 7:
Iterate: Adjust your media queries and styles as needed based on your tests.


# CODE:
```
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    div, li {
        font-size: 16px;
        line-height: 1.5;
    }

    @media screen and (min-width: 600px) {
        div, li {
            font-size: 18px;
            line-height: 1.6;
        }
    }

    @media screen and (min-width: 900px) {
        div, li {
            font-size: 20px;
            line-height: 1.7;
        }
    }

    @media screen and (min-width: 1200px) {
        div, li {
            font-size: 22px;
            line-height: 1.8;
        }
    }
</style>
</head>
<body>
    <div>
    Saveetha Engineering College
  </div>
  <ul>
    <li>Saveetha Engineering College (SEC) was established in 2001, by the Founder Chairman Dr. N. M. Veeraiyan, 
        a committed and dedicated Medical Professional.</li>
    <li>SEC has a total strength of 4349 students in 15 UG courses, 8 PG Courses including MBA, 
        MS by Research and Doctoral programs (PhD)  in five Departments.</li>
    <li>National Board of Accredition NBA has Accredited 5 UG courses.</li>
    <li>Ranked 96 by NIRF- National Institute Ranking Framework for the academic year 2017-18 among all IITs, 
        Central, State and Private Institutions in India. </li>
    <li>Awarded 'A' GRADE with a high score of 3.19 on a scale of 4 by the National Assessment and Accreditation 
        Council (NAAC) for 5 Years.</li>
    <li>SEC awarded AUTONOMOUS status by the UGC from the academic year 2019-2020. </li>
    <li>SEC is recognized as a Scientific and Industrial Research Organization (SIRO) by the Department of 
        Scientific and Industrial Research (DSIR), Government of India.
        Five Research Centres recognised by Anna University
        MoU's with Reputed Academic Institutions in India and Abroad </li>

    <Li>VISION</Li>
    <li>To be and to be recognized for setting the standard of excellence in engineering education and high 
        quality research in Science and Technology.</li>

    <li>MISSION</li>
    <li>To promote academic excellence; widen intellectual horizon; self-discipline and high ideals for the 
        total personality development of the individual.</li>

        <a href="https://www.saveetha.ac.in/">SEC Home Page</a>
  </ul>
  </body>
  </html>
  ```

  ## OUTPUT:
![Alt text](7-4website.png)

![Alt text](7-4mobile.png)


## RESULT:
  Therefore the code has been successfully executed.





# 7-V-PRINT-FRIENDLY CSS
## AIM:
To use a media query to change the styling of a webpage when it is printed, such as changing the background to white and hiding non-essential elements. Provide a CSS example.

## PROCEDURE:
# STEP 1:
Identify the HTML elements you want to style. In your case, it’s the div and li elements.
# STEP 2:
Define the base styles for these elements. This will be the default styling that applies when no media queries match.
# STEP 3:
Use media queries to apply different styles for different media types. The @media rule is used in CSS to apply styles for specific media types/devices.
# STEP 4:
Inside the media queries, specify the media type for which the styles should apply. You can use print to target printers.
# STEP 5:
Adjust Styles: Inside each media query block, adjust the styles for the identified elements. You can change the background to white and hide non-essential elements.
# STEP 6:
Test your styles using the print preview feature in browsers to ensure they work as expected.
# STEP 7:
Iterate: Adjust your media queries and styles as needed based on your tests.

## CODE:
```
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    div, li {
        font-size: 16px;
        line-height: 1.5;
    }

    @media print {
        body {
            background-color: white;
        }

        div, li {
            font-size: 12px;
            line-height: 1.4;
        }

        /* Add any non-essential elements you want to hide when printing */
        .non-essential {
            display: none;
        }
    }
</style>
</head>
<body>
    <div>
    Saveetha Engineering College
  </div>
<html>
<head>
<style type="text/css">
    div, li {
        font-size: 16px;
        line-height: 1.5;
    }

    @media print {
        body {
            background-color: white;
        }

        div, li {
            font-size: 12px;
            line-height: 1.4;
        }

        /* Add any non-essential elements you want to hide when printing */
        .non-essential {
            display: none;
        }
    }
</style>
</head>
<body>
    <div>
        Saveetha Engineering College
      </div>
      <ul>
        <li>Saveetha Engineering College (SEC) was established in 2001, by the Founder Chairman Dr. N. M. Veeraiyan, 
            a committed and dedicated Medical Professional.</li>
        <li>SEC has a total strength of 4349 students in 15 UG courses, 8 PG Courses including MBA, 
            MS by Research and Doctoral programs (PhD)  in five Departments.</li>
        <li>National Board of Accredition NBA has Accredited 5 UG courses.</li>
        <li>Ranked 96 by NIRF- National Institute Ranking Framework for the academic year 2017-18 among all IITs, 
            Central, State and Private Institutions in India. </li>
        <li>Awarded 'A' GRADE with a high score of 3.19 on a scale of 4 by the National Assessment and Accreditation 
            Council (NAAC) for 5 Years.</li>
        <li>SEC awarded AUTONOMOUS status by the UGC from the academic year 2019-2020. </li>
        <li>SEC is recognized as a Scientific and Industrial Research Organization (SIRO) by the Department of 
            Scientific and Industrial Research (DSIR), Government of India.
            Five Research Centres recognised by Anna University
            MoU's with Reputed Academic Institutions in India and Abroad </li>
    
        <Li>VISION</Li>
        <li>To be and to be recognized for setting the standard of excellence in engineering education and high 
            quality research in Science and Technology.</li>
    
        <li>MISSION</li>
        <li>To promote academic excellence; widen intellectual horizon; self-discipline and high ideals for the 
            total personality development of the individual.</li>
    
            <a href="https://www.saveetha.ac.in/">SEC Home Page</a>
      </ul>

  </body>
  </html>
  ```

  ## OUTPUT:
  ![Alt text](7-5website.png)

  ![Alt text](7-5print.png)


  ## RESULT:
  Therefore the code has been successfully executed.



## 7-VI-DARK MODE IMPLEMENTATION
## AIM:
With the increasing popularity of dark mode in user interfaces, explain how you would use a media query to detect if the user has set their system to prefer a dark color scheme. Provide an example of how you would change the background and text colors of a website based on this preference.

# PROCEDURE:
## STEP 1:
Use the prefers-color-scheme media feature, which is used to detect if the user has requested the system use a light or dark color theme.
## STEP 2:
The prefers-color-scheme media feature can have the values light, dark, or no-preference.
## STEP 3:
In your CSS, you can use this feature within a @media rule to apply different styles depending on the user’s preference.
## STEP 4:
You can set the background color to black and the text color to white when the user prefers a dark color scheme.
## STEP 5:
Conversely, you can set the background color to white and the text color to black when the user prefers a light color scheme.
## STEP 6:
If the user has no preference, you can choose a default color scheme.
## STEP 7:
Remember to test your website in both light and dark modes to ensure the colors work well in both settings.


## CODE:
```
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    body {
        background-color: white;
        color: black;
    }
    @media (prefers-color-scheme: dark) {
        body {
            background-color: black;
            color: white;
        }
    }
    @media (prefers-color-scheme: light) {
        body {
            background-color: white;
            color: black;
        }
    }
</style>
</head>
<body>
    <div>
    Saveetha Engineering College
  </div>
  <ul>
    <li>Saveetha Engineering College (SEC) was established in 2001, by the Founder Chairman Dr. N. M. Veeraiyan, 
        a committed and dedicated Medical Professional.</li>
    <li>SEC has a total strength of 4349 students in 15 UG courses, 8 PG Courses including MBA, 
        MS by Research and Doctoral programs (PhD)  in five Departments.</li>
    <li>National Board of Accredition NBA has Accredited 5 UG courses.</li>
    <li>Ranked 96 by NIRF- National Institute Ranking Framework for the academic year 2017-18 among all IITs, 
        Central, State and Private Institutions in India. </li>
    <li>Awarded 'A' GRADE with a high score of 3.19 on a scale of 4 by the National Assessment and Accreditation 
        Council (NAAC) for 5 Years.</li>
    <li>SEC awarded AUTONOMOUS status by the UGC from the academic year 2019-2020. </li>
    <li>SEC is recognized as a Scientific and Industrial Research Organization (SIRO) by the Department of 
        Scientific and Industrial Research (DSIR), Government of India.
        Five Research Centres recognised by Anna University
        MoU's with Reputed Academic Institutions in India and Abroad </li>

    <Li>VISION</Li>
    <li>To be and to be recognized for setting the standard of excellence in engineering education and high 
        quality research in Science and Technology.</li>

    <li>MISSION</li>
    <li>To promote academic excellence; widen intellectual horizon; self-discipline and high ideals for the 
        total personality development of the individual.</li>

        <a href="https://www.saveetha.ac.in/">SEC Home Page</a>
  </ul>
  </body>
  </html>
  ```

  ## OUTPUT:
  ![Alt text](7-6light.png)
  
  ![Alt text](7-6dark.png)


## RESULT:
  Therefore the code has been successfully executed.







