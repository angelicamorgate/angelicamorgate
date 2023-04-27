<!DOCTYPE html>
<html>
    <head>
        <title>Final_Project_Morgate</title>
        <meta name="author" content="AMM">
        <meta name="keywords" content="html, css, finals">
        <link rel="stylesheet" type="text/css" href="../styles/Final_Project_Mogate.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <body>
        
        <header>
        <div class="logo">
            <a href="#">ESCAFÉ <span> coffee shop </span></a>
            </div>

            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#menu">Menu</a></li> 
                    <li><a href="#shop">Shop</a></li>
                    <li><a href="#contact">Contacts</a></li>  
                </ul> 
            </nav>
        </header>

        <div class="content">
            <h1> Welcome to ESCAFÉ coffee shop!</h1>
            <p>escape through coffee</p>
        </div>
              
        <div class="menu" id="menu">
            <div class="menu-header">
                <h2>Menu</h2>
                <h3>ESCAFÉ Menu</h3>
            </div>
            <div class="menu-content">
                     <div class="hot-coffees">
                        <div class="hot-coffees-image">
                            <img src="../src/hot-coffees.jpg" alt="">
                        </div>
                        <div class="hot-coffes-body">    
                        <h4>Hot Coffees</h4>
                        <label>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</label>
                    </div>
                </div>
                <div class="cold Coffee">
                    <div class="cold-coffes-image">
                        <img src="../src/cold-coffees.jpg" alt="">
                    </div>
                    <div class="cold-coffees-body">
                    <h4>Cold Coffes</h4>
                    <label>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</label>
                     </div>
                </div>
                <div class="frappucino-coffees">
                    <div class="Frappucino-coffee-image">
                        <img src="../src/frappuccino.jpg" alt="">
                    </div>
                    <div class="Frappucino-coffee-body">
                    <h4>Frappucino Coffees</h4>
                    <label>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</label>
                    </div>
                </div>
            </div>
        </div>
    
    
        <div class="shop" id="shop">
            <div class="shop-header">
                <h3>Shop</h3>
                <h4>ESCAFÉ Coffee Drinks</h4>
            </div>
            <div class="shop-box">
                <div class="item-1">
                    <div class="card">
                        <div class="card-image">
                            <img src="../src/cappuccino.jpg">
                        </div>
                        <div class="card-body">
                            <label class="cash">2.45$</label>
                            <h3>cappuccino</h3>
                            <label>Lorem ipsum dolor sit amet.</label>
                        </div>
                    </div>
                </div>
                <div class="item-2">
                    <div class="card">
                        <div class="card-image">
                            <img src="../src/espresso.jpg">
                        </div>
                        <div class="card-body">                          
                            <label class="cash">3.55$</label>
                            <h3>Espresso</h3>
                            <label>Lorem ipsum dolor sit amet.</label>
                        </div>
                    </div>
                </div>
                <div class="item-3">
                    <div class="card">
                        <div class="card-image">
                            <img src="../src/ice-latte.jpg">
                        </div>
                        <div class="card-body">                          
                            <label class="cash">3.45$</label>
                            <h3>Ice latte</h3>
                            <label>Lorem ipsum dolor sit amet.</label>
                        </div>
                    </div>
                </div>
                <div class="item-4">
                    <div class="card">
                        <div class="card-image">
                            <img src="../src/latte macchiato.jpeg">
                        </div>
                        <div class="card-body">                          
                            <label class="cash">2.79$</label>
                            <h3>Latte Macchiato</h3>
                            <label>Lorem ipsum dolor sit amet.</label>
                        </div>
                    </div>
                </div>
                <div class="item-5">
                    <div class="card">
                        <div class="card-image">
                            <img src="../src/Doubleshot-Iced-Coffee.jpeg">
                        </div>
                        <div class="card-body">
                            <label class="cash">3.75$</label>
                            <h3>Doubleshot Cold Coffee</h3>
                            <label>Lorem ipsum dolor sit amet.</label>
                        </div>
                    </div>
                </div>
                <div class="item-6">
                    <div class="card">
                        <div class="card-image">
                            <img src="../src/double chocolate chip.jpg">
                        </div>
                        <div class="card-body">
                            <label class="cash">3.25$</label>
                            <h3>Double Chco-chip frappuccino</h3>
                            <label>Lorem ipsum dolor sit amet.</label>
                        </div>
                    </div>
                </div>
                <div class="item-7">
                    <div class="card">
                        <div class="card-image">
                            <img src="../src/white-chocolate-mocha.jpg">
                        </div>
                        <div class="card-body">
                            <label class="cash">5.40$</label>
                            <h3>white-chocolate-mocha</h3>
                            <label>Lorem ipsum dolor sit amet.</label>
                        </div>
                    </div>
                </div>
                <div class="item-8">
                    <div class="card">
                        <div class="card-image">
                            <img src="../src/Matcha-Cream-Frappuccino.jpeg">
                        </div>
                        <div class="card-body">
                            <label class="cash">5.65$</label>
                            <h3>Matcha green tea frappuccino</h3>
                            <label>Lorem ipsum dolor sit amet.</label>
                        </div>
                    </div>                           
                </div>
            </div>
        </div>
    
        <div class="contact" id="contact">
            <div class="contact-box">
                <div class="contact-image">
                    <img src="../src/bgcoffee.jpg">
                </div>
            </div>
            <div class="contact-box">
                <div class="contact-body">
                    <form>
                        <h2>Contact Us</h2>
                        <div class="form-content">
                            <input type="text" required>
                            <span></span>
                            <label>Username</label>
                        </div>
                        <div class="form-content">
                            <input type="email" required>
                            <span></span>
                            <label>Email</label>
                        </div>
                        <button type="submit">Send</button>
                    </form>
                </div>
            </div>
        </div>
    
    
        <div class="footer">
            <div class="footer-box">
                <div class="social-media">
                    <a href="#"><i class="fa-brands fa-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-youtube"></i></a>
                    <a href="#"><i class="fa-brands fa-tiktok"></i></a>
                </div>
                <div class="copyright">
                    <footer>
                        <p>Developed by: AMM</p>
                </footer>
                    <label>Copyright &copy; 2023</label>
                </div>
                <div class="brand">
                    <label> ESCAFÉ </em><span>Coffee Shop</span></label>
                </div>
            </div>
        </div>
    
    </body>
</html>

        

