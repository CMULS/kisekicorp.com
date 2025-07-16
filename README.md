<html> 
    <head>
    <title>
          Kiseki Group
    </title>
    <style> 
    
        body {
            margin: 0; 
            
         } 
        h1 { 
          margin-bottom: 80px;
          }
         #nav-bar {
            position: fixed;
            top: 0; 
            width: 100%;
            height: 90px;
            background-image: url(https://raw.githubusercontent.com/CMULS/kisekicorp.com/refs/heads/main/Copilot_20250624_144211.png);
            background-position: center;
            display: flex;
            align-items: center;
            padding: 0 20px;
            z-index: 1000;

         } 
            .logo-container {
            flex-shrink: 0;
        } 
       
        .logo {
            height: 80px;
        } 
         .nav-menu {
            display: flex;
            gap: 20px;
            margin-bottom: 20px;
        } 
        .nav-item {
            position: relative;
        } 
        .nav-link {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            display: inline-block;
            background-color: rgba(0, 0, 0, 0.5);
            border-radius: 5px;
        } 
        .dropdown {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            background-color: rgba(0, 0, 0, 0.8);
            min-width: 150px;
            border-radius: 5px;
        } 
        .dropdown a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            display: block;
        } 
        .dropdown a:hover {
            background-color: #444;
        } 
        .nav-item:hover .dropdown {
            display: block;
        } 
        
     .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 40px;
      max-width: 1000px;
      margin: 0 auto 60px auto;
      padding: 0 20px;
    } 
    .service {
      display: flex;
      flex-direction: column;
      align-items: center;
    } 
    .service img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid white;
      transition: transform 0.3s;
    } 
    .service img:hover {
      transform: scale(1.05);
    } 
     .service-title {
      margin-top: 10px;
      font-weight: bold;
      font-size: 14px;
      letter-spacing: 1px;
      text-align: center;
    } 
        
    </style>
    </head>
    
    
    <header>
        <nav id="nav-bar">
         <div class="logo-container">
             <img class="logo" src="https://raw.githubusercontent.com/CMULS/Themes/refs/heads/main/K.png" alt="Piseki Logo" />
         </div>
            <div class="nav-menu">
                <div class="nav-item">
                    <a href="#" class="nav-link">Home</a>
                </div>
                <div class="nav-item">
                    <a href="#" class="nav-link">About</a>
                    <div class="dropdown">
                        <a href="#">Who We Are</a>
                        <a href="#">Our Mission</a>
                        <a href="https://cmuls.github.io/kiseki.org/">Management & Staff</a>
                    </div>
                </div> 
                <div class="nav-item">
                    <a href="#" class="nav-link">Services</a>
                    <div class="dropdown">
                        <a href="#">Business Consultancy</a>
                        <a href="#">Loaning Services</a>
                        <a href="#">Hospitality</a>
                        <a href="#">Farming</a>
                        <a href="#">Online Store</a>
                        <a href="#">Customer Service</a>
                    </div>
                    </div>
                </div>
            </header>
            <body>
            <div class="content">
               <h1>Welcome to Kiseki Group</h1>
           <div class="services-grid">
             <div class="service">
               <img src="https://raw.githubusercontent.com/CMULS/kisekicorp.com/refs/heads/main/WhatsApp%20Image%202025-07-16%20at%2011.46.16_3c4c1133.jpg" alt="Real Estate">
               <div class="service-title">REAL ESTATE</div>
            </div>
            <div class="service">
              <img src="https://raw.githubusercontent.com/CMULS/kisekicorp.com/refs/heads/main/WhatsApp%20Image%202025-07-16%20at%2012.01.46_7d76a00b.jpg" alt="Agriculture">
              <div class="service-title">AGRICULTURE</div>
            </div>
        </nav>
    </body> 
</html>
