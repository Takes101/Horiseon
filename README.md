# Horiseon
<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <!--Moved title element above link element-->
    <title>Horiseon</title>
    <link rel="stylesheet" href="./assets/css/style.css">
</head>

<body>
    <!--removed div class="header" for header tag-->
    <!-- header tag CSS styles would not work, need class="header"-->
    <header class="header">
        <h1>
            <!-- added anchor element so clicking the title would return to hompage -->
            <a href="/">
                Hori<span class="seo">seo</span>n
            </a>
        </h1>

        <!-- changed div below to <nav class"float-right"-->
        <nav class="float-right">
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>

    <div class="hero"></div>

    <section id="content" class="content">
        <!-- removed div and added article for search engine optimization-->
        <!-- added id tag for Search Engine Optimization-->
        <article id="search-engine-optimization" class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" id="different uses of SEO" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </article>

        <!-- removed div and added article for online reputation management-->
        <article id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" alt="where a good reputation can take you" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </article>

        <!-- removed div and added article for social media marketing-->
        <article id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" alt="capabilities of active social media" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </article>
    </section>

    <section class="benefits">
        <div id="lead-generation" class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>

        <div id="brand-awareness" class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>

        <div id="cost-management" class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png"></img>
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </section>

    <!-- changed <div> to <footer>, same problem as header: CSS would not function without class="footer"-->
    <footer class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>
</body>

</html>

