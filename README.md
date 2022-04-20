# Automate-Post-using-Selenium
Selenium is a tool used for controlling web browsers through a program. It can be used in all browsers, OS, and its program are written in various programming languages i.e Java, Python (all versions). 

Selenium helps us automate any kind of task that we frequently do on our laptops, PCs ranging from using Facebook messenger for texting and WhatsApp also, daily tweeting tweets on Twitter, wishing friends “Happy birthday” on Facebook, googling anything we want to learn, and many more task. All these tasks can be automated using selenium in just a small implementation.

Steps: 

#Create a browser object and use the get() function to send a request to the website we want to connect/use.
#Find the elements like username and password input boxes, login button, and using the selenium functions like click(), send_keys(), etc to click on buttons and enter username and password respectively.
#After that using get() function to send a request to /events/birthdays/ page.
#At the top of this page, there is a card of “Today’s Birthdays” which shows a friend’s name whose birthday is today along with an input text box to enter any feed on their timeline.
#Using the XPATH of these input text boxes we will send our feed i.e., “Happy Birthday” using the send_keys() function of selenium.
#Close the browser.

##Make a separate fbpassword.txt file and put your Facebook password in it before the execution of the below program.
