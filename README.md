
We solemnly declare that this project report “(ONLINE STUDENT GRADING SYSTEM)” is the bonafide work done purely by us, carried out under the supervision of A.SIVA KRISHNA REDDY Assistant Professor towards partial fulfillment of the requirements of the Degree of BACHELOR OF TECHNOLOGY in Computer Science & Engineering from Jawaharlal Nehru Technological University, Ananthapur during the year 2018-2019.
It is further certified that this work has not been submitted, either in part of in full, to any other department of the Jawaharlal Nehru Technological University, or any other University, institution or elsewhere, or for publication in any form.



We express heartfelt gratitude towards our institution, PBR VISVODAYA INSTITUTE OF TECHNOLOGY & SCIENCE, KAVALI for giving me an opportunity for the successful completion of our degree.

We express great sense of gratitude and indebtedness to our beloved Chairman Mr. D. Vidyadhara kumar Reddy and Academic In-Charge  Dr. D. Prathyusha Reddi for promoting excellent academic environment in the course.

It  gives  us  immense  pleasure  to  express  my  gratitude  to  our  Principal
Dr. N. Seshaiah who gave an opportunity in completing this course.

We deeply express profound gratitude and wholehearted thanks to our beloved Head of the Department Dr. D. Srujan Chandra Reddy, Associate Professor, Department of Computer Science and Engineering, who provided us with necessary facilities, guidance and endless encouragement which helped us a lot in completing the project with in time.

We express great sense of gratitude and indebtedness to our beloved guide Mr. A. Siva Krishna Reddy, Assistant Professor for her inspiring guidance and her encouragement throughout the course and project.

We also express gratitude to our lecturers and lab coordinators, non-teaching staff and friends who directly or indirectly helped us in completing the project successfully and providing us with suitable suggestions and guidance throughout.








                           ONLINE STUDENT GRADING SYSTEM

ABSTRACT:
This paper presents an online grading system that was developed to collect, process, and return the grades produced by juries using a series of rubrics in a first year project-based design course. It discusses the design requirements, features, and implementation of the online grading system, as well as reactions from course faculty and staff members. It is shown that this system has a number of advantages over analog grading methods, including scalability, real-time feedback on the status of grading, the reduced potential for human error in compiling grades, the ability for jury members to grade remotely and to revise their grades after submission, the ability for course administrators to easily review grading results and remove statistical outliers from the score set the ability to return both provisional and final grades to the course faculty, staff, and students in a timely manner, and the ability to archive and export grading data for future use. Although the online system is a clear improvement over paper-based rubrics, it is also shown that small details can interfere with usability and thus user satisfaction and that compatibility with mobile devices is a necessary, but still unaddressed, requirements
Functionalities Provided By Grading System Are As Follows:
Provides the searching facilities based on various factors.such as examinations,marks,grades,evaluations.
College management system also sells the employees details online for students details  employees details,courses.
It trackes the all the information of students,papers,grades etc.
Manage the information of students
Manage the information of examinations
Manage the information of grades
                                                                                                             
                                                                                                         






LIST OF CONTENTS


CHAPTER NO.
TITLE
PAGE NO.
1
INTRODUCTION
1


1.1 Project Introduction
1


1.2 Problem Statement
1


               1.2.1 Purpose
1


               1.2.2 Features
2


               1.2.3 Implementation Of The Project
2


1.3 Existing System
2


               1.3.1 Drawbacks
3


1.4 Proposed System
3


               1.4.1 Advantages Of The Proposed System
3


1.5 Modules
4
2
SYSTEM REQUIREMENT SPECIFICATION
5


2.1 System Requirements
5


                2.1.1 Hardware Requirements
5


                2.1.2 Software Requirements
5
3
SYSTEM DESIGN
6


3.1 UML Diagrams
6


               3.1.1 Use Case Diagram
7


               3.1.2 Sequence Diagram
8


               3.1.3 Class Diagram
9


               3.1.4 Activity Diagram
10


3.2 Database Design
11
4
SYSTEM IMPLEMENTATION
12


4.1 About Front End
12


4.2 About The Back End
16


4.3 Coding
19
5
SCREEN SHOTS
36


5.1 Input Screens
36
6
REFERENCES
46



1. INTRODUCTION
PROJECT INTRODUCTION
This paper presents an online grading system that was developed to collect, process, and return the grades produced by juries using a series of rubrics in a first year project-based design course. It discusses the design requirements, features, and implementation of the online grading system, as well as reactions from course faculty and staff members. It is shown that this system has a number of advantages over analog grading methods, including scalability, real-time feedback on the status of grading, the reduced potential for human error in compiling grades, the ability for jury members to grade remotely and to revise their grades after submission, the ability for course administrators to easily review grading results and remove statistical outliers from the score set the ability to return both provisional and final grades to the course faculty, staff, and students in a timely manner, and the ability to archive and export grading data for future use. Although the online system is a clear improvement over paper-based rubrics, it is also shown that small details can interfere with usability and thus user satisfaction and that compatibility with mobile devices is a necessary, but still unaddressed, requirements.
1.2 PROBLEM STATEMENT
	The computerization of world becomes more and more important to develop the system like Online student grading system to collect, process, and return the grades produced by juries using a series of rubrics in a first year project-based design course. This will lead lot of manual maintains of records. To efficiently collect, process, and return the grades produced by juries we want to develop a system.
Purpose: 
The purpose of online student grading system is to collect, process, and return the grades produced by juries using a series of rubrics in a first year project-based design course. The main objective of online student grading system is to efficiently evaluate the candidate thoroughly through a fully automated system that not only saves lot of time but also gives fast results. 
1

Features
Provides the searching facilities based on various factors. Such as examinations, marks, grades, evaluations.
Student management system also sells the employees details online for student’s details employee’s details, courses.
It tracks the all the information of students, papers, grades etc.
Manage the information of students
Manage the information of examinations
Manage the information of grades
Implementation of the project: 
Finally the complete project implementation as a whole and verification of the complete project. 
The Risk driven spiral model, highlight the situations of the options and conditions to support the software to reprocess. Software quality can use as a unique or special goal of merging into product growth.
In spiral module the first stage is to prepare a plan to get the goals with these constraints, and then attempt to locate or remove all possible risks during care full analysis and if it is essential by creating a prototype. 
Company should decide which some risks won’t be ruled out. Else ignore the risk or stop the project or continue with that anyhow.  Finally, the outcome are evaluated and next phase design begins.
EXISTING SYSTEM:
In the current system, lot of manual work has been done to give grade to student by juries. This system requires more manpower to evaluate the student’s performances, and produce the appropriate grades. It takes lot of time to process.

11
SYSTEM IMPLEMENTATION
4.1.ABOUT FRONT END:
Why PHP?
PHP remains the most widespread and popular server-side programming language on the web. It is installed by most web hosts, has a simple learning curve, close ties with the MySQL database, and an excellent collection of libraries to cut your development time. PHP may not be perfect, but it should certainly be considered for your next web application. Both Yahoo and Facebook use it with great success.
Why Install PHP Locally?
Installing PHP on your development PC allows you to safely create and test a web application without affecting the data or systems on your live website. This article describes PHP installation as a module within the Windows version of Apache 2.2. Mac and Linux users will probably have it installed already.
All-in-One packages
There are some excellent all-in-one Windows distributions that contain Apache, PHP, MySQL and other applications in a single installation file, e.g. XAMPP (including a Mac version), WampServer and Web.Developer. There is nothing wrong with using these packages, although manually installing Apache and PHP will help you learn more about the system and its configuration options.
The PHP Installer
Although an installer is available from php.net, I would recommend the manual installation if you already have a web server configured and running.
Manual Installation
Manual installation offers several benefits:
backing up, reinstalling, or moving the web server can be achieved in seconds and you have more control over PHP and Apache configuration.
 
 
12
Step 1: download the files
Download the latest PHP 5 ZIP package from www.php.net/downloads.php
As always, virus scans the file and checks its MD5 checksum using a tool such as fsum.
Step 2: extract the files
We will install the PHP files to C:php, so create that folder and extract the contents of the ZIP file into it.
PHP can be installed anywhere on your system, but you will need to change the paths referenced in the following steps.
Step 3: configure php.ini
Copy C:phpphp.ini-recommended to C:phpphp.ini. There are several lines you will need to change in a text editor (use search to find the current setting).
Define the extension directory:
extension_dir = "C:phpext"
Enable extensions. This will depend on the libraries you want to use, but the following extensions should be suitable for the majority of applications (remove the semi-colon comment):
extension=php_curl.dll
extension=php_gd2.dll
extension=php_mbstring.dll
extension=php_mysql.dll
extension=php_mysqli.dll
extension=php_pdo.dll
extension=php_pdo_mysql.dll
extension=php_xmlrpc.dll
If you want to send emails using the PHP mail() function, enter the details of an SMTP server (your ISP’s server should be suitable):
13
[mail function]
; For Win32 only.
SMTP = mail.myisp.com
smtp_port = 25
; For Win32 only.
sendmail_from = my@emailaddress.com
Step 4: add C:php to the path environment variable
To ensure Windows can find PHP, you need to change the path environment variable. From the Control Panel, choose System, (then “Advanced system settings” in Vista), select the “Advanced” tab, and click the “Environment Variables” button.
Scroll down the System variables list and click on “Path” followed by the “Edit” button. Enter “;C:php” to the end of the Variable value line (remember the semi-colon).
 
 
 
 
 
 
 
 
 
 
 
 
 
14

Now OK your way out. You might need to reboot at this stage.
 
Step 5: configure PHP as an Apache module
Ensure Apache is not running (use “net stop Apache2.2” from the command line) and open its confhttpd.conf configuration file in an editor. The following lines should be changed:
Line 239, add index.php as a default file name:
DirectoryIndex index.php index.html
At the bottom of the file, add the following lines (change the PHP file locations if necessary):
 
15
# PHP5 module
LoadModule php5_module "c:/php/php5apache2_2.dll"
AddType application/x-httpd-php .php
PHPIniDir "C:/php"
Save the configuration file and test it from the command line (Start > Run > cmd):
cd Apache2bin 
httpd -t
Step 6: test a PHP file
Create a file named index.php in Apache’s web page root (either htdocs or D:WebPages) and add this code:
<?php phpinfo(); ?>
Ensure Apache has started successfully, open a web browser and enter the address http://localhost/. If all goes well, a “PHP version” page should appear showing all the configuration settings.
4.2 ABOUT THE BACK END:
MySQL
	MySQL, the foremost in style Open supply SQL management system, is developed, distributed, and supported by Oracle Corporation.  The MySQL information processing system (http://www.mysql.com/) provides the most recent info regarding MySQL software system. 
MySQL is a database management system:
	A information could be a structured assortment of knowledge. it should be something from an easy searching list to an image gallery or the Brobdingnagian amounts of data during a company network. 
To add, access, and method knowledge hold on during a electronic database, you wish a direction system like MySQL Server. Since computers area unit superb at handling giant amounts of knowledge, direction systems play a central role in computing, as standalone utilities, or as elements of alternative applications.
16

MySQL databases are relational:
	A knowledgebase stores data in separate tables instead of swing all the info in one massive storage room. The information structures square measure organized into physical files optimized for speed. The logical model, with objects like databases, tables, views, rows, and columns, offers a versatile programming setting. You started rules governing the relationships between totally different information fields, like matched, one-to-many, unique, needed or ex gratia, and “pointers” between totally different tables. The information enforces these rules, in order that with a well-designed information, your application ne'er sees inconsistent, duplicate, orphan, outdated, or missing information. 
	The SQL a part of “MySQL” stands for “Structured question Language”. SQL is that the commonest standardized language wont to access databases. 
	Looking on your programming setting, you would possibly enter SQL directly (for example, to come up with reports), infix SQL statements into code written in another language, or use a language-specific API that hides the SQL syntax. 
	SQL is outlined by the ANSI/ISO SQL normal. The SQL normal has been evolving since 1986 and several other versions exist. during this manual, “SQL-92” refers to the quality free in 1992, “SQL: 1999” refers to the quality free in 1999, and “SQL: 2003” refers to this version of the quality. we have a tendency to use the phrase “the SQL standard” to mean this version of the SQL normal at any time. 
MySQL software is Open Source:
	Open supply means it's potential for anyone to use and modify the code. Anybody will transfer the MySQL code from the net and use it while not paying something. If you want, you will study the ASCII text file and alter it to fit your wants. 
	The MySQL code uses the GPL (GNU General Public License), http://www.fsf.org/licenses/, to outline what you will and will not do with the code in several things. If you're feeling uncomfortable with the GPL or got to implant MySQL code into a poster application, you'll be able to purchase a commercially authorised version from North American country. See the MySQL Licensing summary for a lot of info (http://www.mysql.com/company/legal/licensing/). 

17
The MySQL Database Server is very fast, reliable, scalable, and easy to use:
	If that's what you're yearning for, you must provides it a attempt. MySQL Server will run well on a desktop or laptop computer, aboard your different applications, internet servers, and so on, requiring very little or no attention. If you dedicate a whole machine to MySQL, you'll change the settings to require advantage of all the memory, CPU power, and I/O capability obtainable. MySQL can even proportion to clusters of machines, networked along. you'll notice a performance comparison of MySQL Server with different information managers on our benchmark page. 
	MySQL Server was originally developed to handle massive databases abundant quicker than existing solutions and has been with success employed in extremely rigorous production environments for many years. though underneath constant development, MySQL Server nowadays offers an expensive and helpful set of functions. Its property, speed, and security create MySQL Server extremely suited to accessing databases on the web. 

MySQL Server works in client/server or embedded systems:
	The MySQL info computer code may be a client/server system that consists of a multi-threaded SQL server that supports completely different back ends, many completely different consumer programs and libraries, body tools, and a good vary of application programming interfaces (APIs). 
	We have a tendency to conjointly offer MySQL Server as associate degree embedded multi-threaded library that you just will link into your application to urge a smaller, faster, easier-to-manage standalone product. 
A large amount of contributed MySQL software is available:
	MySQL Server contains a sensible set of options developed in shut cooperation with our users. it's terribly possible that your favorite application or language supports the MySQL information Server.



18
4.3.CODING
Index.php
<?php
session_start();
error_reporting(0);
include('includes/config.php');
if($_SESSION['alogin']!=''){
$_SESSION['alogin']='';
}
if(isset($_POST['login']))
{
$uname=$_POST['username'];
$password=md5($_POST['password']);
$sql ="SELECT UserName,Password FROM admin WHERE UserName=:uname and Password=:password";
$query= $dbh -> prepare($sql);
$query-> bindParam(':uname', $uname, PDO::PARAM_STR);
$query-> bindParam(':password', $password, PDO::PARAM_STR);
$query-> execute();
$results=$query->fetchAll(PDO::FETCH_OBJ);
if($query->rowCount() > 0)
{
$_SESSION['alogin']=$_POST['username'];
echo "<script type='text/javascript'> document.location = 'dashboard.php'; </script>";
}
19
 else{
        echo "<script>alert('Invalid Details');</script>";
}
}
?>
<!DOCTYPE html>
<html lang="en">
    <head>
		 <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
    	<meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Admin Login</title>
        <link rel="stylesheet" href="css/bootstrap.min.css" media="screen" >
        <link rel="stylesheet" href="css/font-awesome.min.css" media="screen" >
        <link rel="stylesheet" href="css/animate-css/animate.min.css" media="screen" >
        <link rel="stylesheet" href="css/prism/prism.css" media="screen" > <!-- USED FOR DEMO HELP - YOU CAN REMOVE IT -->
        <link rel="stylesheet" href="css/main.css" media="screen" >
        <script src="js/modernizr/modernizr.min.js"></script>
    <style>
body {
    background-image: url("Bluei.jpg");
	 background-repeat: repeat-x;
}

20
</style>
</head>
    <body class="">
        <div class="main-wrapper">
            <div class="">
                <div class="row">
<h1 align="center"><font color="#ffffff"> Online Student Grading</font></h1>
                    <div class="col-lg-6 visible-lg-block">
<section class="section">
                            <div class="row mt-40">
                                <div class="col-md-10 col-md-offset-1 pt-50">
                                    <div class="row mt-30 ">
                                        <div class="col-md-11">
                                            <div class="panel">
                                                <div class="panel-heading">
                                                    <div class="panel-title text-center">
                                                        <h4>Students</h4>
                                                    </div>
                                                </div>
                                                <div class="panel-body p-20">
                                                    <div class="section-title">
                                                        <p class="sub-title"></p>
                                                    </div>
                                                    <form class="form-horizontal" method="post">
                                                        <div class="form-group"> 
                                                           <label for="inputEmail3" class="col-sm-6 control-label">Search your result</label>
                                                            <div class="col-sm-6">
                                                              <input type="button" onclick="location.href='find-result.php';" value="click here" />
                                                            </div>
                                                        </div>
                                                    </form>
                                                </div>
                                            </div>
                                            <!-- /.panel -->
                                      
                                        </div>
                                        <!-- /.col-md-11 -->
                                    </div>
                                    <!-- /.row -->
                                </div>
                                <!-- /.col-md-12 -->
                            </div>
                            <!-- /.row -->
                        </section>
                    </div>
                    <div class="col-lg-6">
                        <section class="section">
                            <div class="row mt-40">
<div class="col-md-10 col-md-offset-1 pt-50">
                                    <div class="row mt-30 ">
                                        <div class="col-md-11">
                                            <div class="panel">
                                                <div class="panel-heading">
                                                    <div class="panel-title text-center">
                                                        <h4>Admin Login</h4>
                                                    </div>
                                                </div>
                                                <div class="panel-body p-20">

                                                    <div class="section-title">
                                                        <p class="sub-title">Online student grading</p>
                                                    </div>
                                                    <form class="form-horizontal" method="post">
                                                    	<div class="form-group">
                                                    		<label for="inputEmail3" class="col-sm-2 control-label">Email</label>
                                                    		<div class="col-sm-10">
                                                    			<input type="text" name="username" class="form-control" id="inputEmail3" placeholder="UserName">
                                                    		</div>
                                                    	</div>
                                                    	<div class="form-group">
23
                                                    		<label for="inputPassword3" class="col-sm-2 control-label">Password</label>
                                                    		<div class="col-sm-10">
                                                    			<input type="password" name="password" class="form-control" id="inputPassword3" placeholder="Password">
                                                    		</div>
                                                    	</div>
                                                              <div class="form-group mt-20">
                                                    		<div class="col-sm-offset-2 col-sm-10">
                                                                     			<button type="submit" name="login" class="btn btn-success btn-labeled pull-right">Sign in<span class="btn-label btn-label-right"><i class="fa fa-check"></i></span></button>
                                                    		</div>
                                                    	</div>
                                                    </form>
                                          </div>
                                            </div>
                                            <!-- /.panel -->
                                            <p class="text-muted text-center"><small>Copyright © OSGS</small></p>
                                        </div>
                                        <!-- /.col-md-11 -->
                                    </div>
                                    <!-- /.row -->
                                </div>
24
<!-- /.col-md-12 -->
                            </div>
                            <!-- /.row -->
                        </section>
                    </div>
                    <!-- /.col-md-6 -->
                </div>
                <!-- /.row -->
            </div>
            <!-- /. -->
        </div>
        <!-- /.main-wrapper -->
        <!-- ========== COMMON JS FILES ========== -->
        <script src="js/jquery/jquery-2.2.4.min.js"></script>
        <script src="js/jquery-ui/jquery-ui.min.js"></script>
        <script src="js/bootstrap/bootstrap.min.js"></script>
        <script src="js/pace/pace.min.js"></script>
        <script src="js/lobipanel/lobipanel.min.js"></script>
        <script src="js/iscroll/iscroll.js"></script>
        <!-- ========== PAGE JS FILES ========== -->
        <!-- ========== THEME JS ========== -->
        <script src="js/main.js"></script>
        


25
<script>
            $(function(){
            });
        </script>
        <!-- ========== ADD custom.js FILE BELOW WITH YOUR CHANGES ========== -->
    </body>
</html>
result.php
<?php
session_start();
error_reporting(0);
include('includes/config.php');
?>
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
    	<meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Result</title>
        <link rel="stylesheet" href="css/bootstrap.min.css" media="screen" >
        <link rel="stylesheet" href="css/font-awesome.min.css" media="screen" >
        <link rel="stylesheet" href="css/animate-css/animate.min.css" media="screen" >
        <link rel="stylesheet" href="css/lobipanel/lobipanel.min.css" media="screen" >
26
<link rel="stylesheet" href="css/prism/prism.css" media="screen" >
        <link rel="stylesheet" href="css/main.css" media="screen" >
        <script src="js/modernizr/modernizr.min.js"></script>
		<style>
body {
    background-image: url("Bluei.jpg");
	 background-repeat: repeat-x;
}
</style>
    </head>
    <body>
        <div class="main-wrapper">
            <div class="content-wrapper">
                <div class="content-container">
                    <!-- /.left-sidebar -->
                    <div class="main-page">
                        <div class="container-fluid">
                            <div class="row page-title-div">
                                <div class="col-md-12">
                                    <h2 class="title" align="center">Result</h2>
                                </div>
                            </div>
                            <!-- /.row -->
                          <!-- /.row -->
 </div>
                        <!-- /.container-fluid -->
                        <section class="section">
                            <div class="container-fluid">

                                <div class="row">
                                    <div class="col-md-8 col-md-offset-2">
                                        <div class="panel">
                                            <div class="panel-heading">
                                                <div class="panel-title">
<?php
// code Student Data
$rollid=$_POST['rollid'];
$classid=$_POST['class'];
$_SESSION['rollid']=$rollid;
$_SESSION['classid']=$classid;
$qery = "SELECT   tblstudents.StudentName,tblstudents.RollId,tblstudents.RegDate,tblstudents.StudentId,tblstudents.Status,tblclasses.ClassName,tblclasses.Section from tblstudents join tblclasses on tblclasses.id=tblstudents.ClassId where tblstudents.RollId=:rollid and tblstudents.ClassId=:classid ";
$stmt = $dbh->prepare($qery);
$stmt->bindParam(':rollid',$rollid,PDO::PARAM_STR);
$stmt->bindParam(':classid',$classid,PDO::PARAM_STR);
$stmt->execute();

28
$resultss=$stmt->fetchAll(PDO::FETCH_OBJ);
$cnt=1;
if($stmt->rowCount() > 0)
{
foreach($resultss as $row)
{   ?>
<p><b>Student Name :</b> <?php echo htmlentities($row->StudentName);?></p>
<p><b>Student Roll Id :</b> <?php echo htmlentities($row->RollId);?>
<p><b>Student Class:</b> <?php echo htmlentities($row->ClassName);?>(<?php echo htmlentities($row->Section);?>)
<?php }

    ?>
                                            </div>
                                            <div class="panel-body p-20">
                                                <table class="table table-hover table-bordered">
                                                <thead>
                                                        <tr>
                                                            <th>#</th>
                                                            <th>Subject</th>    
                                                            <th>Marks</th>
                                                        </tr>
                                               </thead>
  
                	
29
<tbody>
<?php                                              
// Code for result
 $query ="select t.StudentName,t.RollId,t.ClassId,t.marks,SubjectId,tblsubjects.SubjectName from (select sts.StudentName,sts.RollId,sts.ClassId,tr.marks,SubjectId from tblstudents as sts join  tblresult as tr on tr.StudentId=sts.StudentId) as t join tblsubjects on tblsubjects.id=t.SubjectId where (t.RollId=:rollid and t.ClassId=:classid)";
$query= $dbh -> prepare($query);
$query->bindParam(':rollid',$rollid,PDO::PARAM_STR);
$query->bindParam(':classid',$classid,PDO::PARAM_STR);
$query-> execute();  
$results = $query -> fetchAll(PDO::FETCH_OBJ);
$cnt=1;
if($countrow=$query->rowCount()>0)
{ 
foreach($results as $result){

    ?>
                         		<tr>
                                                <th scope="row"><?php echo htmlentities($cnt);?></th>
                                                			<td><?php echo htmlentities($result->SubjectName);?></td>
                                                			<td><?php echo htmlentities($totalmarks=$result->marks);?>

30
</td>
                                                		</tr>
<?php 
$totlcount+=$totalmarks;
$cnt++;}
?>
<tr>
                                                <th scope="row" colspan="2">Total Marks</th>
<td><b><?php echo htmlentities($totlcount); ?></b> out of <b><?php echo htmlentities($outof=($cnt-1)*100); ?></b></td>
                                                        </tr>
<tr>
                                                <th scope="row" colspan="2">Percntage</th>           
                                                            <td><b><?php echo  htmlentities($sridhar=$totlcount*(100)/$outof); ?> %&nbsp;&nbsp;&nbsp;</b>
<?php
$total=$sridhar;    
switch($total){    
case ($total>=100):    
echo("A+");    
break;    
case ($total>=95):    
echo("A");    
break;    
case ($total>=80):    

31
echo("B+");    
break;
case ($total>=85):    
echo("B");    
break;
case ($total>=70):    
echo("c+");    
break;
case ($total>=75):    
echo("c");    
break;
case ($total>=60):    
echo("D+");    
break;
case ($total>=65):    
echo("D");    
break;
default:    
echo("FAIl");    
} 
?>
</td>
                                                             </tr>
<tr>
                                               
32
 <th scope="row" colspan="2">Download Result</th>           
                                                            <td><b><a href="download-result.php">Download </a> </b></td>
                                                             </tr>
<?php } else { ?>     
<div class="alert alert-warning left-icon-alert" role="alert">
                                            <strong>Notice!</strong> Your result not declare yet
 <?php }
?>
                                        </div>
 <?php 
 } else
 {?>
<div class="alert alert-danger left-icon-alert" role="alert">
strong>Oh snap!</strong>
<?php
echo htmlentities("Invalid Roll Id");
 }
?>
                                        </div>
                                                	</tbody>
                                                </table>
                                            </div>
                                        </div>
                                        <!-- /.panel -->
33
</div>
                                    <!-- /.col-md-6 -->
                                    <div class="form-group">
                                                           
                                                            <div class="col-sm-6">
                                                               <a href="index.php">Back to Home</a>
                                                            </div>
                                                       </div>
                                </div>
                                <!-- /.row -->
                              </div>
                            <!-- /.container-fluid -->
                        </section>
                        <!-- /.section -->
                    </div>
                    <!-- /.main-page -->
                </div>
                <!-- /.content-container -->
            </div>
            <!-- /.content-wrapper -->
        </div>
        <!-- /.main-wrapper -->
        <!-- ========== COMMON JS FILES ========== -->
        <script src="js/jquery/jquery-2.2.4.min.js"></script>
        <script src="js/bootstrap/bootstrap.min.js"></script>
34
 <script src="js/pace/pace.min.js"></script>
        <script src="js/lobipanel/lobipanel.min.js"></script>
        <script src="js/iscroll/iscroll.js"></script>
        <!-- ========== PAGE JS FILES ========== -->
        <script src="js/prism/prism.js"></script>
        <!-- ========== THEME JS ========== -->
        <script src="js/main.js"></script>
        <script>
            $(function($) {
            });
        </script>
       <!-- ========== ADD custom.js FILE BELOW WITH YOUR CHANGES ========== -->
    </body>
</html>
REFERENCES
Text Books
Learning PHP, MySQL & JavaScript: With jQuery, CSS & HTML5 
Beginning PHP and MySQL: From Novice to Professional 5th ed. Edition
References
PHP Manual: Preface, www.php.net.
 "Introduction: What can PHP do?". PHP Manual. Retrieved 2009-03-05.
"Embedding PHP in HTML". O'Reilly. 2001-05-03. Retrieved 2008-02-25.
"Problems with PHP". Retrieved 20 December 2010.
 "php.internals: Re: Function name consistency". news.php.net. 2013-12-28. Retrieved 2014-02-09.
Rasmus Lerdorf (Dec 16, 2013). "Re: Flexible function naming". Newsgroup: php.internals. Retrieved December 26, 2013.
"PHP - Acronym Meaning Vote". PHP.net. Archived from the original on August 15, 2000.
"Zend Engine version 2.0: Feature Overview and Design". Zend Technologies Ltd. Retrieved 2006-09-17.
Websites
https://www.fromdev.com/2013/09/best-php-books.html
https://www.cloudways.com/blog/best-books-to-help-you-learn-php/
https://en.wikipedia.org/wiki/PHP
https://www.w3schools.com/php/
https://www.w3schools.co
