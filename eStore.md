## Personal e-Commerce Project

[Back Home](README.md)

### Description

For my personal project, I wanted to create an e-commerce web application. This web application is being developed with the MEVN stack. The web application would feature a registration/login page upon site entry (this is currently in production, front-end for this and routing for this needs to be completed), where entry to the web application is validated with bcrypt, CSRF Tokens, and mitigation of XSS. Users are allowed the option register on first entry into the site, or to proceed as a guest. Cookies have been implemented so that users will not have to have log in again on each site entry. In the future, Passport.js will be used to allow registration/sign up with Facebook or Twitter, Google Plus, etc. From here users are routed to a home page that displays various products and their respective titles, prices, and images. This serves as a “browsing” page. In the future, this page will contain sorting options to sort products by price, manufacturer, etc, and a search bar to allow for looking for items with specific keywords. The Product item components currently have an add to cart option. And upon clicking on a product, you will be directed to the products details page via VueRouter. This page contains details about the product and the option to put the item (in the future a user will be able to specify a quantity) into your cart. At the top of all pages, there contains a nav bar to allow for navigation between the home page/browse page, account page, and cart page. The nav bar was created again with VueRouter. The cart page contains a list of all of the items that the user has selected to be in their cart. Items are listed with their title, price (and in the future, quantity) and the option to remove from cart. Upon checkout, users must re-login to ensure security, and payment is facilitated via stripe (Paypal). In the future there are plans to include There are plans in the future to include shipping tracking information and confirmation e-mails.

```markdown
Home Page:
```
![](MEVN_estore_pics/homepage.PNG)


```markdown
Home Page (Adding to Cart):
```
![](MEVN_estore_pics/homepage_addtocart.PNG)


```markdown
Home Page (Removing From Cart):
```
![](MEVN_estore_pics/homepage_removecart.PNG)


```markdown
Cart Page:
```
![](MEVN_estore_pics/cartpage.PNG)

```markdown
Empty Cart:
```
![](MEVN_estore_pics/emptycart.PNG)

```markdown
Product Details Page:
```
![](MEVN_estore_pics/product_details.PNG)


```markdown
Account Page:
```
![](MEVN_estore_pics/account.PNG)


```markdown
Admin Page:
```
![](MEVN_estore_pics/admin.PNG)


```markdown
Show Product:
```
![](MEVN_estore_pics/showproduct.PNG)

```markdown
Edit Product:
```
![](MEVN_estore_pics/editproduct.PNG)

```markdown
Add Product:
```
![](MEVN_estore_pics/addproduct.PNG)



### Lessons Learned / Skills & Knowledge Gained

I gained firsthand experience to many aspects of Full-stack development. 

The process of starting a project from scratch that encompasses so many different components was something that I underestimated. This required a great deal of thought and planning in the beginning stages of development. I decided that I wanted to develop using one of the MERN, MEVN, or MEAN stacks because of their wide use and popularity. I figured that learning one of these stacks would be very applicable to future projects. One of the futures of the design of the website that I was excited about was the fact that I would be creating a single page application. I wanted to make sure that my development choices and specified requirements were chosen with the goal of elevating user experience. I knew a single page application would mitigate interruptions and elevate user experience. With my primary goal determined, I decided that I wanted to take the most efficient path to that goal considering what research I had done. Because of this I decided a good framework to use for this with a small learning curve would be Vue,js.

Before development, I knew that I would need the obvious libraries such as Vue Router, and webpack, etc. However, during development, I discovered that I would also need libraries such as VueX for state management, Passport.js for authentication with Facebook or Twitter, and Stripe for secure payment with Paypal to name a few. Here is a list of some of the technologies that were used during development:

MongoDB, Express.js, Vue.js, Node.js, Vuex, Vue Router, axios, bcrypt, Bluebird, Bootstrap, Multer, Passport.js, Webpack, JQuery, UUID, Fs, Cors, eslint, nodemon

Another thing that I found rewarding about this project was the aspect of problem solving on my own. I didn’t have anyone personally to ask for help other than the internet (which is a pretty good resource). So this project taught me a lot about the process of problem solving on my own and self-learning. I felt that this was very important because these are both powerful skills. I enjoy problem solving so thankfully this was an enjoyable process.

Another skill that improved during the development of this project were time-management skills. Particularly, in the realm of pushing myself to work on something that doesn’t involve a grade or a deadline. This also relates to self-accountability, sticking to my word when I tell myself that I am going to work on this project.

Something that struck me as I pushed through development was how much more research I could have done before choosing my stack and choosing what supporting libraries I would be using to fulfill functionality. Along with this would be spending more time learning the fundamentals of the Vue.js and Express frameworks. In the future, I will spend much more time doing research before I start coding away. I believe that this will make me a much more efficient worker.

Something else that struck me during the development of this project was the importance of assigning priority to the development order of all the different components of the project. I noticed that there were advantages, for example, to starting on routing the components before developing the components themselves. I think that this is something that in the future, I will give more thought to before starting development.  


### What Went Wrong

Unfortunately, the progress of this project has been halted. As neared the last month or two of the fall school semester, I had to focus my efforts on my senior design project and online course, as well as preparing my resume, LinkedIn, and portfolio. However, that does not mean I don’t intend to finish this project in my free time in the future. 

There were a few points while working on this project where I was stuck on an issue, for example uploading image file was a bit of a struggle. Eventually the multer middleware solved this problem. That is until I ran into another issue. The issue that I was having before I had to put the project on hold is that Chrome doesn’t allow its browser to load local resources. 

I should have done more research towards what technologies would be best to implement the functionalities of the project. Some of the libraries that I did not use could have made implementation much more efficient but some of these libraries were exclusively used with React or Angular, or a database that wasn’t MongoDB etc.

I should have worked on some things in a different order, for example I wish that I would have started with the login/registration page first, instead of the home page, and cart pages, that way I would not have had to reroute the application to have the login/registration page as the “entry” point.


### What Went Right

To get started, I had the help of a tutorial from scotch.io on creating forms, routing the application, and using CRUD operations with the axios library. 

As of now, I am satisfied with my stack, framework, and library choices for this project and I am very happy with what I have learned about these tools.

For testing along the way, I used a manual functional testing approach throughout this project, and this performed satisfactorily.

I am very happy with what I learned about my work process and how I can improve it in the future.

I am very happy with getting to use and refine my problem-solving skills.

Had fun pursuing something that interested me.


