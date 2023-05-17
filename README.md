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
- Header is semi-transparent using `background-color: rgba(228, 180, 85, 0.85);`.

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
- Footer is semi-transparent using `background-color: rgba(228, 180, 85, 0.85);`.

*Appendix 4 - Contact details*

![Footer - Contact details](/docs/appendix4.png)

*Appendix 5 - Social links*

![Footer - Social links](/docs/appendix5.png)

### **Favicon**
- Every HTML document in this project is equipped with Favicon. This is to ease navigation for user in case of more tabs opened. Picture of *pizza slice* was selected asfavicon. 

*Appendix 6 - Favicon*

![Footer - Contact details](/docs/favicon.png)

### **404.html**
- This project is designed to have custom `404.html` page *(appendix 7)*. In case of user clicks on broken link user isn't completely "cut off" from browsing, instead a page with header and footer appears and user is informed of the situation. 

*Appendix 7 - 404.html*

![Footer - Contact details](/docs/404.png)

### **Scrollbar**
- This project is designed to browse majority of pages without scrolling bar from Food Menu and Drink Menu as they are long. Custom scroll bar was used to fit within the color theme within the project.

*Appendix 8 - Scrollbar*

![Scrollbar](/docs/scrollbar.png)

## Main HTML documents

### **Home Page**

- **File :** `index.html`
- **Title :** `Cibo Fresco ¦ Home`
- **User :** Suggests to users that page they are going to browse is a presentation of Italian restaurant that only uses fresh ingredients to prepare traditional dishes *(appendix 9)*.
- **Development :** Animation on home page is done used CSS. `@keyframes content-zoom { from { transform: scale(1); } to { transform: scale(1.2); } }`.

*Appendix 9 - Home page*

![Home page - screenshot](/docs/appendix6.png)

### **Reservation Page**

- **File** : `reserve.html`
- **Title** : `Cibo Fresco ¦ Reservation`
- **User** : User is able to book a table in **Cibo Fresco** restaurant *(appendix 10)*. This function isn't available at the time of building this project, it does give user imaginary booking number. The form is looking for reservation details also the customer details. Except of one, all form fields a required to be filled `<input ... required/>`.
- **Development :**
  - After clicking submit button, user is linked to `succes.html`
  - Each input field uses appropriate type. `<input type="...">`. This vary between text, date and email.
  - Input filed for time is contruated with `<select> <option> ... </option> </select>` as I needed to aim only specific times of the day, `<input type="time">` couldn't be used. 

*Appendix 10 - Reservation page*

![Reservation page - screenshot](/docs/appendix7.png)

### **Food Menu Page**

- **File** : `food-menu.html`
- **Title** : `Cibo Fresco ¦ Food Menu`
- **User** : User is able to browse the food dishes that **Cibo Fresco** restaurant is offering *(appendix 11)*.
- **Development :** This page requiered unordered lists `<ul>` and round CSS containers `border-radius: 50%;`

*Appendix 11 - Food Menu Page*

![Food Menu page - screenshot](/docs/food-menu.png)

### **Drink Menu Page**

- **File** : `drink-menu.html`
- **Title** : `Cibo Fresco ¦ Drink Menu`
- **User** : User is able to browse the drink menu that **Cibo Fresco** restaurant is offering *(appendix 12)*.
- **Development :** This page requiered unordered lists `<ul>` and round CSS containers `border-radius: 50%;`

*Appendix 12 - Drink Menu Page*

![Drink Menu page - screenshot](/docs/drink-menu.png)

### **Gallery Page**

- **File** : `gallery.html`
- **Title** : `Cibo Fresco ¦ Gallery`
- **User** : User is able to browse the selection of pictures of famous **Cibo Fresco** restaurant visitors *(appendix 13)*. User is able to enlarge each picture and navigate between them using naviagtion bar *(appendix 14)*.
- **Development :** 
  - This page requiered round CSS containers `border-radius: 50%;`
  - Each picture in round container is a link to a page with enlarged picture page *(appendix 15)* and a navigation bar *(appendix 14)* that allows the user to navigate between sub-pages `gallery-1.html, gallery-2.html, gallery-3.html, gallery-4.html`.

*Appendix 13 - Gallery Page*

![Gallery page - screenshot](/docs/gallery.png)

*Appendix 14 - Gallery Navigation Bar*

![Navigation Bar - screenshot](/docs/navbar.png)

*Appendix 15 - Enlarged Gallery Picture*

![Enlarged Gallery Picture page - screenshot](/docs/enlarged.png)

### **Contact Page**

- **File** : `contact.html`
- **Title** : `Cibo Fresco ¦ Contact`
- **User** : User is able to avail basic contact informatin of **Cibo Fresco** restaurant including phone number, e-mail address, opening times, physical address and map *(appendix 16)*.
- **Development :** The links with phone number and e-mail address, same as in footer are designed for direct phone call, direct e-mail function respectively using `<a href="tel:...">` and `<a href="mailto:...">`. This is very useful browsing the page on mobile phone device.

*Appendix 16 - Contact Page*

![Contact page - screenshot](/docs/contact.png)

### **Succesful Reservation Page**

- **File** : `succes.html`
- **Title** : `Cibo Fresco ¦ Reservation succesful`
- **User** : User gets confirmation of succesful booking within **Cibo Fresco** restaurant *(appendix 17)*.
- **Development :** As mentioned earlier in this documentation file, this is only a dummy page. Full booking system needs further development.

*Appendix 17 - Successful reservation Page*

![Reservation Successful - screenshot](/docs/succes.png)

---

# Wireframes
| Name of page | Wireframe PC | Wireframe Phone
|--|--|--|
| **index.html** | *appendix 18* | *appendix 19*  |
| **food.html** | *appendix 20* | *appendix 21*  |
| **drink.html** | *appendix 22* | *appendix 23*  |
| **reserve.html** | *appendix 24* | *appendix 25*  |
| **gallery.html** | *appendix 26* | *appendix 27*  |
| **contact.html** | *appendix 28* | *appendix 29*  |

*Appendix 18 - Wireframe - index.html PC*

![Appendix 18 - Wireframe - index.html PC](docs/home-pc.png)


*Appendix 19 - Wireframe - index.html Phone*

![Appendix 19 - Wireframe - index.html Phone](docs/home-phone.png)


*Appendix 20 - Wireframe - food.html PC*

![Appendix 20 - Wireframe - index.html PC](docs/food-pc.png)


*Appendix 21 - Wireframe - food.html Phone*

![Appendix 21 - Wireframe - index.html Phone](docs/food-phone.png)


*Appendix 22 - Wireframe - drink.html PC*

![Appendix 22 - Wireframe - drink.html PC](docs/drink-pc.png)


*Appendix 23 - Wireframe - drink.html Phone*

![Appendix 23 - Wireframe - drink.html Phone](docs/drink-phone.png)


*Appendix 24 - Wireframe - reserve.html PC*

![Appendix 24 - Wireframe - reserve.html PC](docs/reserve-pc.png)


*Appendix 25 - Wireframe - reserve.html Phone*

![Appendix 25 - Wireframe - reserve.html Phone](docs/reserve-phone.png)

*Appendix 26 - Wireframe - gallery.html PC*

![Appendix 26 - Wireframe - gallery.html PC](docs/gallery-pc.png)


*Appendix 27 - Wireframe - gallery.html Phone*

![Appendix 27 - Wireframe - gallery.html Phone](docs/gallery-phone.png)


*Appendix 28 - Wireframe - contact.html PC*

![Appendix 28 - Wireframe - contact.html PC](docs/contact-pc.png)


*Appendix 29 - Wireframe - contact.html Phone*

![Appendix 29 - Wireframe - contact.html Phone](docs/contact-phone.png)

---

# **Technologies**
## Technologies used to develop and deploy this project

- **Balsamiq** - to create wireframes.
- **HTML** - main programming language for this project
- **CSS** - styling the project via external CSS file `/asssets/css/styles.css` 
- **CodeAnywhere** - to write and save the code
- **GitBash** - to make commitments of progress and push the results back to GitHub
- **ConText** - code off-line in "doodle-zone" mode
- **GitHub** - to record all commitments and deployment the live project
- **FontAwesome** - to find and use icons
- **TinyPNG** - to compress images
- **FavIcon.io** - to find and compress favicon
- **StackEdit** - used to preview and write portions of `readme.MD` file
