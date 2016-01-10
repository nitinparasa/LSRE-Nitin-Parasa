#Week 46: 

Release Planning often is related to dealing with the requirements that have been collected by various stakeholders involved in a project. The main task in release planning is to separate the requirements collected into different groups upon whose implementation will lead to the development of a working product. 
It is not always true that the requirements gathered are always well understood and match the universal standards. People have different styles of expressing themselves and this is often misinterpreted by the analysts. Hence several meetings are conducted among the stakeholders to achieve clarity and eventually develop a good product. 
This week I have gone through the whole list of requirements elicited. I started to make comments on some of the requirements that I found which are very interesting and could contribute to. Started tracking the issues and commented on Issue #3 “Secure Product”.

#Week 47:

Replies started coming in for the comments that I have made.

**Issue 3: (Secure Product)**
- Description: As a system manager I want the product to prevent unauthorised use, so that I can control who is using the system.
- Comment Posed by me: How about using the university provided credentials (E-mail and password) details for the login? Adding E-mail confirmation after Sign-Up would further enhance the security to the system. 

The professor found this argument interesting enough and asked me to add requirements for this. I started to think on this issue and will try to add in new requirements that reflect this issue in the days later.

**Issue 4: (Limited Views)**

- Description: Different classes of users shall only be able to access predefined sets of functionality -- those sets of the functionality that they have access to use.
-	How I understood this issue is that the customer wanted to restrict the entry into the product only to selected individuals but then I have no clarity as on how to differentiate the users and what are the different functionalities. Hence I posted a comment regarding this.

**Issue 59: (Access to Discussion Forum)**

Description: Only participators in a course shall be able to access the course's discussion forum.

This needs a bit more clarity as of what kind of access id given to the course responsible? Is he also an active member of the discussion forums? Later on with the discussions of other members clarity on this issue has been obtained.

**Issue 69: (Course Chatroom)**

Description: I want to add one or more chatrooms to a course.

This was rather unclear requirement. This needed much fine-tuning and few people already started discussing about this. Then I placed my perspective of having an analysis of the text (sentiment analysis) on the messages being sent in the chats.

**Issue 68: (Contents of Message)**

Description: The user wanted a message to contain all the details of the date, time and the author who is sending the message.

I made a comment to clarify if the data of the authors being stored in our databases. Should wait for the respective personnel to respond to proceed further regarding this.

-	I focussed on the design aspects of some of the requirements related to the layout of the webpages and components that are to be involved in the webpages. Some requirements are Issue 73, Issue 64.

Some issues are already being given some labels by other members. I would start analysing the issues that I have been a main contributor for and would assign the labels to them as well.

#Week 48: 

-	Most of the comments I have made have been addressed by different members of the team. For most of them I get a clear idea as of how I should proceed. 

-	The head of the team has made a point for me to add new requirements that reflect the comments that I have made for already listed requirements. And for some of them I had to find the requirements in the list and link them. This is just to identify the dependencies between the requirements. 

-	I started a discussion forum to discuss about the prioritization technique for prioritizing the requirements that we have. Initially I made a comment on benefits of using either Group Estimation or Judgemental Combination for this project. I also listed out a few techniques like Planning Poker, COCOMO, etc. Later on that day I got replies from various people that planning poker would be fine and some opposing it and focussing on COCOMO II model.

-	Then the head made a comment saying that “Would Planning Poker work for ~5000 requirements”. This made us think and then we started to think of other prioritization techniques like Analytical Hierarchical Process, Cost Value Approach, Ranking Method, Grouping.

#Week 49:

-	Following the comments I started to add new requirements and also started to link the requirements between each other.

**1. Login Credentials #88: (7-December)**

I opened this requirement and linked the other requirements which are related to this requirement. This would be a clarification to the issues #3 and #27.

**2. Recovery Email #92:**

I opened this requirement as an enhancement to Incorrect Login #61. This issue has been linked to it so that there is good traceability.

**3. Admin Functionalities #95:**

I opened this requirement to know what kind of functionalities the admin has to be given. With participant reflecting upon this issue much clarification to other issues could be achieved. Hence labelled this as clarification. Linked #4 to this issue.

**4. Course Start Page #12:**

Linked issue #14 to this as I felt that it is a part of this issue and later on during the design and development this could be of help.

**5. Course Chatroom #69: (8-December)**

I think that issues #23 and #59 which are the discussion forum and the access to it elaborate this issue. And I also opened a new requirement #100 Sentiment Analysis which could be used on the messages that are being sent in the chats. 

**6. Session Manager #109: (10-December)**

I created this requirement to start a functionality of performing the login and logout functionalities of the website. I added the label clarification to this issue. As specified I linked the respective issues #27 and #103 to this.

7. One of the requirement was about having enable and disable option for automatic logout option. I commented on this that the default option could be it being set to “enable” state considering the security of the user.
