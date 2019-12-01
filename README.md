# Chat
The initialization of a simple chat application.
To get started with the app first of all make sure you have Python3 installed!

If not follow the link - https://www.python.org/ftp/python/3.8.0/python-3.8.0-macosx10.9.pkg

After that you have to do the following:
1. Open the Terminal or CMD by any means necessary.
2. Make sure you are at the correct directory. Otherwise change the working directory to the folder named “source”.
3. Run the following commands in the Terminal in the following order. This is done to ensure that all the required packages are installed:

pip3 install django

source ~/.virtualenvs/djangodev/bin/activate

pip3 install channels_redis

brew install redis

brew services start redis

4. For Windows users the way of installing and running redis can be simply googled.
5. And eventually type:
	python3 manage.py runserver
6. In the terminal space you should be seeing the clickable link in a form of http://127.0.0.1:8000/
7. The page consists of the two buttons. If you are a newcomer, you are recommended to click the first one.
8. After the registration you may now use the second button to login.
9. You may input any name for the chat you would like to enter and proceed now from the chat page.
10. The template you are seeing is not a working app. It is just a fancy looking page, the template for which was taken from “https://bootsnipp.com/tags/chat” and slightly modified for this app.
11. To log in as a different user you need to do steps 6-9, but at the step 9 you must enter the same chat name, where the previous user is in, to make them chat together.
12. Typing the message in one tab it should appear at the same tab on the right hand side, as well as at the tab with the second user logged in on the right hand side. Corresponding to the “sent” and “received” messages.
13. To logout and enter as a different user use the “Log Out” button.
