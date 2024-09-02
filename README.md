
body {
    font-family: "Montserrat", sans-serif;
    margin: 0;
    padding: 0;
}


nav {
    background-image: url('https://img.freepik.com/free-vector/data-center-room-tunnel-with-neon-light-glow_107791-30248.jpg?t=st=1725274709~exp=1725278309~hmac=8e06e3aa8389106d6e12c63a7621ddc1753d67bb4d8ea47c45f228640c93d955&w=1380'); 
    background-size: cover; 
    background-position: center;
    background-repeat: no-repeat; 
    height: 50vh; 
    overflow: hidden;
    text-align: center;
    padding: 10px; 
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    position: relative;
    float: none;
    margin: 0;
}

nav ul li a {
    display: block;
    color:#00fe8b;
    text-align: center;
    padding: 14px 20px;
    text-decoration: none;
    font-family: "Roboto", sans-serif;
    font-weight: bold;
}

nav ul li a:hover,
nav ul li a.active {
    color: #55fefd;
    text-decoration-thickness: bold;
    transition: .3s;
}


.dropdown {
    position: relative;
}


.dropdown-content {
    display: none;
    position: absolute;
    background-color: rgba(255, 255, 255, 0.616);
    min-width: 160px;
    border: 1px solid #ddd;
    border-radius: 2vh;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
    padding: 10px;
    max-height: 300px;
    overflow-y: auto;
    white-space: nowrap;
    top: 100%;
    left: 0;
    transition: 0.3s ease, visibility 0.3s ease;
}

.dropdown-content a {
    color: black;
    padding: 8px 12px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.dropdown-content a:hover {
    display: block;
    color:#00366e;
    transition: .3s;
}

.dropdown-content::-webkit-scrollbar {
    display: none;
}


.dropdown:hover .dropdown-content {
    display: block;
}


footer {
    background-color: #f8f9fa;
    padding: 20px;
    border-top: 1px solid #e7e7e7;
}

.footer-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.footer-column {
    flex: 1;
    min-width: 200px;
    margin: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
   
}

.footer-column p, .footer-column address {
    margin: 0 0 10px;
    text-align: center;
}

.footer-column h3 {
    font-size: 1.2em;
    margin-bottom: 10px;
    font-weight: bold;
    text-align: center; 
}

.footer-column ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    text-align: center;
}

.footer-column ul li {
    margin-bottom: 8px;
}

.footer-column ul li a {
    text-decoration: none;
    color: #007bff;
}

.footer-column ul li a:hover {
    text-decoration: underline;
}

.social-icons {
    margin-top: 10px;
    text-align: center; /* Center social icons */
}

.social-icons a {
    margin-right: 10px;
}

.social-icons img {
    width: 24px;
    height: 24px;
}

/* media queires */
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
    }

    .dropdown-content {
        position: static;
        max-height: none;
        overflow: visible;
    }

    .dropdown-content a {
        display: block;
        padding: 10px;
    }
}



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GPU Yard</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Quicksand:wght@300..700&display=swap');</style>
    
<body>
<nav>
        <ul>
            <li><a href="index.php">Home</a></li>
            <li class="dropdown">
                <a href="gpu_servers.php">GPU Servers</a>
                <div class="dropdown-content">
                    <a href="#">All GPU Cards</a>
                    <a href="#">Nvidia GPU</a>
                    <a href="#">GeForce GT</a>
                    <a href="#">Quadro</a>
                    <a href="#">Tesla</a>
                    <a href="#">Nvidia</a>
                </div>
            </li>
            <li class="dropdown">
                <a href="gpu_solutions.php">GPU Solutions</a>
                <div class="dropdown-content">
                    <a href="#">Deep Learning</a>
                    <a href="#">Tensorflow</a>
                    <a href="#">Pytorch</a>
                    <a href="#">Keras</a>
                    <a href="#">XGboost</a>
                    <a href="#">Android Emulator</a>
                    <a href="#">BlueStacks</a>
                    <a href="#">LDPlayer</a>
                    <a href="#">NoxPlayer</a>
                    <a href="#">MEmu</a>
                    <a href="#">GameLoop</a>
                    <a href="#">Live Streaming</a>
                    <a href="#">OBS Studio</a>
                    <a href="#">Octane</a>
                    <a href="#">Rendering</a>
                    <a href="#">Stable Fusion</a>
                    <a href="#">LLaMA 2</a>
                    <a href="#">LLaMA 3.1</a>
                    <a href="#">Ollama</a>
                    <a href="#">AI Image Generator</a>
                    <a href="#">GPU Cluster</a>
                    <a href="#">GPU Farm</a>
                    <a href="#">AI Server</a>
                </div>
            </li>
            <li><a href="about_us.php">About Us</a></li>
        </ul>
    </nav>

    <section class="gpu_servers">

    </section>

    <footer>
        <div class="footer-container">
            
            <div class="footer-column">
                <h3>Home</h3>
                <ul>
                    <li><a href="#">GPU Servers</a></li>
                    <li><a href="#">GPU Solution</a></li>
                </ul>
            </div>

            <div class="footer-column">
                <p>GPU Mart offers professional GPU hosting services that are optimized for high-performance computing projects.
                    We support a wide variety of GPU cards, providing fast processing speeds and reliable uptime for complex applications 
                    such as deep learning algorithms and simulations. Additionally, our expert support team is available 24/7 to assist 
                    with any technical challenges that may arise.</p>
                <address>257 Westwood Dr, League City, TX 77573</address>
                <div class="social-icons">
                    <a href="https://facebook.com" target="_blank" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
                    <a href="https://linkedin.com" target="_blank" aria-label="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
                    <a href="https://youtube.com" target="_blank" aria-label="YouTube"><i class="fab fa-youtube"></i></a>
                </div>
            </div>
            <div class="footer-column">
                <h3>Company</h3>
                <ul>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Data Centers</a></li>
                    <li><a href="#">Affiliate</a></li>
                </ul>
            </div>
            <div class="footer-column">
                <h3>Legal</h3>
                <ul>
                    <li><a href="#">Terms of Service</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Service Level Agreement</a></li>
                </ul>
            </div>
        </div>
    </footer>
</body>
</html>
