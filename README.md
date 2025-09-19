# Online Store v1 by @modernweb

In this repo, you will know about this project's details on what stack it is built on and why. You will also find supportive files that you may need to follow along in the course.

*Online store is made by [**@modernweb**](https://youtube.com/@modernweb) for youtube tutorial* 

👉 You can check it live on - https://online-store.modernweb.in 

## Project Stack

This online store uses all the latest frameworks and libraries 
<br />
<p align="center">
 <img width="400" alt="Screenshot 2025-09-19 at 1 56 55 PM" src="https://github.com/user-attachments/assets/a19bbb8f-d6e1-4db5-bd58-c5282eb958c9" />
</p>

#### Frontend

<!--
<img width="2152" height="1353" style="margin-bottom:20px;" alt="Screenshot 2025-09-19 at 1 46 58 PM" src="https://github.com/user-attachments/assets/b9f07737-0135-4c37-b605-65b4afa7efe5" />
<br><br />
-->

1. **Next JS** - this framework is built on top of react JS. Next js offers some great features like SSR, APIs, ISR etc.
2. **Next Auth** - for google authentication management.
3. **Chakra UI** - for easy, modern, responsive, functional UI components

#### Backend

<!--
<img width="2540" height="1235" alt="Screenshot 2025-09-19 at 1 52 57 PM" src="https://github.com/user-attachments/assets/96efc03d-92f9-4c03-b663-60c685458e9b" />
-->
  
1. **Strapi** - it is a open source professional level CMS ( content management system ), we are using this to maange the data fos tore like order management or products management.
2.  **Stripe** - it is a beginner freindly and easy to use payment gateway which does not require any kind of business verification to use in test mode. This projects run in test mode do no real transaction is involded on this project demo at least.
3. **Cloudinary** - this projects uses cloudinary to manage file uploads, all the files generated on strapi of frontend get saved on cloudinary.
4. **Nodemailer** - this project also uses nodemailer to send email notifications like welcome email, order status or dispute notificaiton etc.

#### Database

1. **Postgres SQL** - this project uses Postgrest SQL database instead of Strapi's default SQLite database.
  
## Project Features

This project is an online store and has a good amount a good features that real world stores have like

1. Google login
2. Global cart sync ( Local and cloud cart sycn )
3. Extensive product filters on search page
4. Dual theme
5. Email notifications
6. Product stock locking in checkout to prevent overselling
7. Clearing the locked stocks in case of order failure every 10 mins or on checkout expiry
8. Support system with threads, managed from strapi. User can re-open tickets if they are not satisfied with the asnwer
9. Fully SSR dynamic pages which helps in SEO
10. Fraud protection by stopping the user from making new order until thier dispute on delivered order is resolved
    
    and much more..


If you have any question regarding this project feel free to contact me on help@modernweb.in. I would love to hear you feedback on this project. Do share your feedback on feedback@modernweb.in
