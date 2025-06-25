<!DOCTYPE html>  
<html>
<head>
<title>Dungeon Quest</title>
<style>
body {                                    
  background-image: url('wallpaper.png'); 
  background-size: cover;                 
  background-repeat: no-repeat;           
  font-family: sans-serif;                       
  margin: 0;                              
  color: white;                           
}

header {                                  
  background-color: #333;                 
  color: white;                           
  padding: 10px 0;                        
}

nav ul {                                  
  list-style: none;                       
  margin: 0;                              
  padding: 10;                           
  text-align: center;                     
}
.sub-nav ul {                             
  display: flex;                          
  justify-content: space-around;          
  align-items: center;                    
  list-style: none;                        
  margin: 0;                              
  padding: 0;                             
}
nav li {                                  
  display: inline;                        
  margin: 0 10px;                         
}

nav a {                                   
  color: white;                           
  }
 
 .container {                             
  display: flex;                          
  justify-content: space-between;10        
  align-items: center;                    
  flex-wrap: wrap;                        
  max-width: 960px;                        
  margin: 0 auto;                         
  padding: 10px 20px;                     .
}

}

.logo img {
  float: left;                           
  margin-right: 100px;                    
  max-height: 80px;                       
  max-width: 200px;                      
}

.search {                                
  float: right;                          
}

.search input[type="text"] {            
  padding: 5px;                          
  border: 1px solid #ccc;               
  border-radius: 5px;                   
}

.search button {
  padding: 5px 10px;
  background-color: #4CAF50;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

main {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: calc(100vh - 100px);
  padding: 20px;
}

.main-content {
  text-align: center;
  max-width: 800px;
  background-color: rgba(255, 255, 255, 0.1); 
  padding: 20px;
  border-radius: 10px;
}
</style>
</head>
<body>
<header>
  <div class="container">
    <div class="logo">
      <img src="logo.png" alt="Logo">
    </div>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    <div class="search">
      <input type="text" placeholder="Search...">
      <button type="submit">Search</button>
    </div>
  </div>
   <nav class="sub-nav">
    <ul>
      <li><a href="sword.html">Sword</a></li>
      <li><a href="Armour.html">Armours</a></li>
      <li><a href="hok.html">Skills</a></li>
    </ul>
  </nav>
</header>

<main>
  <div class="main-content">
    <h2>Welcome to Dungeon Quest!</h2>
    <p>Its a rpg game that utilizes all kinds of weaponary to vanish your foe, ultimstely delcaring yoirself as the king of dungeon.</p>
    
  </div>
</main>

</body>
</html>
