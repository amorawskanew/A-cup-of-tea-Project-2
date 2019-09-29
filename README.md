A CUP OF TEA-PROJECT2

My intention was to create an e-commerce website for small/medium businesses. I chose to design a website for online shop that sells various types of tea ( green tea, black tea, herbal tea and special collection). I tried to keep it simple, mainly focusing on technical aspect of the website. I wanted to include as many Js elements as I could to make it interactive and enhance user's experience, but the process turned out to be quite challenging.

Things that didn't go the way I had planned are as follows:

1. Shopping cart- I was very excited to be finally able to put in practice my js skills. I spent considerable amount of time reading and watching online tutorials on how to design an ecommerce website with shopping cart, but when  I started to write a code myself it took q life of its own. Whenever I wanted to console.log a part of my code to see if it works, I would always get an error notification. I put all my shopping cart Js code in( app- js) file and disabled it, because it was effecting other parts of my website. I intend to finish my shopping cart later when I have more coding experience.
2. Emai box-I set up my email according to the code institute video tutorials and it all worked beautifully in my AWS text editor. However, since AWS doesn't support all the features ( like for example css grid...  etc.) I decided to move it to Visual studio, which I am very happy with. But, then I noticed that my emai page doesn't work anymore. I asked both my mentor and tutors to have a look at it. They run the code on their machines and said everything was ok. ..Maybe it was, but I sill don't know why it doesn't work on my computer.

What I am happy about is that my text animation worked the way I wanted. Initially, I was planning a text animation that  simulates handwriting (I think it would fit better in the mood of my tea website), but this required SVG files, which I am not that familiar with. 
I also spent a significant amount of time on online doing research for my website and managed to find nice quality tea pictures, which I used for my project. 
I experimented with different font sizes/styles, adding some shadow to make it pop out of the screen and add a bit of 3d feel. Styling was a very enjoyable part of the work because I could see immediate results and ask for feedback. I have created 3 different text styles and ask my friends to choose the  one they liked best. About 70% voted for my orange fonts, so I decided to include them in my project.

technologies/languages I used in my project:
I switched from AWS cloud9c to Visual studio, because AWS didn't support all the tools I wanted to use and also I am running out of credits ( only 24$ left).

*HTML-to provide structure for my website.
*css to style my page <link rel="stylesheet" href="css/bootstrap.min.css">
<link rel="stylesheet" href="css/text_over_image.css">
*Js- to create animation elements of the web and working of the email and shopping cart
<script src="assets/js/sendEmail.js">
<script src="js/bootstrap.bundle.min.js">
<script src="js/jquery-3.3.1.min.js">
*fontawsome- to use different types of fonts 
 'https://kit.fontawesome.com/a076d05399.js
*animate website - for text animation
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css">

     
Links to websites/ pictures/ video tutorials that I used when working on my projects:

1.https://www.youtube.com/watch?v=vOne31fj8c4&t=986s
2.file:///Users/Anna/Downloads/node-v10.16.0%203/Project%202/test/index.html
3.https://www.youtube.com/watch?v=7jy5d27jmrY
4.https://www.youtube.com/watch?v=RHj5bdrfCr8&t=3159s
5.https://www.youtube.com/watch?v=90PgFUPIybY&t=9099s
6.https://www.youtube.com/watch?v=6vOJoAmbza0
7.https://www.w3schools.com/java/
8.https://dev.to/programliftoff/create-a-basic-webpage-with-css-and-javascript--1049.
9.http://www.javascripter.net/faq/rgbtohex.htm
10.https://www.crazyegg.com/blog/best-website-layouts/

Features:

1.Landing page and navigation bar allows users to get familiar with what the website is about and the menu( home, about, products, contact)

2.About us -provides a general background about the company and its products. it allows users to get an idea about the company and its products and services.
3.Products- in this section of the website users can see full selection of the products. By clicking on a shopping cart of selected tea they can purchase it. Later I will also create  a card online payment section.
There is also a button for each type of tea ( black tea, green  tea,herbal tea, special blend) connecting to the page where they can get more detailed information about the product(s) of their choice. For now, I included only a landing page  and  pictures of the same product type  ( for example only black tea..), but later on I would like to add more information  about each group of the products and also add a GIFT section, where customers could choose a product, packaging and delivery method( normal or express).

4.Contact- in contact section I have two subsections:
*the green one  with all the social links, Fb, Instagram, Twitter, Google which I connected to some tea website,  just to test if my website works.
*the orange section has a telephone number (not active), email icon connecting to the email box and a map icon (I was alsoconsidering adding a map with the shop location, but that's optional since the online shop doesn't really need to have any conventional setting.I wanted to practice with Google maps, but the website kept on asking me about my credit card number.

Testing 

* Checking if my website is user friendly
I made sure that the website has all the online tea shop relevant elements (I checked other on line websites ( https://www.templatemonster.com/joomla-templates/48083.html) and that it is easy to navigate ( navbar menu plus explore button) 

*checking if the website is responsive
After adding a new element I would go to Chrome browser and check how my website looks on different screen sizes (desktop, iphone, tablet) . The biggest challenge was always the- over- the- image text that has this tendency to change its position  and sometimes show up in the least expected place. 

*testing email box
As previously mentioned, the email itself was set up correctly and worked on AWS, but  it didn’t after moving my project to Visual studio. I think there must have been some kind of error in the process. checked "inspect-console" to detect errors, but didn’t find any problems ( neither my mentor)

*testing shopping cart ( app-js file)
I wrote a piece of code and console.logged it. Most of the time it failed. At the end I gave up on shopping cart (at least for now-I really want to finish it at some point as it is very interesting and doesn't seem to be that complicated) 

*testing if all my links are well connected 
by clicking on a button and making sure that I go where I want to. It all worked , although there are some things I want to improve too.testing user's visual experience.

*testing user's visual experience.I showed the web to some of my friends asked if they would buy a product from this web. They all said that product is well presented and they would use this online shop if they needed.



 Deploying my website

I switched from AWS text editor to Visual studio andI had to practice first how to push my project into github, which was quite easy, but if you do it for the first time it always takes time.
  
I will deploy the project after finishing writing my READme report and will see if there is any differences between development and deployed version.

Here are the questions from READme example file which I don't quite understand. I hope I will be able to answer them in my next project.

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?

Credits

*The text for section ABOUT US  was partially copied from the website:https://theme255-tea.myshopify.com/products/positively-tea?variant=21381320003

*The photos used in this site were obtained from : https://www.templatemonster.com/templates.php?text=tea&sort=relevant

*Acknowledgements
I received inspiration for this project from numerous youtube tutorials ( over 20 in total).
And also a big thank you to my mentor who is very knowledgable and patient with me.

I had a lot of fun creating this page, but also was constantly challenged with implementation of my ideas. The code is not very clean.( run it through html, css, js validator) There is a lot of redundant elements, but I left them intentionally since I still want to work on it and want to try different solutions. Overall working on  my Milestone project was a very demanding, but enjoyable experience (I spent about 20 days on it).  

Thank you for reading my READme report.

Regards,

Anna Morawska 



  

 