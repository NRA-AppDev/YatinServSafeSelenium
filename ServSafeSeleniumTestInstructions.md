# SpencerServSafeSelenium

First challenge - Mandatory 
Create Account              

1.	Use any gmail account.  This automation script should create a new account.  In our system, you can not create two accounts with the same email address.  To bypass this problem, you can use a feature in gmail, where any substring that comes between a + and a @ symbol is ignored.  For example servsafe@gmail.com, servsafe+test1@gmail.com, servsafe+test2@gmail.com will all send email to the servsafe@gmail.com mailbox, but for the purposes of our system, count as separate email addresses.  We expect your code to dynamically generate the part between + and @.  If it does not do this, it does not pass the acceptance criteria.

2.	Automation script should get the point where the verification code should be put in.  You can then manually enter the code you receive, and then continue the script from that point.  Find some approach that causes your script to wait for this input.  The script should continue from this point on to the home page, and assert the user is logged in.

3.	Use assertions wherever you think something needs to be validated, to ensure the behavior of the page is as expected.  Without good use of assertions, it does not pass acceptance criteria.

Second challenge - Mandatory                
Login/Logout – with the account created in the above step, in a second session, in another method,
1.	Log into servsafe.com
2.	Log out of servsafe.com
3.	Log into servsafeinternational.com
4.	Log out of servsafeinternational.com
5.	Make Sure Same Code/Method runs twice to login/logout on 2 sites.
6.	Use Assertions wherever you think needs to be validated

If the code does not test logging into and out of the account on both sites, it does not pass acceptance criteria.

Third challenge – Optional stretch goal if you have time.   
Launch Exam
1.	Use this account to login to Servsafe (nraregression+20220321122315@gmail.com/Password@233)
2.	Click SERVSAFE FOOD HANDLER (link) on home page
3.	Click Take Online Exam 
4.	Select Online Exam (ServeSafe Food Handler Onlien Assesment)
5.	Click Continue and Launches a new window (Assert here to verify New Window)
6.	No Need to Take Exam.
7.	Use Assertions wherever you think needs to be validated
