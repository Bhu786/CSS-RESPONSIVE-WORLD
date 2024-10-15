# CSS-RESPONSIVE-WORLD


#MAKE IMAGE RESPONSIVE A/Q TO DIV/CONTAINER

CSS


# CSS Guidelines

## Centering a div
If you have a div and want to center it, apply the following style to the parent div:

div ki ankar koi div hai toh usko centre karna ho toh
{parent div ki upar yeh wala stylr laaga dege}

```css
display: flex;
justify-content: center;
align-items: center;
```

---

## Responsive Image Size
To ensure the image scales down properly while maintaining its aspect ratio:

```css
.card-img-top {
  max-width: 100%; /* Ensure image scales down properly */
  height: auto;    /* Maintain aspect ratio */
}
```

---

## Removing Bullets from an Unordered List
If you want to remove the default bullets from a list, you can use:

```css
ul {
  list-style-type: none; /* Removes the bullets */
  padding: 0;           /* Optional: Remove default padding */
  margin: 0;            /* Optional: Remove default margin */
}
```

---

## Adding Opacity to an Image
To add opacity on top of an image:

image ki upar opacity lagana ho toh 

```css
background: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.5)), 
url('../Assets/background.png');
background-size: cover;
```

## Remove Border of Button




```css
border:none
```





## Best button style 
```css
button {
  padding: 10px 20px;
  background-color: #3498db;
  border: none;
  color: white;
  cursor: pointer;
  transition: all 0.3s ease; /* Add smooth transition */
}

button:hover {
  transform: scale(1.05); /* Scale the button slightly */
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3); /* Add shadow */
  background-color: #2980b9; /* Change background color */
}


```


















