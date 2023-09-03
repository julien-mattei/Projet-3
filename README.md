<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ohmyfood</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Raleway&family=Roboto:wght@100&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Raleway&family=Roboto:wght@100;300;400;500;700;900&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/9988122eb3.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="Assets/CSS/style-index.css">
</head>

<body>
    <div class="main-container">
        <header class="header">
            <div class="header__logo">
                <img src="Assets/images/logo/ohmyfood.png" class="header__image" alt="">
            </div>
            <div class="header__location">
                <i class="fa-solid fa-location-dot header__icon-loc"></i>
                <p>Paris, Belleville</p>
            </div>
        </header>
        <div class="informations">
            <h2 class="informations__title">Réservez le menu qui vous convient</h2>
            <p class="informations__txt">Découvrez des restaurants d'exceptions, sélectionnées par nos soins.</p>
            <button class="informations__button">Explorer nos restaurants</button>
        </div>
        <div class="fonctionnement">
            <h2 class="fonctionnement__title">Fonctionnement</h2>
            <div class="fonctionnement__pannels">
                <div class="fonctionnement__pannel">
                    <div class="circle">1</div>
                    <i class="fa-solid fa-mobile-screen-button fa-lg fonctionnement__icon"></i>
                    <p>Choisissez un restaurant</p>
                </div>
                <div class="fonctionnement__pannel">
                    <div class="circle">2</div>
                    <i class="fa-solid fa-list-ul fa-lg fonctionnement__icon"></i>
                    <p>Composez votre menu</p>
                </div>
                <div class="fonctionnement__pannel">
                    <div class="circle">3</div>
                    <i class="fa-solid fa-store fa-lg fonctionnement__icon fonctionnement__icon--purple"></i>
                    <p>Dégustez au restaurant</p>
                </div>
            </div>
        </div>
        <div class="restaurants">
            <h2>Restaurants</h2>
            <div class="restaurants__cards">
                <div class="restaurants__card">
                    <img src="Assets/images/restaurants/jay-wennington-N_Y88TWmGwA-unsplash.jpg" class="restaurants__image" alt="">
                    <div class="restaurants__card-new">Nouveau</div>
                    <div class="restaurants__card-content">
                        <div class="restaurants__card-content-txt">
                            <h3 class="restaurants__card-content-txt-title">La palette du goût</h3>
                            <p class="restarants__card-content-txt-loc">Ménilmontant</p>
                        </div>
                        <div class="restaurants__card-content-icon">
                            <i class="fa-regular fa-heart fa-2xl"></i>
                        </div>
                    </div>
                </div>
                <div class="restaurants__card">
                    <img src="Assets/images/restaurants/stil-u2Lp8tXIcjw-unsplash.jpg" class="restaurants__image" alt="">
                    <div class="restaurants__card-new">Nouveau</div>
                    <div class="restaurants__card-content">
                        <div class="restaurants__card-content-txt">
                            <h3 class="restaurants__card-content-txt-title">La note enchantée</h3>
                            <p class="restarants__card-content-txt-loc">Charonne</p>
                        </div>
                        <div class="restaurants__card-content-icon">
                            <i class="fa-regular fa-heart fa-2xl"></i>
                        </div>
                    </div>
                </div>
                <div class="restaurants__card">
                    <img src="Assets/images/restaurants/toa-heftiba-DQKerTsQwi0-unsplash.jpg" class="restaurants__image" alt="">
                    <div class="restaurants__card-content">
                        <div class="restaurants__card-content-txt">
                            <h3 class="restaurants__card-content-txt-title">A la française</h3>
                            <p class="restarants__card-content-txt-loc">Cité Rouge</p>
                        </div>
                        <div class="restaurants__card-content-icon">
                            <i class="fa-regular fa-heart fa-2xl"></i>
                        </div>
                    </div>
                </div>
                <div class="restaurants__card">
                    <img src="Assets/images/restaurants/louis-hansel-shotsoflouis-qNBGVyOCY8Q-unsplash.jpg" class="restaurants__image" alt="">
                    <div class="restaurants__card-content">
                        <div class="restaurants__card-content-txt">
                            <h3 class="restaurants__card-content-txt-title">Le délice des sens</h3>
                            <p class="restarants__card-content-txt-loc">Folie-Méricourt</p>
                        </div>
                        <div class="restaurants__card-content-icon">
                            <i class="fa-regular fa-heart fa-2xl"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <footer class="footer">
            <img src="Assets/images/logo/ohmyfood.png" class="footer__image" alt="">
            <div class="footer__links">
                <div class="footer__links-iconed">
                    <i class="fa-solid fa-utensils footer__icon"></i>
                    <a href="" class="footer__link">Proposer un restaurant</a>
                </div>
                <div class="footer__links-iconed">
                    <i class="fa-solid fa-handshake-angle fa-xs footer__icon"></i>
                    <a href="" class="footer__link">Devenir partenaire</a>
                </div>
                <a href="" class="footer__link">Mentions légales</a>
                <a href="" class="footer__link">Contact</a>
            </div>
        </footer>
    </div>
</body>
