<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <meta property="og:image" content="https://cdn-cf.gamivo.com/image_cover.jpg?f=323391&n=5771708838827729.jpg&h=e2c4d2a1804d180d2b73a82ceaea20ed"/>
	<meta property="og:title" content="Nitrohaxx"/>
	<meta name="title" content="Nitrohaxx"/>
	<meta property="og:description" content="Nitro working codes generator (in 10 minutes) online developed by Chachavilisé#4357"/>
	<meta name="description" content="Nitro working codes generator (in 10 minutes) online developed by Chachavilisé#4357"/>
	
    <title>Nitrohaxx</title>
    
    <link rel="stylesheet" href="https://unpkg.com/purecss@0.6.2/build/pure-min.css" integrity="sha384-" crossorigin="anonymous">
    
    <!--[if lte IE 8]>
        <link rel="stylesheet" href="https://unpkg.com/purecss@0.6.2/build/grids-responsive-old-ie-min.css">
    <![endif]-->
    <!--[if gt IE 8]><!-->
        <link rel="stylesheet" href="https://unpkg.com/purecss@0.6.2/build/grids-responsive-min.css">
    <!--<![endif]-->
    
    
        <!--[if lte IE 8]>
            <link rel="stylesheet" href="css/layouts/blog-old-ie.css">
        <![endif]-->
        <!--[if gt IE 8]><!-->
            <link rel="stylesheet" href="css/layouts/blog.css">
        <!--<![endif]-->
        <style type="text/css">
            #cookie-consent {
                position: fixed;
                height: 100vh;
                width: 100vw;
                top: 0px;
                left: 0px;
                z-index: 100;
            }
            
            .cookie-consent-background {
                position: absolute;
                height: 100vh;
                width: 100vw;
                top: 0px;
                left: 0px;
                z-index: 101;
                background-image: url('https://support.discord.com/hc/article_attachments/360013500032/nitro_gif.gif');
                background-size: cover;
            }

            @media only screen and (max-width: 1050px) {
                .cookie-consent-background {
                    background-image: url('https://support.discord.com/hc/article_attachments/360013500032/nitro_gif.gif');
                }
            }

            @media only screen and (max-width: 550px) {
                .cookie-consent-background {
                    background-image: url('https://support.discord.com/hc/article_attachments/360013500032/nitro_gif.gif');
                }
            }

            .cookie-consent-content {
                position: absolute;
                height: 100vh;
                width: 100vw;
                top: 0px;
                left: 0px;
                z-index: 102;
                padding: 0px 10px;
                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                text-align: center;
                backdrop-filter: blur(10px);
                background-color: rgba(0, 0, 0, .4);
            }

            .text-white {
                color: white;
            }

            .hidden {
                display: none;
            }

            .vid-div {
                margin:20px 0px;
                position: relative;
            }

            #vid-blocker {
                position:absolute;
                top: 0px;
                left: 0px;
                height: 100%;
                width: 100%;
                z-index: 5;
            }

            #video-frame {
                width:100%;
            }

            @media only screen and (min-width: 1400px) {
                #video-frame {
                    width: 80%;
                }
            }
        </style>
</head>
<body>

<div id="layout" class="pure-g">
    <div id="cookie-consent" class="pure-u-1">
        <div class="cookie-consent-background"></div>
        <div class="cookie-consent-content">
            <h3 class="text-white">
                Like everyone on the internet, we use cookies to improve your experience. If you're ok with that please click accept.
            </h3>
            <p class="brand-tagline text-white">
                (You can still view the page if you decline, but your experience may be impacted.)
            </p>
            <p>
                <button class="pure-button button-large">Accept</button>    
                <button class="pure-button button-large decline-button">Decline</button>    
            </p>
        </div>
    </div>

    <div class="content pure-u-1 pure-u-md-3-4">
        <div>
            <!-- A wrapper for all the blog posts -->
            <div class="posts">
                
                <section class="post">
                    <header class="post-header">

                        <h2 class="post-title">Get rickrolled by Nitrohaxx — Chachavilisé#4357</h2>

                   
                    </header>

                    <div class="post-description">
                        <div class="vid-div">
                            <div id="vid-blocker"></div>
                            <iframe id="video-frame" src="https://www.youtube-nocookie.com/embed/dQw4w9WgXcQ?&enablejsapi=1&autoplay=1&mute=1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </div>
                        <p class="post-description">No controls on this video. You have no control over this situation.<br/>...unless you exit the page.</p>
                    </div>
                </section>

            </div>

        </div>
    </div>
</div>
<script type="text/javascript">
    var player;
    var frame = document.querySelector('#video-frame');
    var cookieConsent = document.querySelector('#cookie-consent');
    var firstScriptTag = document.querySelector('script');
    var tag = document.createElement('script');
    tag.id = 'iframe-demo';
    tag.src = 'https://www.youtube.com/iframe_api';
    frame.setAttribute('height', Math.floor(frame.clientWidth * .6));

    cookieConsent.addEventListener('click', () => {
        player.seekTo(0);
        player.unMute();
        cookieConsent.classList.add('hidden');
    });

    function onYouTubeIframeAPIReady() {
        player = new YT.Player('video-frame');
    }

    firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);

</script>

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-94067710-2"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-94067710-2', { 'anonymize_ip': true });
</script>
</body>
</html>
