---
title: "Create cloud9 instance"
date: "`r Sys.Date()`" 
weight : 2
chapter : false
pre : " <b> 2. </b> "
---

### Create 1 Cloud9 instance

  In this step we will create new **cloud9 instance**
  1.Login AWS Management Console. 
    ![cloud9](/images/2.createinstance/home.png)
  1. Click search box and fill "**Cloud9**"
  - Click  **Cloud9** to go management page **Cloud9** 
    ![cloud9](/images/2.createinstance/search.png)
  
  2. At "**Cloud9**" screen
  - Click ***Create Environment**
    ![cloud9](/images/2.createinstance/create1.png)
  - 
  3. At step 1 "**Name environment**"
  - set name for you instance
  - VD: firstcloud9
  - Click **Next Step**
    ![cloud9](/images/2.createinstance/name.png)
  - 
  4. At step 2 "**Configure settings.**"
  - Environment type : Choose Create a new EC2 instance for environment (direct access).
  - Instance type : Choose t2.micro.
  - Platform : Choose Amazon Linux2.
  -Cost-saving setting : chọn **After 30 minutes**. Allow auto stop after 30m
    ![cloud9](/images/2.createinstance/config.png)
    
  1. At **Review** page.
  -Check configuration
  -Move to end of page, 
    ![cloud9](/images/2.createinstance/review.png)
  1. It's take some minutes to create
    ![cloud9](/images/2.createinstance/inprpgress.png)
  2. You create a instance successfully
    ![cloud9](/images/2.createinstance/doen.png)



  - Click **Next step**.

