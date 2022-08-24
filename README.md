# BookEx - Book Exchange  
## Introduction  
For TUM course SEBA, our team built a web application which facilitates book exchange, and more importantly, also brings people with similar reading tastes together.  
Once reading history is uploaded, our system automatically matches other users with similar reading tastes.  
After reaching an exchange agreement, users can start the exchange order right on our web app.  
To lower the risk of fraud, we take deposit from both sides. Users can also leave a review for the order, which will be displayed on the other user's main page.  

### Tech Stack  
The project uses MERN stack.  
- Frontend: React.js
- Backend: Express.js, Node.js
- Database: MongoDB  

### My Contribution  
- Prototype with Figma (click [here](https://www.figma.com/proto/Gif16Vt7j81WJ8witb5VGG/Book?page-id=0%3A1&node-id=34%3A1333&viewport=28%2C105%2C0.1&scaling=contain) to view it online)  
- Fullstack contribution  
  - User profile create & update   
  - Authentication & authorization with JWT  
  - Exchange order process and detail page  
- Other pure frontend contribution  
  - _All_ pages' layout & styles  
---
## Gallery  
### Auth Page  
![Screenshot 2022-08-21 at 19.17.27.png](https://res.cloudinary.com/hxlb1slpj/image/upload/v1661102615/Screenshot_2022_08_21_at_19_17_27_c8dca3f722.png)  
### Profile Pages
This is where user can edit their profile and book lists. 
**Book Collection** contains the books that the user has read, those available for exchange are maked as *exchangeable*.  
**Wish List** shows the books that the user wants from other users.  
![Screenshot 2022-08-21 at 19.18.20.png](https://res.cloudinary.com/hxlb1slpj/image/upload/v1661102611/Screenshot_2022_08_21_at_19_18_20_74660c8c4e.png)  

This is the *book list generation* page, where users can edit their **Book Collection** and **Wish List**. Book search is performed via Google Book API.  
![Screenshot 2022-08-21 at 19.20.13.png](https://res.cloudinary.com/hxlb1slpj/image/upload/v1661102621/Screenshot_2022_08_21_at_19_20_13_9914ab1252.png)  

### Bookmate Pages  
This page also acts as the main page. It gives a list of recommended bookmates for the user, based on the intersection of **Book Collections** of both sides. 
![Screenshot 2022-08-21 at 19.17.59.png](https://res.cloudinary.com/hxlb1slpj/image/upload/v1661102626/Screenshot_2022_08_21_at_19_17_59_0d98e56cbb.png)  

**Simple text messages (not realtime).**  
![Screenshot 2022-08-21 at 19.18.51.png](https://res.cloudinary.com/hxlb1slpj/image/upload/v1661102615/Screenshot_2022_08_21_at_19_18_51_1a42b2d743.png)  

**Bookmate profile page.**  
![Screenshot 2022-08-21 at 19.18.08.png](https://res.cloudinary.com/hxlb1slpj/image/upload/v1661102612/Screenshot_2022_08_21_at_19_18_08_aa42f7920d.png)  

**Reviews that this user has received for previous exchange orders.**  
![Screenshot 2022-08-21 at 19.18.35.png](https://res.cloudinary.com/hxlb1slpj/image/upload/v1661102609/Screenshot_2022_08_21_at_19_18_35_395d5437d8.png)  

### Exchange Order Pages  
![Screenshot 2022-08-21 at 19.21.06 1.png](https://res.cloudinary.com/hxlb1slpj/image/upload/v1661102624/Screenshot_2022_08_21_at_19_21_06_1_193373c5cc.png)  

**Picking books for the exchane order.**  
![Screenshot 2022-08-21 at 19.20.54.png](https://res.cloudinary.com/hxlb1slpj/image/upload/v1661102622/Screenshot_2022_08_21_at_19_20_54_08bcc7cbbc.png)  

**Order detail/progress.**  
![Screenshot 2022-08-21 at 19.19.11.png](https://res.cloudinary.com/hxlb1slpj/image/upload/v1661102617/Screenshot_2022_08_21_at_19_19_11_4cde907faf.png)