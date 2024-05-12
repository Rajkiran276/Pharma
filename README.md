# Ex.10 Responsive Web Design using Bootstrap
## Date:12/05/2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```C
main.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - Reddy'sCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">Reddy'sCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/main.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to  Dr. Reddy's Laboratories</h1>
        <p>Welcome to  Dr. Reddy's Laboratories, your trusted source for high-quality pharmaceutical products. We are dedicated to improving the health and well-being of our customers by providing safe and effective medications.</p>
        <p>At Dr. Reddy's Laboratories, we offer a wide range of prescription and over-the-counter medications to meet your healthcare needs. Whether you're managing a chronic condition or simply looking for relief from minor ailments, we have the products you need.</p>
        <p>In addition to medications, we also carry a variety of healthcare products and accessories, including vitamins, supplements, first aid supplies, and more. Our knowledgeable staff is here to assist you with any questions you may have and to ensure you find the right products for your needs.</p>
        <p>Thank you for choosing PharmaCompany for your healthcare needs. We look forward to serving you and helping you live a healthier life.</p>
      </div>
      <div class="col-md-4">
        <img src="C:\Users\Rajkiran\Downloads\tablet.jpg" class="img-fluid" alt="Pharmacy Image">
      </div>
    </div>
  </div>
  <body background="C:\Users\Rajkiran\Downloads\bacground.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 Reddy'sCompany. All rights reserved. BY RAJKIRAN.J(212222043006)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```C
about.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Reddy'sCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">Reddy'sCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#NUTRITION STORY">NUTRITION STORY</a>
            <a class="dropdown-item" href="#VISION">VISION</a>
            <a class="dropdown-item" href="#VALUES">VALUES</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>About Reddy'sCompany</h1>
        <div id="NUTRITION STORY">
          <h2>NUTRITION STORY</h2>
          <p>These simple words describe the deep-rooted belief that drives us. Sometimes, the simplest words describe the most profound truths.</p>
        </div>
        <div id="VISION">
          <h2>VISION</h2>
          <p>Scientist and entrepreneur Dr. K Anji Reddy established Dr. Reddy’s Laboratories with the vision to make medicines accessible to everyone.</p>
        </div>
        <div id="VALUES">
          <h2>VALUES</h2>
          <ul>
            <li>Quality: We are committed to maintaining the highest standards of quality in everything we do.</li>
            <li>Integrity: We conduct our business with honesty, transparency, and ethical behavior.</li>
            <li>Innovation: We strive to continuously innovate and improve our products and services to better serve our customers.</li>
            <li>Customer Focus: We are dedicated to understanding and meeting the needs of our customers.</li>
            <li>Teamwork: We work together as a team to achieve our goals and deliver exceptional results.</li>
          </ul>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>
  <body background="C:\Users\Rajkiran\Downloads\bacground.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 Reddy'sCompany. All rights reserved.  BY RAJKIRAN.J(212222043006)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```C
product.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products - Reddy'sCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">Reddy'sCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/main.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/about.html">About</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/product.html">Products <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <img src="C:\Users\Rajkiran\Downloads\product1.jpg" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 1</h5>
              <p class="card-text">Adalimumab is used to treat various autoimmune conditions such as rheumatoid arthritis, ankylosing spondylitis, psoriasis, psoriatic arthritis, Crohn disease, and ulcerative colitis..</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="C:\Users\Rajkiran\Downloads\product2.jpg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 2</h5>
              <p class="card-text">Non-valvular atrial fibrillation to reduce the risk of stroke and blood clots</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="C:\Users\Rajkiran\Downloads\product2.jpg" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 3</h5>
              <p class="card-text">Lenalidomide is used to treat anemia (low red blood cells) in patients with a certain type of myelodysplastic syndrome (MDS).</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 Reddy'sCompany. All rights reserved.  BY RAJKIRAN.J(212222043006)</p>
  </footer>
  <body background="C:\Users\Rajkiran\Downloads\bacground.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```C
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">Reddy'sCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/main.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/product.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>Reddy'sCompany</h2>
        <address>
          <strong>Address:</strong><br>
          123 xyz street, Chennai<br>
          India, 632007<br><br>
          <strong>Email:</strong><br>
          info@Reddy'scompany.com<br><br>
          <strong>Phone:</strong><br>
          +1432789560
        </address>
      </div>
    </div>
  </div>
  <body background="C:\Users\Rajkiran\Downloads\bacground.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 Reddy'sCompany. All rights reserved.  BY RAJKIRAN.J(212222043006)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```


## OUTPUT:
![Screenshot (95)](https://github.com/Rajkiran276/Pharma/assets/147471453/5f4c9b0c-be44-4fc7-a87c-7ac477344488)
![Screenshot (96)](https://github.com/Rajkiran276/Pharma/assets/147471453/0fbb5a63-a889-4596-97fd-dfe70edce31d)
![Screenshot (97)](https://github.com/Rajkiran276/Pharma/assets/147471453/18a1322f-b25e-4274-97fa-2590ee836d70)
![Screenshot (98)](https://github.com/Rajkiran276/Pharma/assets/147471453/fdd61256-404b-40d5-bd6f-40d648292a0c)

## RESULT:
The program for responsive web design using Bootstrap is completed successfully.
