# **Cibo Fresco - Portfolio Project 1**

- This Portfolio Project 1 website called **Cibo Fresco** is an imaginary restaurant site offering only the best Italian food and drink. Cibo Fresco restaurant is presenting to is't visitors with Food and Drink menu, small picture gallery, contact details and function of making table reservation (Hoping to enable this function later, progressing the course).
- Live version of **Cibo Fresco** page can be viewed [here](https://tomik-z-cech.github.io/PP1-Cibo-Fresco/) .

![Mockup](/docs/mockup.png)
---
# **Site map**
![Site Map](/docs/site-map.png)
---

# **Features**

## **Features used in every HTML document**

### **Header**
- Header contains a Logo section *(appendix 1)* which is also used as a link to Home page `index.html` in the left top corner and Menu section *(appendix 2)* for easy navigation through all the pages. Menu is designed to change to "hamburger menu" *(appendix 3)* when the resolution changes to less than 1140 pixels in width.
- Header is designed to have fixed position on top of page `top: 0px` through all browsing.
- Header is designed to cover full width `width: 100%` of the browsing window.

*Appendix 1 - Logo*

![Header - Logo](/docs/appendix1.png)

*Appendix 2 - Menu*

![Header - Menu](/docs/appendix2.png)

*Appendix 3 - "Hambuger menu"*

![Header - Hamburger Menu](/docs/appendix3.png)

### **Footer**
- Footer is designed to reveal basic contact details *(appendix 4)* to **Cibo Fresco** restaurant on left side, phone number and email address are constructed to be clickable links that are very useful espeacilly for mobile phone users. Right hand side of footer *(appendix 5)* is designed to bring the user to Social networks web pages (Facebook, Twitter, Instagram) via links that open in new browser tabs.
- Footer is designed to have fixed position on the bottom of page `bottom: 0px` through all browsing.
- Footer is designed to cover full width `width: 100%` of the browsing window.

*Appendix 4 - Contact details*

![Footer - Contact details](/docs/appendix4.png)

*Appendix 5 - Social links*

![Footer - Social links](/docs/appendix5.png)

### **Favicon**
- Every HTML document in this project is equipped with Favicon. This is to ease navigation for user in case of more tabs opened. Picture of *pizza slice* was selected asfavicon. 

*Appendix 6 - Favicon*

![Footer - Contact details](/docs/favicon.png)

### **404.html**
- This project is designed to have custom `404.html` page. In case of user clicks on broken link user isn't completely "cut off" from browsing, instead a page with header and footer appears and user is informed of the situation. 

*Appendix 7 - 404.html*

![Footer - Contact details](/docs/404.png)

## Individual HTML documents

### **Home Page**

- **File :** `index.html`
- **Title :** `Cibo Fresco ¦ Home`
- **User :** Suggests to users that page they are going to browse is a presentation of Italian restaurant that only uses fresh ingredients to prepare traditional dishes *(appendix 8)*.
- **Development :** Animation on home page is done used CSS. `@keyframes content-zoom { from { transform: scale(1); } to { transform: scale(1.2); } }`.

*Appendix 8 - Home page*

![Home page - screenshot](/docs/appendix6.png)

### **Reservation Page**

- **File** : `reserve.html`
- **Title** : `Cibo Fresco ¦ Reservation`
- **User** : User is able to book a table in **Cibo Fresco** restaurant *(appendix 9)*. This function isn't available at the time of building this project, it does give user imaginary booking number. The form is looking for reservation details also the customer details. Except of one, all form fields a required to be filled `<input ... required/>`.
- **Development :**
  - After clicking submit button, user is linked to `succes.html`
  - Each input field uses appropriate type. `<input type="...">`. This vary between text, date and email.
  - Input filed for time is contruated with `<select> <option> ... </option> </select>` as I needed to aim only specific times of the day, `<input type="time">` couldn't be used. 

*Appendix 9 - Reservation page*

![Reservation page - screenshot](/docs/appendix7.png)
