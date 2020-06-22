<!DOCTYPE html>

<html class="no-js" lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive YouTube Player with Scrolling Thumbnail Playlist</title>
    <style type="text/css">
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: rgb(33,49,67);
            color: #333;
        }
        h1 {
            font-size: 2.5em;
            color: #213143;
        }
        h3 {
            font-size: 1.5em;
            color: #213143;
            margin-bottom: 4px;
            margin-left: 40px;
        }
        .spacer {
            height: 50px;
        }
        .wrapper {
            -webkit-box-sizing: border-box; /* Safari/Chrome, other WebKit */
            -moz-box-sizing: border-box;    /* Firefox, other Gecko */
            box-sizing: border-box;         /* Opera/IE 8+ */
            width: 100%;
            max-width: 1080px;
            margin: 0 auto;
            padding: 15px;
        }
        
        .hdr {
            position: relative;
            min-height: 560px;
            /*background-image: url('http://i3.ytimg.com/vi/779OQH4R8Bk/maxresdefault.jpg');*/
            /*background-image: url('http://img.youtube.com/vi/sxymSXYEnnw/maxresdefault.jpg');*/
            /*background-position: top, center;*/
            background-repeat: no-repeat;
            background-size: cover;
        }
        .main {
            background-color: rgb(33,49,67);
            position: relative;
            z-index: 1;
        }
        .logo {
            position: relative;
            margin-top: 42px;
            margin-left: 48px;
            z-index: 1;
        }
        .logo img {
            width: 440px;
        }
        .bar {
            width: 100%;
            background-color: rgba(33,49,67,.8);
            color: #fff;
            position: absolute;
            bottom: 0;
        }
        .tag {
            font-size: 18px;
            line-height: 30px;
            padding-left: 40px;
        }
        ul.cb-slideshow {
            list-style-type: none;
            list-style: none;
            margin:0;
            padding: 0;
        }

        .cb-slideshow,
        .cb-slideshow:after { 
            /*position: fixed;*/
            width: 100%;
            height: 100%;
            top: 0px;
            left: 0px;
            z-index: 0; 
        }

        .cb-slideshow li span { 
            width: 100%;
            height: 100%;
            position: absolute;
            top: 0px;
            left: 0px;
            color: transparent;
            background-size: cover;
            /*background-position: center top; */
            background-repeat: no-repeat;
            z-index: 0;
        }
        @media (max-width: 900px) {
            .hdr {
                min-height: 460px;
            }
            .logo {
                margin-top: 36px;
            }
            .logo img {
                width: 384px;
            }
        }
        @media (max-width: 480px) {
            .hdr {
                min-height: 340px;
            }
            .logo {
                margin-top: 12px;
                margin-left: 16px;
            }
            .logo img {
                width: 280px;
            }
            .tag {
                padding-left: 10px;
            }
        }
    </style>

    <!-- MyList Styles -->
    <link href="mylist-gallery/css/mylist-player.css" rel="stylesheet">

    <!-- MyList Custom Styles -->
    <style type="text/css">
        .player-container h3 {
            color: #fff;  /* <-- color of playlist titles */
        }
        .vid-item .desc {
            color: #9ca0a4;  /* <-- color of video titles in playlist */
        }
        .vid-item:hover .desc {
            color: #439DDE;  /* <-- hover state color of video titles */
        }
        .mlvp-arrow-left, .mlvp-arrow-right {
            color: #9ca0a4;  /* <-- color of playlist arrows */
        }
        .mlvp-arrow-left:hover, .mlvp-arrow-right:hover {
            color: #439DDE;  /* <-- hover color of playlist arrows */
        }
    </style>

    <!-- MyList Gallery SETTINGS -->
    <script type="text/javascript">
        // include a youtube playlist id for each playlist
        // place quotation marks around each and seperate by commas
        var playListID = [
            "PLSSPBo7OVSZsthvEQhtu2sZ1G9GUAnnZ7", 
            "PLSSPBo7OVSZu820GHiO3qjYRT2oL2V9wM", 
            "PLSSPBo7OVSZszs6coWD3nnAhJyVe_2drG"
        ]; 
        var apiKey = "AIzaSyAn7fiusMZf59A1tfIS1Tip3fs3Vg6jiUc"; // this default YouTube API key will work but you should change it to your own
        var autoPlayNext = 1; // auto play next video in list when current ends? 0 for no. 1 for yes.
        var showPlayerControls = 1; // display YouTube video player controls? 0 for no. 1 for yes.
        var showTitlesInList = 1; // display video titles under each thumbnail in playlist? 0 for no. 1 for yes.
    </script>

    <!-- jQuery -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>

    <!-- MyList Javascript -->
    <script src="mylist-gallery/js/mylist-player.js" defer></script>

</head>

<body>

    <div class="hdr">
        <ul class="cb-slideshow">
            <li><span style="background-image: url('http://img.youtube.com/vi/tQwXd5JtjmA/maxresdefault.jpg')" data-stellar-background-ratio="0.4">Image 01</span></li>
            <li><span style="background-image: url('assets/bike.jpg');" data-stellar-background-ratio="0.4">Image 02</span></li>
            <li><span style="background-image: url('http://i3.ytimg.com/vi/779OQH4R8Bk/maxresdefault.jpg')" data-stellar-background-ratio="0.4">Image 03</span></li>
        </ul>
        <div class="wrapper">
            <div class="logo"><img src="assets/mlvg-logo.png" alt="MyList Video Gallery"></div>
        </div>
        <div class="bar">
            <div class="wrapper">
                <p class="tag">Demo: Three Playlists on Dark Background</p>
            </div>
        </div>
    </div>

    <div class="main">
        <div class="wrapper">

            <div class="spacer"></div>

            <!-- MYLIST PLAYER HTML START -->
            <div id="player-container1" class="player-container">
                <h3>GoPro: Hello Winter!</h3>

                <!-- LEFT AND RIGHT ARROWS -->
                <div class="mlvp-arrows">
                    <div class="mlvp-arrow-left"><i class="demo-icon icon-left-open">&#xe800;</i></div>
                    <div class="mlvp-arrow-right"><i class="demo-icon icon-right-open">&#xe801;</i></div>
                </div>
                <!-- THE PLAYLIST -->
                <div class="mlvp-list-container">
                    <div class="mlvp-list noselect" ></div>
                </div>
            </div>

            <!-- MYLIST PLAYER HTML START -->
            <div id="player-container2" class="player-container">
                <h3>GoPro: Animals</h3>

                <!-- LEFT AND RIGHT ARROWS -->
                <div class="mlvp-arrows">
                    <div class="mlvp-arrow-left"><i class="demo-icon icon-left-open">&#xe800;</i></div>
                    <div class="mlvp-arrow-right"><i class="demo-icon icon-right-open">&#xe801;</i></div>
                </div>
                <!-- THE PLAYLIST -->
                <div class="mlvp-list-container">
                    <div class="mlvp-list noselect" ></div>
                </div>
            </div>

            <!-- MYLIST PLAYER HTML START -->
            <div id="player-container3" class="player-container">
                <h3>GoPro: Music</h3>

                <!-- LEFT AND RIGHT ARROWS -->
                <div class="mlvp-arrows">
                    <div class="mlvp-arrow-left"><i class="demo-icon icon-left-open">&#xe800;</i></div>
                    <div class="mlvp-arrow-right"><i class="demo-icon icon-right-open">&#xe801;</i></div>
                </div>
                <!-- THE PLAYLIST -->
                <div class="mlvp-list-container">
                    <div class="mlvp-list noselect" ></div>
                </div>
            </div>


            <!-- THE YOUTUBE PLAYER -->
            <div class="mlvp-container">
                <div class="mlvp-close"><img src="mylist-gallery/fonts/mlvp-close.svg" onClick="hide_mlvp();"></div>
                <div id="vid_frame"></div>
            </div>


            <!-- MYLIST LIST PLAYER HTML END --> 

            <br>&nbsp;

        </div>
    </div>

    

    <!-- Banner Slideshow -->
    <script type="text/javascript">
      $(document).ready(function() {

            function fadeInOut () {
                $('.cb-slideshow li:nth-child(3) span').delay(6000).fadeOut(1000, function () {
                    $('.cb-slideshow li:nth-child(2) span').delay(6000).fadeOut(1000, function () {
                        $('.cb-slideshow li:nth-child(3) span').delay(6000).fadeIn(1000, function () {
                            $('.cb-slideshow li:nth-child(2) span').fadeIn(10);
                            setTimeout(fadeInOut, 500);
                        });
                    });
                });
            }

            fadeInOut();

      });
    </script>

    <!-- parallax -->
    <script src="http://www.woosterwebdesign.com/lhmarchitects/theme/Wooster/js/jquery.stellar.min.js"></script>
    <script>
        // $(function(){
        //   $.stellar({
        //     horizontalScrolling: false,
        //     verticalOffset: 0
        //   });
        // });

        var isMobile = {
            Android: function() {
                return navigator.userAgent.match(/Android/i);
            },
            BlackBerry: function() {
                return navigator.userAgent.match(/BlackBerry/i);
            },
            iOS: function() {
                return navigator.userAgent.match(/iPhone|iPad|iPod/i);
            },
            Opera: function() {
                return navigator.userAgent.match(/Opera Mini/i);
            },
            Windows: function() {
                return navigator.userAgent.match(/IEMobile/i);
            },
            any: function() {
                return (isMobile.Android() || isMobile.BlackBerry() || isMobile.iOS() || isMobile.Opera() || isMobile.Windows());
            }
        };

        if( !isMobile.any() ) {
          console.log("not mobile");
              $(function(){
                $.stellar({
                  horizontalScrolling: false,
                  verticalOffset: 0
                });
              });
            }
        else {
          console.log("mobile");
          // $(".hdr").addClass("fixed");
        }
        
    </script>

</body>
</html>
