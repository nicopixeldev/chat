# Gatsby
[Gatsby](https://github.com/gatsbyjs/gatsby).

[gatsby-starter-lumen](https://github.com/alxshelepenok/gatsby-starter-lumen)

## Table of Contents  
[Gatsby Pages](#Pages)  
[Link](#Link)

## Pages
+ The `/src/pages` will represent all pages of our Gatsby site
+ `/src/pages/index.js` is our HOME 
+ For example, the `blog.js` page is accesible by `/blog` URI

## Link
`Link` provides two options for adding styles to the active link
+ activeStyle — a style object that will only be applied when the current item is active
+ activeClassName — a class name that will only be added to the Link when the current item is active

```jsx
    <Link
      to="/"
      {/* This assumes the `active` class is defined in your CSS */}
      activeClassName="active"
    >
      Home
    </Link>
    <Link
      to="/about/"
      activeStyle={{ color: "red" }}
    >
      About
    </Link>
```



## GraphQL
3 main operations we can perform:




```jsx

```
