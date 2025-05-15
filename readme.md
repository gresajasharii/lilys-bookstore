# Online Quiz Application

**Lily's Bookstore** is a responsive e-commerce web application built to simulate a charming online bookstore. Users can browse books by genre, add items to a cart, and simulate the shopping experience. It features genre filtering, local storage-based cart persistence, and a clean, accessible interface.



# Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Project Structure](#project-structure)
5. [Screenshots](#screenshots)
6. [Hosting](#hosting)


# Features

- **Add to Cart:** Books can be added to a shopping cart with persistent totals.
- **Genre Filtering**: Browse books by multiple categories such as Fiction, STEM, Poetry, and more.
- **Local Storage**: Shopping cart state is saved across sessions.
- **Responsive Design**: Looks great on mobile, tablet, and desktop.
- **Google Maps Integration**: Embedded location of the bookstore.
- **SVG Logo**: Custom vector logo built with inline SVG.



# Technologies Used

- **HTML5**  
- **CSS3 + Flexbox + Media Queries**  
- **Bootstrap 5**  
- **Font Awesome**  
- **JavaScript**
- **LocalStorage API**
- **SVG & iFrame Embeds** 


# Installation

This is a frontend-only project. To run it locally:

- *Clone the Repository: git clone:*    
https://github.com/gresajasharii/quiz_app
- *cd bookstore*
- *open app.html*


# Project Structure

These functions handle the core interactivity of the bookstore app:

- `addToCart(price, title)`  
  Adds a book to the cart and updates both the UI and localStorage.

- `renderCart()`  
  Renders all items in the cart to the cart section and updates total.

- `updateMiniCartTotal()`  
  Syncs the top navbar mini-cart total with the cart's total value.

- `clearCart()`  
  Clears the cart from localStorage and resets the cart display.

- `showGenre(genre)`  
  Dynamically shows the selected book genre and hides others.

# Screenshots

This is the first screen users see. A carousel with bookstore-themed images invites visitors to explore the collection. The "SHOP NOW" button scrolls directly to the book genres.


![Home Page Carousel](/assets/1.PNG)


After entering the email student@student.uni-pr.edu, the application displays the quiz questions with two options: True and False. Users have the ability to navigate to the previous question to revise their answers if needed.

![Genre Browsing](/assets/2.PNG)


Clicking “Add to Cart” updates the mini cart in the navbar and adds the book to the cart list. The cart section at the bottom of the page shows all selected books, with the total dynamically updated and persisted using LocalStorage.

![Add to Cart & Cart View](/assets/3.PNG)


The Contact section includes a map showing the bookstore’s location and a modern form where users can submit messages after accepting data collection consent.

![Google Map & Contact Form](/assets/4.PNG)

# Hosting

The project is hosted on:


