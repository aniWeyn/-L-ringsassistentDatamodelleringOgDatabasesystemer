# Datamodellering og Databasesystemer

## Assignment 1
### XAMPP Installation problems
#### XAMPP - Port 80 in use by “Unable to open process” with PID 4!
This solution will let you to develop with XAMPP and with Microsoft solutions (such as ISS and MS SQL)

##### Solution:
Set Apache to listen on a different port:
1. click on the "Config" button on the same line as the "Apache" module
2. select the "httpd.conf" file in the dropdown 
3. change the "Listen 80" line to "Listen 8080"
4. save the file and close it.

**phpMyAdmin page: http://localhost:8080/phpmyadmin/**

Source: https://stackoverflow.com/a/22357053

### Installing PHPUnit - Windows
Denne PCen -> Egenskaper -> Avanserte systeminnstillinger -> Miljøvariabler -> Brukervariabler for DinBrukerNavn -> Ny

Add this two path:
C:\bin
C:\xampp\php
