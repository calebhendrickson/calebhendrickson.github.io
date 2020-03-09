## MEAN Stack E-Commerce Project

[Back Home](README.md)

### Non-Technical Description
I created an e-commerce web application where non-admin users can browse a list of products, view their details, and add the products to their shopping cart. Admin users can upload, edit, and delete the products displayed on the website from an exclusive admin dashboard. Visitors have the option to create an account but it is not required. This was a feature I felt strongly about. I wanted to make site access convenient for the ordinary user.

# Deployment
This application was deployed using Heroku's cloud web hosting, mLab's cloud database service, and AWS S3 bucket cloud file storage for image file storage

# Features of the Application:

  Navbar
  
 * Contains links to the different pages within the application 
  
 * Navbar links differ depending on if the user is an administrator or not an administrator of if the user is logged in or not
    
 * The adminstrator account functionality is a superset of user account functionality
    
 * Contains a counter next to the cart link to let users know how many items are in their cart instantly
    
  User Functionality:
  
    Pages/UI Routes
    
      Home
      
        * Product list
        
        * Each product card shows the product image, price, name
        
        * Each card also contains an Add/Remove from cart button
        
        * Each card also contains a view more button to view more product details
        
      Registration
      
        * Registration form
        
      Login
      
        * Login form
        
      Profile
      
        * Displays account information such as name, username, and email
        
      Product Details
      
        * Displays product image, name, description, and price
        
        * Add/Remove from cart button
        
      Cart
      
        * Allows users to view all of the items that they have slected for their cart
        
        * Allows users to increase/decrease the quantity of the items in their cart
        
        * Remove product button to remove that item from the cart completely
        
        
  
  Administrator/Manager Additional Functionalities:
  
      Dashboard
      
        * Hub for navigating to editing, creating, and deleting products
        
        * Contains an add product button and an edit product button to route the user to the appropriate form
        
        * Can delete products and their data from the database with the click of the remove product button
        
      Add Product
      
        * Add product form
        
      Edit Product
      
        * Edit product form
        

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

The completion of this project was a long time coming. I first had the idea for this project in the Summer of 2018. At the time, I had decided that I wanted to work with the MEVN JavaScript stack. This choice was fairly arbitrary, I had only selected it because I found a tutorial that I thought would be helpful. In the end, I did not end up using this tutorial but I liked the design of the appliaction within the tutorial and I wanted to keep the design with some changes. I gained experience with JavaScript, Node, MongoDB, and Vue through my initial efforts on the application that summer. However, I did not come close to finishing the application. If I had consistently kept at it, I would have been able to finish the application in the following months during my free time from school. However, I am not sure that I had a strong enough grasp on the high level concepts of web application design and architecture, so I don't know for sure how long it would have taken me only working on it sparingly. 

Round two of work on this application began again in the summer of 2019. I continued with the MEVN stack and restarted from scratch on the codebase. I progressed further than I had the previous summer, but I was not able to put my full focus on the project this go around because I was preoccupied with a summer course and the start of development for my senior design project. i put my senior design project at a higher priority because I did not want to let my team down and I believe that required coursework should come first. I continued work on the project through the fall of 2019, but I was never happy with the amount of time I spent on the project. However, I don't believe that this was the reason why I had not successfully completed the project.

Fast forwarding to my December 2019 graduation, (approximately a whole 18 months after starting the project) I began applying for jobs but I didn't have any strong personal projects to put on my portfolio. And this project had been on my mind. A personality trait that is ingrained in me (that I can't stop myself from doing it unless I really try), is that the longer, and with the greater intensity I work on a problem, the desire to complete the task increases. In this scenario, I had just managed to let other things take my attention away from the project. I would also say that I never truly put intensity into the completion of the project.

As I was searching through web development jobs, I found that there were not very many jobs hiring for the JavaScript stack, and there were very many hiring for Java EE and ASP.NET frameworks. Upon discovering this, I felt really foolish for realizing this so late. I didn't have any practice with either framework. So I decided that I really wanted to dive in gain experience with one of the two and implment the E-Commerce project that I had failed to complete for the last year and a half to accomplish two things at once. I decided to go with the Microsoft stack for two reasons. I had seen from several sources online that it might be a little bit easier to go with ASP.NET first. Also, I didn't know much of anything about C#, and I really prefer to have some type of understanding of many things rather than a specialized understanding of a few things. I had already used Java quite heavily at Iowa State so I was familiar with it. It wasn't until I started studying C# that I realized how similar the two languages are. Before studying C# I didn't even know that it was an object oriented language.

So I started diving into the ASP.NET developer course on LinkedIn learning. This course covered a lot of ground and helped my get my footing. The RESTful API sub-course was 4 hours and was the turning point in my understanding of the high level concepts associated with web development such as architectures, and how data flows through the back-end of an application. This was something that I was very lacking previously and was holding me back in my attempts to develop my project in the past. ASP.NET conventions use a very structured aproach towards development and this was critical building my understanding of how to develop a web application. I never used these concepts in my development with the JavaScript stack and I was inept because of it.

Now that I realized this I was excited to 

understanding things from a high level view first
implementing too many features
not enough knowledge



### What Went Wrong




### What Went Right

To get started, I had the help of a tutorial from scotch.io on creating forms, routing the application, and using CRUD operations with the axios library. 

As of now, I am satisfied with my stack, framework, and library choices for this project and I am very happy with what I have learned about these tools.

For testing along the way, I used a manual functional testing approach throughout this project, and this performed satisfactorily.

I am very happy with what I learned about my work process and how I can improve it in the future.

I am very happy with getting to use and refine my problem-solving skills.

Had fun pursuing something that interested me.


