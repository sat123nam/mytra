# mytra
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;

        }
        header{
            
        
            margin-top: 10px;
        }
        .optine{
            display: flex;
            position: relative;
            left: 130px;
            bottom: 40px;
        }
        .optine a{
            margin: 14px;
            text-decoration: none;
            color: black;
        }
        .search{
            display: flex;
            justify-content: flex-start;
            align-items: center;
            padding: 10px;
          }
        .searcher input{
            width: 400px;
            height: 50px;
            position:relative;
            left: 550px;
            bottom: 105px;
            border-radius: 20px;
        }
.button{
            display: flex;
            justify-content: flex-start;
            align-items: center;
            }
            .buton a{
                float: left;
                margin: 11px;
                position: relative;
                left: 640%;
                bottom: 170px;
                text-decoration: none;
                color: black;

            }
           
     .photo{
        display: flex;
     }
     .images img{
           position: relative;
           bottom: 130px;
     }

    </style>
</head>
<body>
    <header>
        <nav class="navbaar">
            <div class="logo">
                <a href="#"><img width="70px" src="./myntra-1200x900.webp" alt=""></a>
            </div>
            <div class="optine">
                <a href="#">Men</a>
                <a href="#">Women</a>
                <a href="#">Kids</a>
                <a href="#">Home</a>
                <a href="#">Beauty</a>
                <a href="#">Studio</a>
            </div>
            <section class="search">
                <div class="searcher">
                    <i class="fa-solid fa-magnifying-glass"></i>
                    <input type="text"  placeholder="Search for Products, Brands and More ">
                </div>

            </section>
            <section class="button">
                <div class="buton">
                    <a href="#"><img width="30px" src="././profime logo.jpg" alt=""><h6>Profile</h6></a>
                    <a href="#"><img width="30px" src="./heart.webp" alt=""><h6>Wishlist</h6></a>
                <a href="#"><img width="30px" src="./bage.jpg" alt=""><h6>Bag</h6></a>
                </div>
            </section>
             
        </nav>
    </header>
    <section class="photo">
        <div class="images"><img width="100%" src="./offer.webp" alt=""></div>
    </section>
</body>
</html>
