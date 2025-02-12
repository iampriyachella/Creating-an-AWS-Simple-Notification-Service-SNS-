# Creating-an-AWS-Simple-Notification-Service-SNS
AWS SNS is a pub/sub messaging service that allows publishers to send messages to multiple subscribers (email, SMS, Lambda, SQS, etc.)

![Screenshot 2025-02-12 054019](https://github.com/user-attachments/assets/a95f58c9-87cf-49ad-b071-16865a18a188)

Step 1: In SQS,Create an Queue and name it as MyQueue

![Screenshot 2025-02-11 224232](https://github.com/user-attachments/assets/88951ccd-b20f-4e01-b8ae-74bdd290eba6)

![Screenshot 2025-02-11 224321](https://github.com/user-attachments/assets/5bab3b19-afbe-4876-b845-fe3b52afa035)

Step 2: In SNS,Create an Topic and name it as MyTopic

![Screenshot 2025-02-11 224630](https://github.com/user-attachments/assets/72df0fe9-e399-4a8d-856c-d5c5f1803b9a)

Add MyTopic in SQS

![Screenshot 2025-02-11 224835](https://github.com/user-attachments/assets/70fbe0fe-f64e-4a84-87fc-9f347856bd3e)

Again add that MyTopic in Email and give your Email id in which it wants to publish the message.

![Screenshot 2025-02-11 225009](https://github.com/user-attachments/assets/58d04f53-daaf-48d8-90aa-102e24085dd9)

Step 2: Subscribe the SQS Queue to the SNS Topic

![Screenshot 2025-02-11 225142](https://github.com/user-attachments/assets/f0218d3a-61e8-4a6c-af20-89da58772655)

![Screenshot 2025-02-11 225203](https://github.com/user-attachments/assets/d00ae4c9-3a88-436f-8bd9-5bc409df56f8)

Now Go to Email,An Subscription confirmation has been popped-up.

![Screenshot 2025-02-11 225224](https://github.com/user-attachments/assets/447ac39a-cba0-434c-96c4-a59791784f35)

Click Subscription confirmation

![Screenshot 2025-02-11 225240](https://github.com/user-attachments/assets/23609b84-43da-49ba-8292-b3b5c39d486e)

Here,Both SQS and Email has been confirmed

![Screenshot 2025-02-11 225326](https://github.com/user-attachments/assets/e57a55f9-0a14-4987-b1e6-cb5a367d7b08)

Click that MyTopic and select Publish Message

![Screenshot 2025-02-11 225405](https://github.com/user-attachments/assets/f4856187-4dab-4df5-bebe-e0d8a1da5265)

Write your message in that

![Screenshot 2025-02-11 225613](https://github.com/user-attachments/assets/9787c5c6-fe3e-4f1b-bf2b-ef0058ae8660)

Step 3: Go to SQS, By scrolling down,you can find Message available 1 to view that you must select "Poll for messages"

![Screenshot 2025-02-11 225728](https://github.com/user-attachments/assets/5bbe5702-c454-4e42-8265-bec94f9bb6d1)

Message has been appeared

![Screenshot 2025-02-11 225745](https://github.com/user-attachments/assets/0049861e-9cc6-4869-ab7a-e915a18a9b3f)

Now In Email, you have got the message too

![Screenshot 2025-02-11 225801](https://github.com/user-attachments/assets/831c3d12-4bc0-4d0d-b9d2-4f24e6a9e0b8)






