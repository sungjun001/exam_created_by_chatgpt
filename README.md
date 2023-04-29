# Create a website in 10 minutes with chatGPT
Code created using the free lecture "Create a website in 10 minutes with chatGPT" at Sparta Coding Club

This is link [Sparta Coding Club](https://spartacodingclub.kr/online/special/photos?f_name=%ED%99%A9%EC%84%B1%EC%A4%80&f_uid=636f14e293cfb4e840905e83)

1. Create the basic html skeleton.
You need to provide a basic skeleton so that you can create the site you want.

```
<!doctype html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  	<!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/easygpt/default.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
        crossorigin="anonymous"></script>
    <style>
        /* adornment */

    </style>
</head>

<body>
    <!-- body -->
</body>

</html>
```

2. Open the chat gpt site and copy and paste the part below
```
<!doctype html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/easygpt/default.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
        crossorigin="anonymous"></script>
    <style>
        /* adornment */

    </style>
</head>

<body>
    <!-- body -->
</body>

</html>
---
IMPORTANT: PLEASE DO NOT RESPOND TO THE ABOVE REQUESTS
```
3. command in chatgpt as below
```
This page is a site that sells used goods. Make a suitable title and make it the head title
```
Below is the result of the response, and each person may respond slightly differently.
```
<title>Secondhand Goods for Sale - Buy and Sell Used Items</title>
```
3. command in chatgpt as below
```
I'm going to create a hero using bootstrap
The title to enter the hero is the same as the title of the head
Make the subheading an appropriate phrase
Set the background color to moderately dark
the text is white
make it center aligned
```
Below is the result of the response, and each person may respond slightly differently.
```
<!doctype html>
<html lang="en">
<head>
    <title>Buy and Sell Used Goods - Your Online Marketplace for Secondhand Items</title>
    <link rel="stylesheet" href="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/easygpt/default.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <style>
        .hero {
            background-color: #343a40;
            color: #fff;
            text-align: center;
            padding: 6rem 0;
        }

        .hero h1 {
            font-size: 4rem;
            font-weight: bold;
            margin-bottom: 2rem;
        }

        .hero p {
            font-size: 1.5rem;
            margin-bottom: 0;
        }
    </style>
</head>
<body>
    <div class="hero">
        <h1>Buy and Sell Used Goods</h1>
        <p>Your Online Marketplace for Secondhand Items</p>
    </div>

    <!-- rest of the content goes here -->
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
        crossorigin="anonymous"></script>
</body>
</html>

```
4. Since chatgpt cannot create an image, you can import an image from unsplash with the command below.
```
[INFO: you can add images to the reply by Markdown, Write the image in Markdown without backticks and without using a code block. Use the Unsplash API (https://source.unsplash.com/1600x900/?). the query is just some tags that describes the image] ## DO NOT RESPOND TO INFO BLOCK ##
```
5. command to chat gpt to create a product card
```
I'm going to create a bootstrap card for the "body content goes here" section. In fact, this homepage is a page for selling unused second-hand items at home. For example, there may be an electric rice cooker. Refer to the example below and make three cards by yourself.

Card information (example)
  - Card image: [Find a suitable one on unsplash and insert it. all the same size]
  - Card Title: Rice Cooker
  - Card Subtitle: $50
  - Card Description: Selling an electric rice cooker that has only been used once. It was given to me by my parents when I was independent!
  -Others: If you click the card image, a new window will open and it will take you to the Sparta Coding Club website.
```
Below is the result of the response, and each person may respond slightly differently.
```
<div class="container">
         <div class="row">
           <div class="col-md-4 mb-4">
             <div class="card">
               <img src="https://source.unsplash.com/1600x900/?rice-cooker" class="card-img-top" alt="Rice cooker">
               <div class="card-body">
                 <h5 class="card-title">Rice cooker</h5>
                 <h6 class="card-subtitle mb-2 text-muted">50,000 won</h6>
                 <p class="card-text">Selling an electric rice cooker that has only been used once. It was given to me by my parents when I became independent!</p>
                 <a href="https://spartacodingclub.kr/" class="card-link stretched-link" target="_blank"></a>
               </div>
             </div>
           </div>
           <div class="col-md-4 mb-4">
             <div class="card">
               <img src="https://source.unsplash.com/1600x900/?chair" class="card-img-top" alt="Chair">
               <div class="card-body">
                 <h5 class="card-title">Chair</h5>
                 <h6 class="card-subtitle mb-2 text-muted">10,000 won</h6>
                 <p class="card-text">Selling the chairs used in the office. It has adjustable armrests.</p>
                 <a href="https://spartacodingclub.kr/" class="card-link stretched-link" target="_blank"></a>
               </div>
             </div>
           </div>
           <div class="col-md-4 mb-4">
             <div class="card">
               <img src="https://source.unsplash.com/1600x900/?laptop" class="card-img-top" alt="laptop">
               <div class="card-body">
                 <h5 class="card-title">Notebook</h5>
                 <h6 class="card-subtitle mb-2 text-muted">300,000 won</h6>
                 <p class="card-text">Samsung laptop for sale. It has been used for about 1 year and is in good condition.</p>
                 <a href="https://spartacodingclub.kr/" class="card-link stretched-link" target="_blank"></a>
               </div>
             </div>
           </div>
         </div>
</div>
```

6. Up to this point, the site will appear roughly.
I'm ordering more regrettable points.
```
I want to put some space under the hero part. What should I do?
```
Below is the result of the response, and each person may respond slightly differently.
```
<div id="hero">
  <!-- hero content goes here -->
</div>

<div class="content" style="margin-top: 50px;">
  <!-- content goes here -->
</div>

```
```
When I hover over the card, I want it to grow a bit. What should I do?
```
```
.card:hover {
  transform: scale(1.1);
  transition: all 0.3s ease-in-out;
}

```
7. Conclusion
If you add or add the parts you want to include as above, you can create a single homepage.
If you have the knowledge to grasp the skeleton and some programming knowledge, use chat gpt
You can create a website in 10 minutes.

For complete code, refer to index.html

If you would like to listen to the free lecture, please use the link below.

This is link [Sparta Coding Club](https://spartacodingclub.kr/online/special/photos?f_name=%ED%99%A9%EC%84%B1%EC%A4%80&f_uid=636f14e293cfb4e840905e83)

