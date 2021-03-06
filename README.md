# 2021-1 Open Source Software Lab Final Project

## 21300717 Huiwon Jeong
Youtube link -> https://youtu.be/ExxEr70aK88
## What does this project do?
This project is designed to help you register for class.\
If there is a vacancy in the class, you can receive a notification via email.

## Structure & Process
A simple web server was implemented through an open-source web framework, "Flask", and the web was used to receive the necessary information from the user.
If you enter information about the class you want to enroll in via the web, the program reads the number of students currently enrolled in the class and limit number of students through crawling. After pressing a button on the web, all processes are implemented to operate through thread.

## Set up & Usage
0. Clone this repository and move to 'OSS_final' directory 

1. To install the required Python package, run the command below.
```
$ sudo apt-get update
```
```
$ sudo pip install -r requirements.txt
```
2. type gmail ID and App PW in task_mail.py file (How to make App PassWord? -> https://yeolco.tistory.com/93)
```
s.login('gmail ID', 'App PW')
```
3. Run server.py file
```
$ python3 server.py
```

4. Connect to Web and use it!
```
type 'raspberry ip address' + 'port number 5000(default)' in your browser
ex) 192.168.0.65:5000
```

* you need to type '분반' like 01, 02... not 1, 2

## Web image
![image](https://user-images.githubusercontent.com/61661237/121774548-deabf180-cbbd-11eb-8817-45f800f8f30c.png)

