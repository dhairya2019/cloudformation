# cloudformation

**SNS alert via mail when any action occurs in IAM account via Cloud Trail API Calls using cloudformation script**

**Steps:**

1. Download the given script above

2. Go to AWS Cloudformation console

3. First create a stack and upload the yaml/json file you created

4. Specify the stack name and email on which you wanted to send email

5. Check your resources being created in SNS

6. Allow CloudTrail to monitor your API calls

7. Now Go to IAM and try changing any event mentioned in the script

8. You will get the mail that you have mentioned.

Output:

![image](https://user-images.githubusercontent.com/54815529/126997767-733ecf04-2c7e-446c-b2b0-ff47ff9d16c2.png)


Your output will look like this in email

You can also parse it to get the desired fields :)
