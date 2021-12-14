# Car rental system (website)

#### Video Demo:  <https://www.youtube.com/watch?v=Z3Y75T7ORyU>

#### Description:
Hello , this project is about creating a site for renting cars to users , it is coded with HTML , CSS and JAVA SCRIPT.
The users must first get rigester and then they should log in in their acount and then they can rent a car.
the parts of this project are : 1-navigation  2-slider 3-list of cars  4-footer  5-login page  6-register page 7-Admin pannel
I will explain each part for you
                                                                  *************
                                                                  Navigation part:

This part is the top of the site , it has right side and left side , both sides are included some icons.
In home.html , I linked the site which I got icons from it .
Also in style.css , I  linked the font that I used in site , the font is BRUSHSCI , and in body part I wrote the font-size , so it fixed unless I change it.
In home.css , I classified each part and I chose color , font-size , margin , padding and etc for each class.
so this is how this beutiful navigation has been made.

                                                                  Slider part:

This part is below navigation and it will show 3 slides (image with span on them) each slide changes after 4 seconds unless the user click and change slides.
In home.html in class slider , I linked this 3 images with their span , and in class buttons , I liked 3 buttons and each button is for one image
so when users click on buttons they can see specefic image of each button (by using onclick).
In home.css , I wrote color , font-size and etc for each part . Becase we want to see 1 image at the same time so other images must be hidden
for this , I used one slide as active .
In main.js , it will chech if slide that user clicke on is active or not if another slide is active , we should remove active first , changing slide every 4 seconds and after slide 3 go back to slide 1.
I mantined main.js in home.html.


                                                                   list of cars:

This part is under slider and it will show image of cars , name and renting price of each car , buttons for ratting , like and renting car.
In home.html , in main part there are cods of this part they included icons link , image link (4 images) and etc . I also wanted to design it with flexbox and
the site size be bortebele in laptop screen , mobile screen and other devises screen but it didnt work :(.
I divided codes into classes and in home.css I set color , font size , positions and etc of each class elements.
the most interesting part is that the class of text for like and rent buttons are hidden , when mouse pointer go on them , they will be unhide and we can see the text
also the texts will smoothly be expanded by transiton in .75 second , in home.css

                                                                   footer:

This part is the last part part of this page , it shows description about admin and links and social medias which you can connect with admin also you can see copy right signs.
In home.html , in footer tag , you can see the code and link of icons of footer part.I wanted to devide it into left prt and right part but I couldnt.
Iin style.css you can see all color , positions ,font-size and etc that I use In footer part.

                                                                    register page:

This page is fo regestering user , user by entering username , email , password anconfriming password , can creat acount.
In register.html you can see codes of this part and in register.css you can see color , font-size , positions and etc that I used in this part.
I linked register.html in login.html , so if the user is not registered yet , he or she can go to register page by clicking that part.

                                                                    login page:

This page is for users that have been registered bofor , they can enter this page by clicking login icon in home page and then by entering their
username and password they can enter . If they are not registered yet by clicking the text below , they will go to register page for regestring.
In login.html , you can see codes , icon links that I used for this part . In login.css , you can see color font-size , back ground , positions and etc that I used for login page.
I linked login.html in home.html so the user can go to this page from home page.

                                                                     admin panel:

This page is for amin , admin can see their profile , including image and last time they were online , details about cars , users and etc.
Their is a pie chart that shows the most rented cars brands so the admin can know which brand is more populer amoung users.
In panel.html you can see code of this part and in panel.css you can see color , font-size , positions and etc that I used in this part.
And in panel.js , you can see functions that I used for hiding and unhiding texts and icons when user click on them , this part was the hardest part.
Also in pnel.js , you can see function of pie chart and its elements.
I linked panel.html in home.html so the user can go to this page from home page.

Thank you for reading this and special thanks to CS50X team for teaching me so many good things :) .

