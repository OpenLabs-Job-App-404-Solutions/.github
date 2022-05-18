#### OpenLabs JobUp App Challenge Open Source Project Instructions and Overview

![](https://github.com/OpenLabs-Job-App-404-Solutions/.github/blob/main/jobUp.jpeg)


# OpenLabs JobUp App Challenge - 404 Solutions


Successful development teams establish goals at the beginning of each project, and constantly communicate with members from other teams to manage dependencies at each iteration. We support each other to solve problems at a much faster pace. Which in turn, helps the system sprint in quality, measurable increments.

![](https://github.com/OpenLabs-Job-App-404-Solutions/.github/blob/main/404.jpeg)

Namely: 
# Godfred Addai Amoako - Project Manager & Product Designer
# Safana - Backend Development 
# Marvin - Nothing 
# Elliot - Android Developer 
# Kevin Awuku - React



**Description**:Job Up App purposes is that, OpenLabs Students, Alumni can easily apply for intership and jobs, as school admininstation manages its smoothy with a few clicks

Other things to include:
 

<h3 align="left">
  - **Technology stack**:</h3>
<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://kotlinlang.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> </p>


  - **Status**:  Alpha, Beta, 1.1, This is the first version of JobUp; The goal is to let interested people exprience the user intreactive of this project, as they will be signUp/SigniN and apply for jobs/interns on sample company data.
  - **Routes of the the Backend **
  - Jobs Up
 

Routes

You're to test your app on this 

Blog 

GET localhost:/
GET localhost:/blogs Auth{basic}
POST localhost:/blogs Auth{Super Admin}
PATCH localhost:/blogs Auth{Super Admin}
DELETE localhost:blogiD Auth{Super Admin}


Admin

GET localhost: /company/confirm Auth{Admin}
GET localhost: /alumni/confirm Auth{Admin}
GET localhost: /student/confirm Auth{Admin}

POST localhost: /company/profile/verified Auth{Admin}
POST localhost: /alumni/profile/verified Auth{Admin}
PATCH localhost: /company/profile/Verified Auth{Admin}

DELETE localhost: /company/profile Auth{Admin}
DELETE localhost: /alumni/profile Auth{Admin}
DELETE localhost: /student/profile Auth{Admin}

Company 
GET localhost:/ Dashboard Auth{Company , } 
POST  localhost:/ Dashboard/Jobs Auth{Company }
PATCH  localhost:/ Dashboard/Jobs Auth{Company , } 


Alumni & Ally 

POST localhost: /alumni/confirmCert/ Auth{Basic}
PATCH localhost: /alumni /confirmCert/ Auth{basic }

POST localhost: /ally/institutionalCode/ Auth{Admin}
DELETE localhost: /ally /institutionalCode/ Auth{Admin }



Jobs 
GET localhost:/ Jobs Auth{Basic} 
GET  localhost: /Job/Find Auth{All}
GET  localhost: /Job/Find/JobiD Auth{All}
POST localhost: /Job/Apply Auth{Alumni, Students}
PATCH localhost: /Job/Apply Auth{Alumni, Students}
DELETE localhost: /Job/Apply Auth{Alumni, Students}

GET localhost:/Company Auth{All} 
GET localhost:/Company/profile Auth{All} 
GET  localhost: /Company/Find Auth{All}
GET  localhost: /Company/Find/CompanyiD Auth{All}


User
GET localhost:/User/SignUp Auth{All}
POST localhost:/User/SignUp Auth{All}
POST localhost:/User/SignIn/token Auth{All}
GET localhost:/User/ResetPass/ Auth{All}
POST localhost:/User/ResetPass/ Auth{All}



FeedBack 
POST localhost:/ Feedback Auth{Company , Alumni, Students } 
GET  localhost:/ Feedback/Jobs Auth{Super Admin }




**Screenshot**: If the software has visual components, place a screenshot after the description; e.g.,

![](https://github.com/OpenLabs-Job-App-404-Solutions/.github/blob/main/signUp.jpeg)
![](https://github.com/OpenLabs-Job-App-404-Solutions/.github/blob/main/email%20verification.jpeg)
![](https://github.com/OpenLabs-Job-App-404-Solutions/.github/blob/main/mesage.jpeg)
![](https://github.com/OpenLabs-Job-App-404-Solutions/.github/blob/main/WhatsApp%20Image%202022-05-18%20at%209.42.13%20AM.jpeg)
![](https://github.com/OpenLabs-Job-App-404-Solutions/.github/blob/main/WhatsApp%20Image%202022-05-18%20at%209.42.13%20AM%20(1).jpeg)
![](https://github.com/OpenLabs-Job-App-404-Solutions/.github/blob/main/WhatsApp%20Image%202022-05-18%20at%209.42.12%20AM.jpeg)



## Installation

Detailed instructions on how to install, configure, and get the project running will be given to school management after we win.
You can download this buggy app for now and test our User Interactions of The Job App
[INSTALL](https://drive.google.com/file/d/1z1e-r0tn_mpX2Tl_0QtDg0uw36Z_bofG/view?usp=sharing) Android App .

## Android Architure 
Model-View-ViewModel (ie MVVM) is a template of a client application architecture, proposed by John Gossman as an alternative to MVC and MVP patterns when using Data Binding technology. Its concept is to separate data presentation logic from business logic by moving it into particular class for a clear distinction. 
![](https://github.com/OpenLabs-Job-App-404-Solutions/.github/blob/main/mvvm2.png)

If the software is configurable, describe it in detail, either here or in other documentation to which you link.

## Usage

Show users how to use the software.
Be specific.
Use appropriate formatting when showing code snippets.

## How to test the software

If the software includes automated tests, detail how to run those tests.

## Known issues

Document any known significant shortcomings with the software.

## Getting help

Instruct users how to get help with this software; this might include links to an issue tracker, wiki, mailing list, etc.

**Example**

If you have questions, concerns, bug reports, etc, please file an issue in this repository's Issue Tracker.

## Getting involved

OpenLabs JobUp challenge 404 Solutions is the best, as it focus on solving internship dfiiculties as the school and easily 
auotmate redaunant works, send me a private mail if you want to contribute to this. 


General instructions on _how_ to contribute should be stated with a link to [CONTRIBUTING](CONTRIBUTING.md).


----

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)


----
