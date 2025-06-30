<html> 
    <head>
    <title>
          Kiseki Group
    </title>
    <style> 
    
        body {
            margin: 0; 
            
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
         .nav-menu {
            display: flex;
            gap: 40px;
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
        .content {
            padding-top: 70px; /* To avoid overlap with fixed navbar */
            text-align: center;
        } 
    </style>
    </head>
    
    
    <header>
        <nav id="nav-bar">
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
            <div class="content">
            </div>
        </nav>
    </header><br>
    <body>
         
    </body>
</html>
