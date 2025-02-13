<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>
<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/kevin-christianto/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>
<div id="github" align="center">
    <img src="https://komarev.com/ghpvc/?username=kevhoz&style=flat-square&color=blue" alt=""/>
</div>
<div id="body-header" align="center">
<h1>
  Simple Unit Testing
</h1>
</div>
### :hammer_and_wrench: Languages and Tools:
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/php/php-original.svg" title="PHP"  alt="PHP" width="40" height="40"/>&nbsp;
</div>

### :woman_technologist: This repository cover:

1. Prepare The Environment.
2. Simple Case of Unit Testing.

<div id="prepare-environment">
<h2>
  Prepare The Environment
</h2>

What we need is:

PHP
  - You can install PHP from Xampp (apachefriends.org)
  - We need only PHP for this simple unit testing

Composer (getcomposer.org)
 - Go to the website, and install Composer
 - Sometimes need restart to finalize the installation

Get Development Ready and Install PHPUnit
- Create folder "testing" inside your root folder for web hosting (if xampp, then htdocs)
- Go inside the folder and create 2 folder (src and tests), like this structure:
```
-testing
--src
--tests
```
- Open CMD from inside the folder:

  ![image](https://github.com/user-attachments/assets/c30f7cc1-8aa7-46c9-9070-355314649707)

- Install PHPUnit library into the folder:
```
composer require --dev phpunit/phpunit ^10
```
- After installation done, final check on the folder will become like this:

  ![image](https://github.com/user-attachments/assets/cd3c0385-b0b8-49ff-aa67-d0a3f85b5e79)

- Installation done, continue to unit testing case

</div>

<div id="unit-testing-1">
<h2>
  Simple case 1: User Testing
</h2>

- Create 2 PHP file; "User.php" in src folder and "UserTest.php" in tests folder
- This is source code for User.php:

- This is source code for UserTest.php:


- Lets try test it: (To test all script inside folder tests)
```
./vendor/bin/phpunit --bootstrap vendor/autoload.php tests
```
- Lets try test it: (To test spesific script inside folder tests)
```
./vendor/bin/phpunit tests/UserTest.php
```
- Simple Case 1, Done

</div>

<div id="unit-testing-2">
<h2>
  Simple case 2: Calculator Testing
</h2>

- Create 2 PHP file; "Calculator.php" in src folder and "CalculatorTest.php" in tests folder
- This is source code for Calculator.php:

- This is source code for CalculatorTest.php:


- Lets try test it: (To test all script inside folder tests)
```
./vendor/bin/phpunit --bootstrap vendor/autoload.php tests
```
- Lets try test it: (To test spesific script inside folder tests)
```
./vendor/bin/phpunit tests/CalculatorTest.php
```
- Simple Case 2, Done

</div>

<div id="unit-testing-3">
<h2>
  Simple case 3: Student Testing
</h2>

- Create 3 PHP file; "Student.php" and "Course.php" in src folder and "StudentTest.php" in tests folder
- This is source code for Student.php:

- This is source code for Course.php:

- This is source code for StudentTest.php:


- Lets try test it: (To test all script inside folder tests)
```
./vendor/bin/phpunit --bootstrap vendor/autoload.php tests
```
- Lets try test it: (To test spesific script inside folder tests)
```
./vendor/bin/phpunit tests/StudentTest.php
```
- Simple Case 3, Done

</div>
