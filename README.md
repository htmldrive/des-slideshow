desSlideshow - Stylish featured image slideshow jQuery plugin
=======================

[![desSlideshow - Stylish featured image slideshow jQuery plugin](http://www.htmldrive.net/media/2010/8/10/1281449205.jpg "desSlideshow - Stylish featured image slideshow jQuery plugin")](http://www.htmldrive.net/items/demo/324/desSlideshow-Stylish-featured-image-slideshow-jQuery-plugin "desSlideshow - Stylish featured image slideshow jQuery plugin")

[**Demo**](http://www.htmldrive.net/items/demo/324/desSlideshow-Stylish-featured-image-slideshow-jQuery-plugin "desSlideshow - Stylish featured image slideshow jQuery plugin")

##Usage
**Include js and css files.**

    <link href="css/style.css" rel="stylesheet" type="text/css" />
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
    <script src="js/desSlideshow.js"></script>
  
**Add html.**

    <div id="desSlideshow" class="desSlideshow">
        <div class="switchBigPic">
            <div>
                <a title="" href="#"><img class="pic" src="./images/006.jpg" /></a>
                <p><strong>Description Title1</strong><br/>
                    Description Content1
                </p>
            </div>
            <div>
                <a title="" href="#"><img class="pic" src="./images/004.jpg" /></a>
            </div>
            <div>
                <a title="" href="#"><img class="pic" src="./images/001.jpg" /></a>
                <p><strong>Description Title3</strong><br/>
                    Description Content3
                </p>
            </div>
            <div>
            <a title="" href="#"><img class="pic" src="./images/003.jpg" /></a>
                <p><strong>Description Title4</strong><br/>
                    Description Content4
                </p>
            </div>
        </div>
        <ul class="nav">
            <li><a href="#" target="_blank">Slideshow1</a></li>
            <li><a href="#" target="_blank">Slideshow2</a></li>
            <li><a href="#" target="_blank">Slideshow3</a></li>
            <li><a href="#" target="_blank">Slideshow4</a></li>
        </ul>
    </div>

        
**Add startup script.**

    <script language="javascript" type="text/javascript">
        $(function() {
            $("#desSlideshow").desSlideshow({
                autoplay: 'enable',//option:enable,disable
                slideshow_width: '800',//slideshow window width
                slideshow_height: '249',//slideshow window height
                thumbnail_width: '200',//thumbnail width
                time_Interval: '4000',//Milliseconds
                directory: 'images/'// flash-on.gif and flashtext-bg.jpg directory
            });
        });
    </script>