---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: 
layout: home
---
<style>
    .caption {
        margin: 50px 100px;
        color: #4880F0;
        text-align: center;
        font-family: 'Helvetica', -apple-system, BlinkMacSystemFont, sans-serif;
        font-size: 30px;
    }

    .main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: calc(100vh - 55px);
        min-height: calc(100vh - 55px);
        margin-top: -30px;
        margin-bottom: -30px;
        /* there was some weird behavior when trying to make .main take up the entire screen's width */
        /* background: linear-gradient(285deg, rgba(72,128,240,.2) 0%, rgba(88,144,255,0.05) 100%); */
        /* width: 100vw; */
    }

    .logo {
        height: 70px;
        width: auto;
        min-height: 70px;
        margin-top: 40px;
    }

    .news {
        display: none;
    }

    .newsSmall {
        border-radius: 15px;
        object-fit: contain;
        height: 28vh;
    }

    .download {
        display: block;
        width: 120px;
        margin-top: 20px;
    }

    .content {
        width: 300px;
        margin-top: 40px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .leftSide {
        margin-right: 0px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .description {
        font-size: 18px;
        color: #4880F0;
        text-align: center;
    }

    @media (min-width: 768px) {
        .main {
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            height: calc(100vh - 55px);
            min-height: calc(100vh - 55px);
            margin-top: -30px;
            margin-bottom: -30px;
            /* there was some weird behavior when trying to make .main take up the entire screen's width */
            /* background: linear-gradient(285deg, rgba(72,128,240,.2) 0%, rgba(88,144,255,0.05) 100%); */
            /* width: 100vw; */
        }
        
        .newsSmall {
            display: none;
        }

        .news {
            border-radius: 15px;
            object-fit: cover;
            margin-left: 30px;
            height: 50vh;
            display: inline;
        }

        .description {
            padding-left: 50px;
            padding-bottom: 50px;
            text-align: left;
            font-size: 18px;
            color: #4880F0;
        }

        .leftSide {
            margin-right: 30px;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: flex-start;
        }

        .logo {
            height: 100px;
            width: auto;
            min-height: 100px;
        }

        .content {
            width: 350px;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: flex-start;
            margin-top: 20px;
        }

        .download {
            padding-left: 70px;
            margin-top: 0px;
        }
    }

    @media (min-width: 1000px) {
        .news {
            height: 60vh;
        }

         .content {
            width: 500px;
            margin-top: 20px;
        }

        .download {
            display: block;
            width: 160px;
            height: auto;
        }
    }

</style>

<div class="main">
    <img src="/images/index/markus-spiske-2G8mnFvH8xk-unsplash.jpg" class="newsSmall" alt="news">
    <div class="leftSide">
        <link rel="prefetch" href="/images/index/verifai_logo.svg">
        <link rel="prefetch" href="/images/index/markus-spiske-2G8mnFvH8xk-unsplash.jpg">
        <img src="/images/index/verifai_logo.svg" class="logo" alt="VerifAI Logo">
        <div class="content">
            <!-- <h1 class="caption">AI-powered Fact Checker</h1> -->
            <p class="description">
                <b>AI-Powered Fact Checker</b>
            </p>
            <a href="https://chromewebstore.google.com/" style="display: inline-block;">
                <img src="/images/index/download_now.svg" class="download" alt="Download Now">
            </a>
        </div>
    </div>
     <img src="/images/index/markus-spiske-2G8mnFvH8xk-unsplash.jpg" class="news" alt="news">
</div>

