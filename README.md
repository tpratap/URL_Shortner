# Welcome to URL Shortner!

This is web app  titled **[>URL_Shortner](https://hly.herokuapp.com/)**. A URL shortner is an online service that gives you a new, very short URL that is **easier to share**. It's not just useful with Twitter, but also with email, text messages, and any other situation where a long URL is unmanageable. 


## URL_Shortner 

This URL Shortner app is basically built using **[Django](https://www.djangoproject.com/)** (is a Python-based free and open-source web framework that follows the model–template–views architectural pattern). In this app, we generate random keys and mantain a **key-value pair** (or hash) where key as duplicate url  and value as original url.  Anyone visiting on that duplicate url is redirected to the original url.


# Technology Stack

 1. Python (3.10.0)
 2. Django, (a python web framework)  (3.2.9)
 3. HTML5
 4. CSS3
 5. GIT and Github
 6. Heroku
 7. SQLite3


##  Features 

1.  Authentication
2.  Custom URL
3.  Random URL Generation
4.  Number Of Visits
5.  Free URL Shortening
6.  Deletetion of previous URL


## How can I configure it on my local machine

 1.  **[Download](https://github.com/tpratap/URL_Shortner/archive/refs/heads/master.zip)** this zip file and unzip it.
 2. **[Download](https://www.python.org/ftp/python/3.10.0/python-3.10.0-amd64.exe)** and install python (3.10.0) and add path to your environment.
 3. It is better to create virtual environment for installing django, for  creating virtual environment [refer here](https://www.geeksforgeeks.org/creating-python-virtual-environment-windows-linux/).
	 1. Open command prompt ( or command line or terminal).
	  2. for windows, use command: **pip install virtualenvwrapper-win**
	  3. Then use command: **mkvirtualenv venv** to create a virtual environment titled 'venv'.
 4. Now, it' time to install django, to install django [refer here](https://docs.djangoproject.com/en/3.2/topics/install/) or follow these steps: 				
	  1. for windows, use command: **workon venv** to activate virtual environment.
	  2. Then install django using command: **pip install  django**.
 5. With Django Migrations, you can easily keep multiple databases in sync with your models. To apply migartions, 
	  1. Navigate to the folder where you have unzipped the app, you can [refer here ](https://www.computerhope.com/issues/ch000795.htm) if you want to know how to navigite using cmd or use command: **cd path** path can be like C:\Users\user\Downloads\url_shortner-master
	  2. Use command: ***python manage*.py migrate**.
	  3. Use command: ***python manage*.py makemigrations**.
 6. Now it's time to deploy the app locally, so use command: ***python manage*.py runserver**


##  How it works

Basically, when the URL shortner gives you your shortened URL, it **remembers** the full address. When other users go to the shortened URL, they will be automatically redirected to the full address.

The webpage will still exist at the longer URL—the shortened URL is simply a  **shortcut**  to make the link easier to manage.

## Let's shorten a URL!
Even if you've never shortened a URL, it's very easy. We're going to use >URL_Shortner, but the process will be similar when using other shortening services.
The basic process is to copy the long URL into the URL shortner, and it will give you a shorter URL. The exact steps are below:

 1. Go to any website (you can use this link if you want). Websites with
    longer URLs are the best candidates for URL shortening, although any
    site will work.
    
 2. Select the URL in the address bar and copy it. You can use the
    keyboard shortcut Ctrl+C  to copy it.
   
 3. Go to URL Shortner and signup, click on Dashboard paste the URL into
    the space provided, using the keyboard shortcut Ctrl+V to paste it.
    
 4. Click on Generate, shorten link will appear copy it and paste it in browser. 

##  So what can you do with a shortened URL?

URL shortners aren't just useful with Twitter. There are lots of situations where a shorter URL is more convenient:

-   **Emails**: Long URLS can sometimes wrap to two or more lines, which makes them unwieldy.
-   **Resumes and cover letters**: Shortened URLs can look a bit neater.
-   **Text messages**: Most text messages have a limit of 160 characters, making short URLs essential.
-   **Phones**: If you need to tell someone to go to a specific webpage, a shortened URL can save time and trouble.