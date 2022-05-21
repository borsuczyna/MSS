# What is MSS?
MSS is advanced MTA CSS library that allows you to load CSS without any performance lost, **for now it doesn't contain all CSS functions**

# Installation
Unpack mss to MTA resources folder

# Style functions
<details>
   <summary>X Position</summary>
   
   ```css
   x: size unit;
   /* Changes relative x position,
      if using % uses given percent of width */

   main {
       background-color: rgb(15,15,15);
       border: 1px solid rgb(255,255,255,155);
   }

   main:hover {
       x: -20px;

       transition: .2s;
   }
   ```
   ![Example](https://user-images.githubusercontent.com/65825775/169347399-d84818c1-50f1-4f42-bb7c-a08fbb7bf998.gif)

</details>
<details>
   <summary>Y Position</summary>
   
   ```css
   y: size unit;
   /* Changes relative y position,
      if using % uses given percent of height */

   main {
       background-color: rgb(15,15,15);
       border: 1px solid rgb(255,255,255,155);
   }

   main:hover {
       y: -10%;

       transition: .2s;
   }
   ```
   ![Example](https://user-images.githubusercontent.com/65825775/169348174-330ce1c3-c6b4-4c53-9d00-79e4fb23417b.gif)
 
</details>
<details>
   <summary>Width</summary>
   
   ```css
   width: size unit;
   /* Changes element width,
      if using % uses given percent of default width (given by script not CSS) */

   main {
       background-color: rgb(15,15,15);
       border: 1px solid rgb(255,255,255,155);
   }

   main:hover {
       x: 5%;
       width: -10%;

       transition: .2s;
   }
   ```
   ![Example](https://user-images.githubusercontent.com/65825775/169348523-905c92dc-95d7-4e6a-a7a8-837e2cc70d00.gif)
   
</details>
<details>
   <summary>Height</summary>
   
   ```css
   height: size unit;
   /* Changes element height,
      if using % uses given percent of default height (given by script not CSS) */

   main {
       background-color: rgb(15,15,15);
       border: 1px solid rgb(255,255,255,155);
   }

   main:hover {
       height: 10%;

       transition: .2s;
   }
   ```
   ![Example](https://user-images.githubusercontent.com/65825775/169348834-e740a822-d3d3-40e4-9740-948f6637be99.gif)
  
</details>
<details>
   <summary>Border radius</summary>

   ```css
   border-radius: size unit;
   /* Changes element border radius,
      if using % uses given percent of default width or height (smaller one, given by script not CSS) */

   main {
       background-color: rgb(15,15,15);
       border: 1px solid rgb(255,255,255,155);
       border-radius: 10%;
   }

   main:hover {
       border-radius: 40%;

       transition: .2s;
   }
   ```
   ![Example](https://user-images.githubusercontent.com/65825775/169349202-2968aa6e-cab8-4903-be3d-39873018df7b.gif)
   
</details>

<details>
   <summary>Background color</summary>
      
   ```css
   background-color: color format;
   /* Changes element background color, accepts text color, hex (#rrggbb, #rrggbbaa), rgb and rgba */

   main {
       background-color: rgb(15,15,15);
       border: 1px solid rgb(255,255,255,155);
   }

   main:hover {
       background-color: red;

       transition: .2s;
   }
```

![Example](https://user-images.githubusercontent.com/65825775/169349724-93b0826e-8064-40c3-8fb2-c08b5b854589.gif)
</details>
<details>
   <summary>Border</summary>
   
   ```css
   border: size unit, border type, color format;
   
   main {
       background-color: rgb(15,15,15);
       border: 3px solid lime;
      border-radius: 30%;
   }

   main:hover {
      border: 8px solid red;

       transition: .2s;
   }
   ```
   ![Example](https://user-images.githubusercontent.com/65825775/169666810-d99b8b6b-9631-4fb0-a029-641f77af2c71.gif)
</details>
<details>
   <summary>Text color</summary>
   
   ```css
   color: color format;
   
   main {
       background-color: rgb(15,15,15);
       border: 1px solid rgb(255,255,255,155);
      font-size: 30px;
      color: white;
   }

   main:hover {
      color: red;

       transition: .2s;
   }
   ```
   ![Example](https://user-images.githubusercontent.com/65825775/169666914-83382423-1a4d-41eb-8608-2256e839e68c.gif)
</details>
<details>
   <summary>Text align</summary>
   
   ```css
   main {
      background-color: rgb(15,15,15);
      border: 1px solid rgb(255,255,255,155);
      font-size: 30px;
      color: white;
      text-align: left;
   }

   main:hover {
      text-align: right;

       transition: .2s;
   }
   ```
   ![Example](https://user-images.githubusercontent.com/65825775/169667051-3ffd8fb8-a288-43cf-936a-55cfe32875e4.gif)
</details>
