# cloudformation

**SNS alert via mail when any action occurs in IAM account via Cloud Trail API Calls using cloudformation script**

**Steps:**

1. Download the given script above

2. Go to AWS Cloudformation console

3. First create a stack and upload the yaml/json file you created
![image](https://user-images.githubusercontent.com/54815529/126999142-778d63b1-0033-4008-9d33-f754f3e8c0e7.png)


4. Specify the stack name and email on which you wanted to send email

![image](https://user-images.githubusercontent.com/54815529/126999200-7ccd1a75-9909-4b8a-a895-63e6f1d19379.png)


5. Check your resources being created in SNS

![image](https://user-images.githubusercontent.com/54815529/126999309-d61d627f-c4fe-449d-b99f-1a7855e403d0.png)


6. Allow CloudTrail to monitor your API calls

7. Now Go to IAM and try changing any event mentioned in the script

![image](https://user-images.githubusercontent.com/54815529/126999386-9c8872a4-ccb2-4ddd-8dd1-1ca6d538e8d8.png)


8. You will get the mail that you have mentioned.

Output:

![image](https://user-images.githubusercontent.com/54815529/126998982-8546c19f-1e2c-4afa-b9fb-4ff7793c8b8b.png)



Your output will look like this in email

You can also parse it to get the desired fields :)
