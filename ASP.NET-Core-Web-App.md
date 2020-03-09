Description

 * This application is designed to allow users to sign up and create an account/log in to an existing account.

 * Once an account has been created, users can buy/sell crypto-currencies based on real-time prices with the virtual balance they have been alotted on sign up.

 * There is no real money exhanging hands in this application. This is just a simulation of buying/selling crypto currency to get people exposed to the crypto market for free.

 * The user's balance and total value of assets is displayed on the user's account page.

 * The hangfire framework server runs in the background and requests the data on cryptocurrencies every 15 minutes. This would be updated up to the minute if there was not a limit on the amount of API calls that you can make to the Alpha Vantage API to get crypto-currency data for free. I wanted to keep development cost of this application absolutely free.

Lessons Learned / Skills & Knowledge Gained

Immediately after completing my MEAN stack E-Commerce project, I debated between iterating on development features to really polish off the newly finished application, or creating another web application that used the ASP.NET Core framework.
After all, I had already spent a good deal of time learning the framework already. And I thought it would be more advantageous to have a fully completed, from scratch ASP.NET Core appliaction deployed on web because it would increase the range of my skillset. 
I also really wanted to prove to myself that I could do it, and do it quickly. Thus, I began brainstorming ideas for an appliaction that I would find just as useful and intriguing as the E-Commerce project that I had just completed. I knew that if I could come 
with an idea with such a quality, the project would be a success. 

Something that I had always wanted access to growing up was some sort of stock trading simulator. I didn't want to spend any actual money, but I wanted to learn what it was like
to trade stocks. So, I knew that this was the correct idea for a project. I had a personal interest and drive for the concept of the application. I began looking for an API that I could access to retrieve financial stock data in real time,
and stumbled upon the AlphaVatnage API which gave access to stock data and crypto-currency data. Once I saw this, I was intruiged and changed the direction of the project to be directly focused on crypto-currency data.

Development: I actually began development using the older ASP.NET framework as opposed to the newer ASP.NET Core framework. I chose this framework because I had seen many job postings with ASP.NET in the reuirements list instaead of ASP.NET Core. I also had no expereince with the ASP.NET framework, so I wanted to see where the two frameworks differed. 
So, once I began working on the appliation, I was foolish and failed to follow the layered architecture concept that I had recently learned. In doing this, my code became very hard to follow and had high levels of coupling and low levels of modularlity. This bothered me, and I refactored the code into the 4 standard layers described in layered architecture. This primarily
consisted of me abstracting the data persistence layer away from the controller logic. When I was doing this, I wanted to my implementation of this new layer to focus on increasing the modularity, extensibility, and readability of the application code. I created helper methods in a class the persistence layer with as few interdependencies between methods as possible. In the 
future I plan on abstracting related into separate classes once the size of the class gets too large. I also wanted very descriptive method names for the helper methods so that, paired along with the comments in the controller layer, it will be very easy for othersa nad myself in the future to read and understand the code. 

I ran into one issue while working with the ASP.NET framework that led to a large change. Initially I started with only working with one cryptocurrency that was available to view, buy, sell in real time. However I was calling the API on each one of tese actions. The AlphaVantage API limits their free users to 5 API Calls a minute or 500 API calls a day. 
So, I realized my current process for calling the API was unfeasible and inefficient anyway. I decided that it made more sense to use a background service to Call the API and update the database and then use the freshly updated database data for viewing, buying, and selling. This approach would be much more scalable with a large userbase. And it was a necessity for me given that I was only allowed a set amount of API Calls.


API Call structure & limit
Switching to layered architecture
Switching to ASP.NET Core
Hangfire Background Service
Deployment with Docker, Kubernetes, adn Google Cloud



What Went Wrong


What Went Right
To get started, I had the help of a tutorial from scotch.io ocreating forms, routing the application, and using CRUD operations with the axios library.
As of now, I am satisfied with my stack, framework, and library choices for this project and I am very happy with what I have learned about these tools.
For testing along the way, I used a manual functional testing approach throughout this project, and this performed satisfactorily.
I am very happy with what I learned about my work process and how I can improve it in the future.
I am very happy with getting to use and refine my problem-solving skills.
Had fun pursuing something that interested me.
