<!DOCTYPE html>

<html>
    <head>
        <title>drop down menu</title>
    <style>
        body {
            margin:0px;
            font-family: 'Open Sans', sans-serif, arial; 
        }
        
        #topbar{
            width:100%;
            height:100px;
            background-color: white;
    
        }
        #bar{
            max-width:1200px;
            height:100px;
            margin: 0 auto;
            padding-top:10px;
           
        }
        
        #logo{
            height:100px;
            float:left;
            position:relative;
            bottom:10px; 
            
        }
   
        ul {
            list-style: none;
            margin: 0px;
            color:white;
            text-align: center;
            float:left;
            position:relative;
            top:65px;
            font-size:15px;
            
            
        }
        
        ul li{
            float:left; 
            width: 150px;    
            height:35px;
            text-align: center; 
            line-height: 40px;
            display:block; 
            text-decoration: none; 
            color:Black;
            text-decoration: none;  
        }
        
        ul li a{
            display:block; 
            position: absolute;
            text-align: centre;
            font-size:15px;
            text-decoration: none;
            margin:0;
            width: 150px;    
            height:35px;
            
            
        }
        
        ul li a:hover{
            background-color:#0BC0FF;
            opacity: .6;
            color:white;
            width:150px; 
            height:35px;
            display:block;
        }
      
        ul li ul li{
            display:none;
            background:white;
            opacity: .6;  
        }
        
        ul li:hover ul li{
            display: block;
            text-align: center;
            position:relative;
            right:40px;
            bottom:30px;
            margin:0px;
            width:150px; 
            height:35px;   
            
        }
        
        .clear{
            clear: both;
        }
        
        #middleimage{
            width:100%;
            height:350px;
            overflow:hidden;
            background: cover;
            z-index: auto;
            margin:0px;
            
            
        }
        
        #textpicture-box{
            z-index: 1;
            height:140px;
            width:700px;
            background-color: black;
            position: absolute;
            top:320px;
            left:25px;
            opacity: 0.4;
            color:white;
            border-top-left-radius: 25px;
            
        }
        
        #textpicture{
            font-size: 20px;
            padding:0px 0px 10px 25px;
            
        }
        #middle-section-box{
            height:400px;
            max-width:1400px;
            background: white;
        }
        .middle-section{
            Float:left;
            height:280px;
            width:400px;
            background: white;
        }   
        
        #middle-section-image1{
            position:relative;
            left:80px;
        }    
            
        #middle-section-image2{
            position:relative;
            left:120px;  

        }
        
          #middle-section-image3{
            position:relative;
            left:80px; 
            top:40px;

        }
           
        .middle-section-box-text{
            text-align: center;
            font-size:17px; 
        }  
            
        #middle-section-box-text3{
            position:relative;
            top:40px;  
            right:20px;
               
        }  
        
        .middle-section a{
            text-decoration: none;
            color:#00A1E2;
            position:relative;
            left:150px;
        }
        #middle-section-box-text3-learn{
            position:relative;
            top:40px;    
                
        }
        
        hr{
           position:relative;
           bottom:80px;
           opacity: .3;
        }
        
        h1 {
           font-size:20px;
           position:relative;
           Bottom:50px;
           left:40px; 
           margin:0px;
        }
        #customer-box{
            height:500px;
            width:100%;
            background:white;
            position:relative;
            bottom:50px;
            
        }
        
        .individual-customer-box{
            height:200px;
            width: 200px;
            border: 2px solid #EEEDEB;
            background:white;
            float:left;
            margin:54px;
            border-radius: 25px;
            transition: all .25s ease-in-out;
            
        }
        .individual-customer-box:hover{
            height:208px;
            width: 208px;
            background:white;
            box-shadow: 5px 5px #EEEDEB;
            transform:scale(1.05);
           
        }
       
        #customer-ee{
            margin:30px 0px 0px 30px;
        }
        
         #customer-asda{
            margin:40px 0px 0px 35px;
            
        }
         #customer-Bijenkorf{
            margin:40px 0px 0px 10px;
            
        }
         #customer-blokker{
          position: relative;
          top:40px;
          right:0px;
          max-height: 50%;
        }
        
        #hrbreak{
        position:relative;
        bottom:200px;
        }
        
        #bottom-text{
        height:100px;
        width:700px;
        
        font-size:18px;   
       
        }
        h2 {
        margin:0px; 
        }
        
        .text-position-bottom{
        position:relative;
        bottom:180px;
        left: 40px;
        }
        
        #button{
            height:100px;
            width: 300px;
            border-radius: 10px;
            background: #019EE0;
            background: linear-gradient(lightblue, #019EE0, lightblue)
        }
        
        #button a{
           color:white;
           font-size: 30px;
           text-decoration: none;
           text-align: center;
           line-height: 100px;
        }
        
        
    </style>
    </head>
        <body>
            <div id='topbar'>
                <div id='bar'>
                    <img id='logo' src='images/logo.png'>
                    <ul>
                        <li><a>Solutions</a>
                            <ul>
                                <li><a>Guest Access</a></li>
                                <li><a>Analytics</a></li>
                                <li><a>Interaction</a></li>  
                            </ul>
                        </li>
                        <li><a>Industries</a>
                            <ul>
                                <li><a>retail</a></li>
                                <li><a>Events</a></li>
                                <li><a>Public Transport</a></li> 
                                <li><a>Hospitality</a></li>
                                <li><a>Healthcare</a></li>  
                            </ul>
                        </li>
                        <li><a>Partners</a></li>
                        <li><a>About</a>
                            <ul>
                               <li><a>Career</a></li>
                               <li><a>News</a></li>
                               <li><a>Downloads</a></li> 
                            </ul>
                        </li>
                        <li><a href='#'>Contact</a></li>
                     </ul>
                </div>  
            </div>
           
            <div id='middleimage'>
                <div id='textpicture-box'>
                     <p id='textpicture'>
                        Picopoint Solutions delivers location based marketing services  
                        over a wireless connection to the consumer’s smartphone. This 
                        ranges from guest access to data analytics and from custom 
                        campaigns to two-way communication with shoppers.
                    </p>
                </div> 
                  <img  src='images/droplet.png'>
                </div>
                <div class='clear'></div>
                <div id="middle-section-box">
                    <div Class='middle-section'> 
                        <img id="middle-section-image1" src='images/wifi.png'>
                        <p class="middle-section-box-text">
                        State-of-the-art wireless guest access<br>
                        matching your company's brand.
                        </p>
                        <p><a href='#'><b>Learn more</b></a></p> 
                    </div>
                    <div class='middle-section'>    
                        <img id="middle-section-image2" src='images/analytics.png'>
                        <p class="middle-section-box-text">
                        Reliable data-analysis and reporting<br>
                        on any level of detail.
                        </p>
                        <p><a href='#'><b>Learn more</b></a></p>
                    </div>
                    <div class='middle-section'>
                        <img id="middle-section-image3" src='images/interaction.png'>
                        <p class="middle-section-box-text" id='middle-section-box-text3'>
                        Open up new channels to<br> 
                        communicate with your customers.
                        </p>
                        <p><a id='middle-section-box-text3-learn' href='#'>
                         <b>Learn more</b></a>
                        </p>
                    </div>
                </div>
            <hr />
        <div class='clear'></div>
        <div>
            <h1>Our customers</h1>
        </div>    
        <div id='customer-box'>
            <div class='individual-customer-box'>
                <a href='#'>
                <img id='customer-ee' src='images/ee.png'>
                </a>
            </div>
            <div class='individual-customer-box'>
                <a href='#' '>
                <img id='customer-asda' src='images/asda.png'>
                </a>
            </div>
            <div class='individual-customer-box'>
                <a href='#'>
                    <img id='customer-Bijenkorf' src='images/bijenkorf.png'>
                </a>
                
            </div>
            <div class='individual-customer-box'>
                <a href='#'>
                <img id='customer-blokker' src='images/blokker.png'>
                </a>
            </div>
        </div>
      <hr id='hrbreak'/>  
      <div>
      <h2 class='text-position-bottom'>Get in Touch</h2>
        <div id='bottom-text' Class='text-position-bottom'>
            <p>Do you want to offer your customers easy and secure and branded access
               at all your locations, further enhancing the customer experience? Please
               don’t hesitate to contact us. We would be happy to answer any of your 
               questions and help you to improve on-site communication with your customers.
            </div>
            <div id='button'>
                 <a href='#'><img src='images/mail-logo.png'> Get in touch</a>
            </div>
        </div>
      </body>
 </html>     
