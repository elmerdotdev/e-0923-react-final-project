# E-0923 React Final Project

Goal: Create a shopping website with your category of choice (electronics, food, clothes, toys, etc.)

## Installation

Create a NextJS project with `npx create-next-app@14.1.0`. Use this version instead of the latest version (14.2.0) as it still has problems on Windows.

## Requirements

- Your website should created using NextJS.
- You must use an in-memory database stored in the backend.
- Your website should have these pages:

  - Home
  - Products List with images and Add to Cart button
  - Add Product page
  - Edit Product page
  - View Product Detail page
  - View Cart page
  - About page
  - Contact Us with a working form

- The website should have CRUD functionality (Create, Retrieve, Update, Delete). Use **Server Actions**.
- The website must be mobile responsive.
- For the product images, use Cloudinary API to store your images and save the image url into your in-memory database [https://cloudinary.com/]. Just use the free plan.
- You must have a Shopping Cart sidebar showing the products you added to cart. The same products will appear on the View Cart page.
- Clicking on the product image on the Product List page should open a modal showing the product image. On the modal, you can display details like Product Name, Product Price, Product Image, Add to Cart button.

## Tips

- Please check out Behance [https://www.behance.net/] for some inspiration for your design. But I will focus more on the functionality.
- If you are going to use a Google Font, NextJS can support it [https://nextjs.org/docs/app/building-your-application/optimizing/fonts#google-fonts]
- Use `<Image />` component for your product images

## Presentation

Presentation will be on April 22, 2024. Each team needs to present their project with a minimum of 10 minutes.
