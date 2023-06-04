<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Superhero hunter app</title>
    <link rel = "stylesheet" href = "parida.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    
    <div class = "main-wrapper">
        <div class = "app">
            <!-- app header -->
            <div class = "app-header">
                <h2 class = "app-header-title">SuperHero<span>Hunter</span></h2>
                <form class = "app-header-search">
                    <input type = "text" class = "form-control" placeholder="Search your superhero here ..." name = "search">
                    <button type = "submit" class = "search-btn">
                        <i class = "fas fa-search"></i>
                    </button>
                    <div class = "search-list" id = "search-list">
                    </div>
                </form>
            </div>
            <!-- end of app header -->

            <div class = "app-body">
                <div class = "app-body-content">
                    <!-- app body thumbnail -->
                    <div class = "app-body-content-thumbnail">
                        <img src = "./thumbnail-batman.jpg">
                    </div>
                    <!-- end of app body thumbnail -->
                    
                    <div class = "app-body-content-list">
                        <div class = "name">Batman</div>

                        <!-- tabs head -->
                        <div class = "app-body-tabs-head">
                            <button type = "button" class = "tab-head-single" data-id = "1">
                                <span>powerstats</span>
                            </button>
                            <button type = "button" class = "tab-head-single" data-id = "2">
                                <span>biography</span>
                            </button>
                            <button type = "button" class = "tab-head-single" data-id = "3">
                                <span>appearance</span>
                            </button>
                            <button type = "button" class = "tab-head-single" data-id = "4">
                                <span>connections</span>
                            </button>
                        </div>
                        <!-- end of tabs head -->

                        <!-- tabs body -->
                        <div class = "app-body-tabs-body">
                            <!-- powerstats tab -->
                            <ul class = "tab-body-single powerstats">
                                <li>
                                    <div>
                                        <i class = "fa-solid fa-shield-halved"></i>
                                        <span>intelligence</span>
                                    </div>
                                    <span>100</span>
                                </li>
                                <li>
                                    <div>
                                        <i class = "fa-solid fa-shield-halved"></i>
                                        <span>strength</span>
                                    </div>
                                    <span>26</span>
                                </li>
                                <li>
                                    <div>
                                        <i class = "fa-solid fa-shield-halved"></i>
                                        <span>speed</span>
                                    </div>
                                    <span>27</span>
                                </li>
                                <li>
                                    <div>
                                        <i class = "fa-solid fa-shield-halved"></i>
                                        <span>durability</span>
                                    </div>
                                    <span>50</span>
                                </li>
                                <li>
                                    <div>
                                        <i class = "fa-solid fa-shield-halved"></i>
                                        <span>power</span>
                                    </div>
                                    <span>47</span>
                                </li>
                                <li>
                                    <div>
                                        <i class = "fa-solid fa-shield-halved"></i>
                                        <span>combat</span>
                                    </div>
                                    <span>100</span>
                                </li>
                            </ul>
                            <!-- end of powerstats tab -->

                            <!-- biography tab -->
                            <ul class = "tab-body-single biography">
                                <li>
                                    <span>full name</span>
                                    <span>terry mcginnis</span>
                                </li>
                                <li>
                                    <span>alert-egos</span>
                                    <span>no alter egos found.</span>
                                </li>
                                <li>
                                    <span>aliases</span>
                                    <span>Batman II, The Tomorrow Knight, Batman Beyond</span>
                                </li>
                                <li>
                                    <span>place-of-birth</span>
                                    <span>Gothan City, 25th Century</span>
                                </li>
                                <li>
                                    <span>first-apperance</span>
                                    <span>Batman Beyond #1</span>
                                </li>
                                <li>
                                    <span>publisher</span>
                                    <span>DC Comics</span>
                                </li>
                            </ul>
                            <!-- end of biography tab -->

                            <!-- appearance -->
                            <ul class = "tab-body-single appearance">
                                <li>
                                    <span>
                                        <i class = "fas fa-star"></i> gender
                                    </span>
                                    <span>Male</span>
                                </li>
                                <li>
                                    <span>
                                        <i class = "fas fa-star"></i> race
                                    </span>
                                    <span>human</span>
                                </li>
                                <li>
                                    <span>
                                        <i class = "fas fa-star"></i> height
                                    </span>
                                    <span>5' 10''</span>
                                </li>
                                <li>
                                    <span>
                                        <i class = "fas fa-star"></i> weight
                                    </span>
                                    <span>170 lb</span>
                                </li>
                                <li>
                                    <span>
                                        <i class = "fas fa-star"></i> eye-color
                                    </span>
                                    <span>blue</span>
                                </li>
                                <li>
                                    <span>
                                        <i class = "fas fa-star"></i> hair-color
                                    </span>
                                    <span>black</span>
                                </li>
                            </ul>
                            <!-- end of appearance -->

                            <!-- connections -->
                            <ul class = "tab-body-single connections">
                                <li>
                                    <span>group--affiliation</span>
                                    <span>Batman Family, Justice League Unlimited</span>
                                </li>
                                <li>
                                    <span>relatives</span>
                                    <span>Bruce Wayne (biological father), Warren McGinnis (father, deceased), Mary McGinnis (mother), Matt McGinnis (brother)</span>
                                </li>
                            </ul>
                            <!-- end of connections -->
                        </div>
                        <!-- end of tabs body -->
                    </div>
                </div>
            </div>
        </div>
    </div>
    

    <script src = "parida.js"></script>
</body>
</html>
