# Octa-net-task-1
<!DOCTYPE html>
<html>
<head>
    <title>Audi Car-Themed Website</title>
    <style>
*{
    margin: 0; 
    padding:0;
} 
html{
    scroll-behavior: smooth;
}
.logo{ 
width:20%; 
display: flex; 
justify-content: center; 
align-items: center;

} 
.logo img{
    width: 33%;

}

.navbar{ 
           display: flex;
           align-items: center;
           justify-content: center;
           position: sticky;
           top: 0;
           cursor: pointer;
       }
        /* Define styles for columns */
        .column {
            width: 33.33%;
            float: left;
            padding: 10px;
            box-sizing: border-box;
        }

        /* Clear floats after columns */
        .row:after {
            content: "";
            display: table;
            clear: both;
        }

        /* Style for header and footer */
        .header, .footer {
            background-color: #7a9ca2;
            color: rgb(92, 52, 98);
            padding: 10px;
            text-align: center;
        }

        /* Style for main content section */
        .content {
            padding: 20px;
        }
        
        /* Style for Audi car items */
        .audi-car-item {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px;
            text-align: center;
            background-color: #a6c391;
        }
        
        /* Style for car images */
        .car-image {
            max-width: 100%;
            height: auto;
        }

    </style>
</head>
<body>
    <div class="header">
        <h1>Audi Car-Themed Website</h1>
    </div>
    
    <nav class="navbar background">
        <ul class="nav-list">
              <div class="logo"><img src="background.avif" alt="logo" srcset=""></div>
              <li><a href="#contact">CONTACT US</a></li>  
          </ul>
          <div class="rightnav">
              <input type="text" name="search" id="search">
              <button class="btn btn-sm">search</button>
          </div>
      </nav>

    <div class="row">
        <div class="column">
            <h2>New Arrivals</h2>
            <div class="audi-car-item">
                <h3>Audi A3</h3>
                <img class="car-image" src="audi_a3.jpg" alt="Audi A3">
                <p>The Audi A3 - A perfect blend of style and performance.</p>
            </div>
            <div class="audi-car-item">
                <h3>Audi Q5</h3>
                <img class="car-image" src="Audi-Q5.webp" alt="Audi Q5">
                <p>The Audi Q5 - Luxury SUV with cutting-edge features.</p>
            </div>
        </div>
        <div class="column">
            <h2>Popular Models</h2>
            <div class="audi-car-item">
                <h3>Audi A6</h3>
                <img class="car-image" src="Audi-A6.jpg" alt="Audi A6">
                <p>The Audi A6 - Elegance, performance, and technology combined.</p>
            </div>
            <div class="audi-car-item">
                <h3>Audi Q7</h3>
                <img class="car-image" src="audi Q7.jpg" alt="Audi Q7">
                <p>The Audi Q7 - Uncompromising luxury and versatility.</p>
            </div>
        </div>
        <div class="column">
            <h2>Featured Cars</h2>
            <div class="audi-car-item">
                <h3>Audi RS5</h3>
                <img class="car-image" src="audi rs5.webp" alt="Audi RS5">
                <p>The Audi RS5 - High-performance sports coupe.</p>
            </div>
            <div class="audi-car-item">
                <h3>Audi e-tron</h3>
                <img class="car-image" src="audi e tron GT.jpg" alt="Audi e-tron">
                <p>The Audi e-tron - All-electric SUV, a new era of mobility.</p>
            </div>
        </div>
    </div>

    <div class="content">
        <h2>About Audi</h2>
        <p>Experience the world of Audi, where luxury, innovation, and performance converge to create a driving experience like no other.</p>
    </div>

    <div class="footer">
        <p>&copy; 2023 Audi Car-Themed Website. All rights reserved.</p>
    </div>
</body>
</html>

