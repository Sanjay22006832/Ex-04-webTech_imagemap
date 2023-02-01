# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1
Clone the github repository into Theia IDE .
## Step 2
Create a new django project.
## Step 3
Write the needed HMTL code.
## Step 4
Run the Django server and execute the HTML FILES.

# Code:

```map.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>My College</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>SAVEETHA ENGINEERING COLLEGE</b></font>
</h1>
<h3 align="center">
<font color="blue"><SANJAY(22006832)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCollege" height="580" width="1100">
<map name="MyCollege">
<area shape="rectangle" coords="208,366,57,163" href="/static/html/eee.html" title="EEE BLOCK" target="_blank">
<area shape="rectangle" coords="163,706,323,495" href="/static/html/ece.html" title="ECE BLOCK" target="_blank">
<area shape="rectangle" coords="350,746,555,551" href="/static/html/admin.html" title="ADMIN BLOCK" target="_blank">
<area shape="rectangle" coords="630,697,790,486" href="/static/html/cse.html" title="CSE/IT BLOCK" target="_blank">
</map>
</center>
</body>
</html>

eee.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>EEE BLOCK</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="green"><b>SAVEETHA ENGINEERING COLLEGE</b></font>
</h1>
<h3 align="center">
<font color="green"><b>ELECTRICAL AND ELECTRONICS DEPT</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="6">
The Department of Electrical & Electronics Engineering was started in the year 2002, with an intake of sixty students. 
The team of twenty two faculty members of this Department are well qualified and experienced. The Department currently has 
about 250 students from various states of India, including the North-Eastern states, who work together in a cordial atmosphere 
conducive to excellence in education. The Department of EEE is committed to achieving academic excellence in Electrical
Engineering and promoting R & D activities. The mission of this Department is to produce Engineers with self discipline,
high integrity and good personality by providing excellent engineering education and training.
</font>
</p>
</body>
</html>

ece.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>ECE BLOCK</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>SAVEETHA ENGINEERING COLLEGE</b></font>
</h1>
<h3 align="center">
<font color="red"><b>ECE BLOCK</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Arial" size="6">
<b>
The Department of Electronics and Communication Engineering was established in the year 2001 with an intake of 60 students. It was 
increased to 120 students in the year 2005-2006. In 2017-18 it is increased to 180. From 2017 it is increased to 300. Faculties have 
completed their Master’s degree, 33 of them are Doctorates and most of them are pursuing their Ph.D. Every year we are producing 90%
 graduands. Our vision is to develop, the department into a State of Art, with Centre of Excellence in Electronics and Communication 
 Engineering Education, on par with global standards.</b>
</font>
</p>a
</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>ADMIN BLOCK</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>SAVEETHA ENGINEERING COLLEGE</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ADMIN BLOCK</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Saveetha Engineering College is a co-educational Institution. The College is affiliated with Anna University, Chennai,
the largest technical university in India. Saveetha Engineering College is granted Autonomous status by University Grants
Commission., Affiliated to Anna University located in Chennai, India.It was founded in 2001 by the Saveetha Medical and
Educational Trust, a registered charitable society. Approved by the All India Council for Technical Education (AICTE), a
statutory body of the Government of India, and also by the Government of Tamil Nadu.

</font>
</p>
</body>
</html>

cse.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>CSE/IT BLOCK</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>SAVEETHA ENGINEERING COLLEGE</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CSE/IT BLOCK</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
The Department of Computer science and Engineering was established in the year 2001 with an intake of 60 students. It was 
increased to 120 students in the year 2005-2006. In 2017-18 it is increased to 180. Our Department offers B.E Computer science 
and Engineering, M.E Computer science and Engineering programs. The department has a team of 46 sincere, dedicated, competent
and experienced faculty with commitment to serve the college in achieving its goals. All have completed their master degrees,
14 of them are Doctorates and most of them are pursuing their Ph.D.s. Every year we are producing very good results
</font>
</p>
</body>
</html>
```

# Output:
![image](https://user-images.githubusercontent.com/119830477/215970105-da1ddc04-224f-464d-a0c6-29ac5455cd95.png)
![image](https://user-images.githubusercontent.com/119830477/215970130-35184114-466a-4cec-9c6f-29406b86342b.png)
![image](https://user-images.githubusercontent.com/119830477/215970148-d0f6273a-3637-44e6-ae6d-c77188ffcdc6.png)
![image](https://user-images.githubusercontent.com/119830477/215970160-352e3062-dfa1-44f0-87d6-62aa6e790415.png)
![image](https://user-images.githubusercontent.com/119830477/215970176-50215376-c091-4987-8510-1d9017a6c45a.png)
![image](https://user-images.githubusercontent.com/119830477/215970195-1d9c341c-8780-4113-bd68-fbd54453eb74.png)


# Result:
all done
