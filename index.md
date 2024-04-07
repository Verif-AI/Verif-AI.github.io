---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: 
layout: home
---
<style>
    .caption {
        padding-left: 140px;
        padding-bottom: 50px;
        text-align: left;
        font-size: 18px;
        color: #4880F0;
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
        margin-bottom: 40px;
        margin-left: 90px;
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
            padding-bottom: 50px;
            text-align: justify;
            font-size: 18px;
            color: #5C5C5C;
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
            padding-left: 170px;
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
    <div class="leftSide">
        <link rel="prefetch" href="/images/index/verifai_logo.svg">
        <link rel="prefetch" href="/images/index/markus-spiske-2G8mnFvH8xk-unsplash.jpg">
        <div class="content">
            <img src="/images/index/verifai_logo.svg" class="logo" alt="VerifAI Logo">
            <p class="caption">
                <b>AI-Powered Fact Checker</b>
            </p>
            <!-- <p class="description">
                Have you ever come across news that seemed too good (or bad) to be true? With the rise of fake news and misinformation, it's becoming increasingly difficult to distinguish fact from fiction. That's where Verif.AI comes in - our cutting-edge solution leverages an ensemble of fine-tuned Large Language Models (LLMs) augmented with RAG technology to combat misinformation in real-time. By using our browser extension, you can easily verify the accuracy of claims with unparalleled speed and reliability at scale. Our platform provides users with instant insights into the truthfulness of information, enabling informed decision-making and fostering a more resilient society. Join us in the fight against fake news and misinformation with Verif.AI - where truth is just a click away.
            </p> -->
            <p class="description">
                Have you ever come across news that seemed too good (or bad) to be true? That's where Verif.AI comes in - our cutting-edge solution stands as a powerful shield against the rampant spread of misinformation. Verif.AI's user-friendly browser extension seamlessly verifies online claims with exceptional speed, empowering you to make informed decisions and build a stronger society. Join us in the fight against fake news and misinformation with Verif.AI - where truth is just a click away.
            </p>
            <a href="https://chromewebstore.google.com/" style="display: inline-block;">
                <img src="/images/index/download_now.svg" class="download" alt="Download Now">
            </a>
        </div>
    </div>
    <img src="/images/index/markus-spiske-2G8mnFvH8xk-unsplash.jpg" class="news" alt="news">
</div>

