# Ex01 Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
</head>
<body> 
  <h1 align="center">
    Portfolio
  </h1>
  <table width="100%" bgcolor="#DFD7D2">
    <tbody>
    <tr>
      <td>
        <table align="center"cellspacing="0" width="80%" >
          <tbody >
          <tr >
            <td>
              <img src="./images/3 copy (1).jpg" width="70">
            </td>
            <td align="right">
              <h3>ANTO JESSI A</h3>
              B.E.CSE(3rd Year)
              <p><a href="mailto:antojessi266@gmail.com">Email Me!</a></p>
            </td>
          </tr>
        </tbody>
        </table>
      </td>
    </tr>
  </tbody>
  </table>
  
  <br>
  <table align="center" cellspacing="0" width="80%">
    <tbody>
    <tr bgcolor="lightgrey">
      <td align="center" id="Experience/Hobbies"><a href="#Experience/Hobbies">Experience/Hobbies |</a>
        <a href="#About Me">About |</a>
        <a href="#About Me">Contact</a</td>
    </tr>
    <tr>
      <td align="center"colspan="3"><h3> EXPERIENCE / HOBBIES</h3></td>
    </tr>
  </tbody>
  </table>
        <table align="center" cellspacing="0" width="80%">
          <tbody>
          <tr>
            <td>
              <p>
                   <img src="./images/Smart India Hackathon Ideathon - G-Code.png" width="300">
              <h3 align="center"><a href="certifications.html">Hackathon</a></h3>
              Participated in Hackathons,Ideathons,events</p>
            </td>
            <td align="center">
              <p>
              <img src="./images/Smart India Hackathon Ideathon - G-Code (1).png" width="300" >
              <h3 align="center" > Machine Learning</h3>
              Learnt Basics in Machine Learning
            </p>
            </td>
            <td align="right">
              <p>
              <img src="./images/Smart India Hackathon Ideathon - G-Code (2).png" width="300">
                <h3 align="center"><a href="photo.html">Photography</a></h3>
                Capturing the Details (NaturePhotography)
              </p>
            </td>
          </tr>

          <tr>
            <td colspan="3" align="center">
              <h3><a href="certifications.html">CERTIFICATIONS</a></h3>
            </td>
          </tr>

          <tr>
            <td>
                   <img src="./images/certificates/Screenshot 2024-08-11 171733.png" width="300">
              <h3 align="center">Social Emotional Learning</h3>
              <p align="center">IUCEE NEP Course </p>
            </td>
            <td align="center">
              <p>
              <img src="./images/certificates/Screenshot 2024-08-11 171321.png" width="300" >
              <h3 align="center" > Google Skill Boost</h3>
              Google Cloud Career Launchpad 
            </p>
            </td>
            <td align="right">
              <p>
              <img src="./images/certificates/Screenshot 2024-08-11 173707.png" width="300">
                <h3 align="center">AI & ML</h3>
                Completed One Month Internship
              </p>
            </td>
          </tr>
        </tbody>
      </table>
      <footer>
        <table width="100%" bgcolor="#DFD7D2">
          <tbody>
          <tr>
            <td>
              <table width="80%" align="center" cellspacing="0">
                <tbody>
                  <tr>
                    <td colspan="2"> <h3 align="center">About Me</h3></td>
                  </tr>
                  <tr>
                    <td bgcolor="white">
                      <h3 align="center" id="About Me">Personal Details</h3>
                      <ul>
                        <li>Anto Jessi A</li>
                        <li>Chennai</li>
                        <li>Student</li>
                        <li>Ph : 1234567890</li>
                      </ul>
                    </td>
                    <td bgcolor="#cBb7a6">
                      <h3 align="center" id="About Me">Education / Skillset</h3>
                      <ul>
                        <li>B.E.CSE(3rd Year)</li>
                        <li>HTML, CSS</li>
                        <li>Canva</li>
                        <li>C, Python, C++</li>
                      </ul>
                    </td>
                  </tr>
                  <tr>
                    <td><br><br></td>
                    <td></td>
                  </tr>
                </tbody>
              </table>
            </td>
          </tr>
        </tbody>
        </table>
        <br>
      </footer>
      <p align="center"> @Copyright 2024</p>
  
</body>
</html>
```

certifications.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1 align="center"><br>
        CERTIFICATIONS<br>
    </h1>
    <br>
    <table width="80%" align="center" cellspacing="30">
        <tbody align="center">
            <tr>
                <td >
                <img src="./images/certificates/Screenshot 2024-08-11 171539.png" width="500">
            </td>
            <td>
                <img src="./images/certificates/Screenshot 2024-08-11 171643.png" width="500">
            </td>
        </tr>
        <tr>
            <td >
            <img src="./images/certificates/Screenshot 2024-08-11 171849.png" width="500">
        </td>
        <td>
            <img src="./images/certificates/Screenshot 2024-08-11 171912.png" width="500">
        </td>
    </tr>
    <tr>
        <td >
        <img src="./images/certificates/Screenshot 2024-08-11 171410.png" width="500">
    </td>
    <td>
        <img src="./images/certificates/Screenshot 2024-08-11 171733.png" width="500">
    </td>
</tr>
<tr>
    <td >
    <img src="./images/certificates/Screenshot 2024-08-11 171321.png" width="500">
</td>
<td>
    <img src="./images/certificates/Screenshot 2024-08-11 171810.png" width="500">
</td>
</tr>
<tr>
    <td >
    <img src="./images/certificates/Screenshot 2024-08-11 174308.png" width="500">
</td>
<td>
    <img src="./images/certificates/Screenshot 2024-08-11 174322.png" width="500">
</td>
</tr>
<tr>
    <td>
        <img src="./images/certificates/Screenshot 2024-08-11 174405.png" width="500">
    </td>
    <td>
        <img src="./images/certificates/iete.jpg" width="500">
    </td>
</tr>
</tbody>
</table>
</body>
</html>
```

photo.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body >
    <h1 align="center"><br>
        Nature Photography<br>
    </h1>
    <br>

    <table width="80%" align="center" >
        <tbody align="center">
        <tr>
            <td >
                <img src="./photos/bitterguardflower.jpg" width="400">
            </td>
            <td>
                <img src="./photos/rain1.jpg" width="400">
            </td>
            
        </tr>
        <tr>
            <td >
                <img src="./photos/crow-lake-1.jpg" width="400">
            </td>
            <td >
                <img src="./photos/beachsunset.jpg" width="400">
            </td>
        </tr>
        <tr>
            <td >
                <img src="./photos/IMG20240502171553.jpg" width="400">
            </td>
            <td  >
                <img src="./photos/IMG_20240422_135253.jpg" width="400">
            </td>
        </tr>
        <tr>
            <td align="center" >
                <img src="./photos/kitty1-11.jpg" width="400">
            </td>
            <td  >
                <img src="./photos/pathway-1.jpg" width="400">
            </td>
        </tr>
        <tr>
            <td >
                <img src="./photos/planeLIGHTS-1.jpg" width="400">
            </td>
            <td>
                <img src="./photos/bevel white.jpg" width="400">
            </td>
        </tr>
        <tr>
            <td>
                <img src="./photos/skyMOONlight-1.jpg" width="400">
            </td>
            <td>
                <img src="./photos/IMG20240328175102.jpg"width="400" >
            </td>
        </tr>
        <tr>
            <td  >
                <img src="./photos/IMG20240501184654.jpg" width="400">
            </td>
            <td  >
                <img src="./photos/track-1.jpg" width="400">
            </td>
        </tr>
        <tr>
            <td></td>
            <td align="right">
                <p>- Anto Jessi A</p>
            </td>
        </tr>
        <tr >
           <td colspan="2" align="center">For More : <a href="https://www.instagram.com/treasures_of_nature_in_frame/">treasures_of_nature_in_frame</a>
            </td>
        </tr>
    </tbody>
    </table>
    
</body>
</html>
```


## OUTPUT
![image](https://github.com/user-attachments/assets/51c556ec-75a6-4578-ba6e-1978268131f8)
![image](https://github.com/user-attachments/assets/1b766fde-a2f2-411a-897f-96160c5bc654)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
