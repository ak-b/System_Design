1. How do you design the Vending Machine in Java? (solution)
You need to write code to implement a Vending machine that has a bunch of products like chocolates, candy, cold-drink, and accept some coins like Nickle, Dime, Quarter, Cent, etc. Make sure you insert a coin, get a product back, and get your chance back. Also, write the Unit test to demonstrate that these common use cases work. If you get stuck you can read my two-part articles (part1 and part 2) about solving these classical system design questions.
2. How do you design a URL Shortening service like goo.gl or bit.ly? (solution)
This one is another common System design questions. You have given a (typically) long URL, how would you design a service that would generate a shorter and unique alias for it? If you are not familiar with URL shortener service have a look at some of the popular ones like goo.gl from Google and bit.ly which is used by Twitter.
Make sure to provide database schema and rationale behind some design decisions like how long you keep the data, how to get stats and analytics etc. If you get stuck, you can follow the solution given on Grokking the System Design Interview course on Educative.
Image for post
3. How do you design a traffic control system?
A classical system design question from old age which is still popular. Make sure you know how to transition from one state to another like RED to GREEN and from GREEN to ORANGE to RED etc.
Image for post
Photo by Harshal Desai on Unsplash
4. How to design a limit order book for trading systems? (solution)
A limit order book is used in stock exchanges to match a buy order with a sell order based on price and time priority. How would you go about that? Which data structure you will use? Remember, the speed of matching is key and also the reliability.
If you need a refresher on Data Structure then you can check out Data Structure and Algorithm in Java course and If you feel stuck you can check out my solution here.
Learn Data Structures and Algorithms: Ace the Coding Interview
Course Ratings are calculated from individual students' ratings and a variety of other signals, like age of rating and…
www.udemy.com
5. How do you design a website like Pastebin?
Pastebin allows you to paste text or code and then share a link to that code anywhere you want. It’s not an online code editor but you can use this to store any kind of text.
6. How would you create your own Instagram? (solution)
Instagram is a photo-sharing application that provides some custom filters to enhance your photo quality. Your application should have photo upload functionality, tagging photos for search, and some basic filters. If you could add share or social network that could be great.
Btw, if you stuck, you can see the free solution provided on the Educative Grokking System design course as well.
Image for post
7. How do you design global file sharing and storage apps like Google Drive or Dropbox?
These are used to store and share files, photos, and other media. How do you go about designing things like allowing users to upload/view/search/share files or photos? track permissions for file sharing, and allow multiple users to edit the same document?
If you like Youtube video, here is a nice one which will teach you how to design a Dropbox or Google Drive or any other document hosting solution:

8. How do you design a chat application like WhatsApp or Facebook Messenger?
You have surely used WhatsApp and Facebook, right? No? If not let me tell you that a chat application allows you to send messages to your friend. It’s a point to point connection.
You keep a friend list and see their status and chat with them. In WhatsApp, you can also connect groups but that is for advanced and experienced developers. At a minimum, you should provide a design to keep a friend list and send and receive messages from them.
If you need some tips then I suggest you check out Preparing for the System Design Interview Course on Udemy, where you will find a whole case study to solve this problem.
Preparing for the System Design Interviews
System design interviews are very common in big software firms. They are different from coding interviews or data…
udemy.com
9. How do you design a Twitter Clone?
Twitter is a popular messaging service that lets you broadcast your messages to all your followers. You tweet and your followers see those messages, they can like or retweet.
Make sure you implement common features like followers, hashtag, tweet, delete, etc. If you going nowhere and stuck, you can follow the solution on System Design Interviews: Grokking the System Design Interview.
Image for post
10. How to design a global video streaming service like YouTube or NetFlix?
While designing a video streaming service like NetFlix or YouTube key thing is smooth streaming and buffering and functioning over low bandwidth connection, how do you manage those challenges. You can check out this system design course to learn how to deal with such problems.
11. How to design an ATM machine?
An ATM machine allows a user to deposit and withdraw cash. It also allows a user to see his balance. How do you design such a system? What are your main challenges?
12. How do you design an API Rate Limiter?
13. How do you design Twitter Search?
14. How to design a Web Crawler like Google?
A Web Crawler goes to a website and crawl all link and index them e.g. Google so that they can later appear in a search result. A Crawler can also use for searching a particular file in a set of directories, how do you design such things? What are the main challenges?
15. How to design Facebook’s Newsfeed? What kind of Algorithm will you use?
The newsfeed is an important part of Facebook which allows a user to see what’s happening around his world which includes friends and families, the pages he has liked, the group he has followed, and of-course the Facebook Ads.
The job of the Newsfeed algorithm is to show messages which are most important for the user and which can generate high engagement. Obviously, messages from friends and family should take priority.
If you feel not going anywhere and stuck, you can follow the solution on System Design Interviews: Grokking the System Design Interview.
Image for post
16. How to design Yelp or Nearby Friends?
17. How to design a global ride-hailing service e.g. Uber, Grab, or Ola backend?
Uber and Ola are two of the most popular ride-hailing services, it brings both drivers and passengers together. How do you go about designing to allow a passenger to see nearby taxis and book them?
18. How to design BookMyShow?
A website that allows you to book cinema and event tickets. This is actually an Indian startup that is doing well.
19. How to design a social network + message board service sites like Quora, Reddit, or HackerNews?
Reddit, Quora, and HackerNews are some of the most popular social network sites where users can post questions or share links. Other users can answer questions or comment on the shared links.
20. How do you design an application like Airbnb?
It allows some users to upload rooms for rent and other users to rent them. Some of the features are only available to admins, publishers, and subscribers.
21. How do you design an Elevator of the Lift system?
We All know about Elevators and Lift as most of us use it. You might have seen them in pairs and in some big office buildings you can see 3 to 4 lifts. You need to design software for that so that it can reach use quickly on different levels. You can assume you have two lifts and a 10-floor building.
Here is a nice Youtube video which explains the solution to this popular system design interview question, you can watch it right here.

22. How would you go about designing an e-commerce website like Amazon or Flipcart at scale?
23. How would you go about designing the e-commerce website using microservices, how will you handle transactions?
24. How would you design a Parking Lot system? (solved)
This is an interesting problem and asked for companies like Amazon, Google, Apple, and other FAANG companies.
You should cover the following use cases
Give a user ticket when he enters
Generate price when the user exits.
Here is a nice youtube video that explains this problem and the solution. They also discuss APIs, Database models, and database choice. they also discuss on how to make it distributed. We also discuss concurrency.

24. Create an autocomplete feature like word suggestions on search engines? Scale it to millions of users?
25. How would you go about creating a feed posting on a social network like Facebook, Instagram, Twitter, LinkedIn, etc?
