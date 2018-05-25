# Wk-8-Assignment

RED - CSRF
![red csrf](https://user-images.githubusercontent.com/37880152/40532884-c689b6d6-5fb5-11e8-845f-05b18af41ca9.gif)

Red IDOR 1
Looked to find the last visible ID of 9 then tried submitted other numbers found hidden users that were only appearing on admin side.
![red idor](https://user-images.githubusercontent.com/37880152/40532886-c6ddb8f8-5fb5-11e8-96d5-116818e4277e.gif)

Red IDOR 2
Went through inspect elemnt to change the name same can be done for Salesperson field.
![red idor 2](https://user-images.githubusercontent.com/37880152/40532885-c6aceb88-5fb5-11e8-9d8f-89ec1abc6da6.gif)

Green User Enumeration 
There is a difference between the bolded and not bolded may tell you something about the username entered as in one lets you know its correct or not. (But obvi I know which one is right)
![green user enumeration](https://user-images.githubusercontent.com/37880152/40532893-cb0a9e00-5fb5-11e8-9f23-6a134a945ecd.gif)

Green XSS
Self-explanatory got it from the Facebook Assignment page for week 8.
![green xss](https://user-images.githubusercontent.com/37880152/40532895-cb2c3d76-5fb5-11e8-83c2-776f4809eed6.gif)

Blue SQL

Also self-explanatory entered it in a few different places such us contact areas until it worked via url 
![blue sql](https://user-images.githubusercontent.com/37880152/40532912-d5fbacd2-5fb5-11e8-8621-599df79d7ad2.gif)

Blue Session Hijacking
This one would be considered session hijacking because the sessionid is shared amongst the 3 sites despite only logging in to 1 site I am able to access all 3 with admin login even though there is a 30min logout timer. This is due to the fact that the session id's are shared between the websites. Giving you access to things/websites you shouldnt have access to.
![blue session hijacking](https://user-images.githubusercontent.com/37880152/40532917-d9a9d96c-5fb5-11e8-8142-d6da75f2713e.gif)
