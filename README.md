# Nurul Aini Portfolio
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Review this part and modify it to your liking -->
    <meta name="description" content="Sample text for portfolio template meta tag">
    <meta name="keywords" content="Sample text for portfolio template meta tag">
    <meta name="author" content="Sample text for portfolio template meta tag">
    <title>About me</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="stylesheet" type="text/css" href="style-about-me.css">
    <!-- font for the quote -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Covered+By+Your+Grace&display=swap" rel="stylesheet">
    <!-- font for the body -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@200&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400&display=swap" rel="stylesheet">
    <!-- font for headings -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@200&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400&display=swap" rel="stylesheet">
</head>

<body>
    <!-- navigation bar -->
    <nav class="sticky">
        <label for="drop" class="toggle" id="main-toggle">
            <span class="nav-icon"></span>
        </label>
        <input type="checkbox" id="drop">
        <ul class="main-nav">
            <li><a href="index.html">Home</a></li>
            <li><a href="about-me.html">About me</a></li>
            <li><a href="skill-set.html">Skill-set</a></li>
            <li><a href="portfolio.html">Portfolio</a></li>
            <li><a href="index.html#contact-me">Contact me</a></li>
        </ul>
    </nav>

    <!-- about me -->
    <!-- section1 - introduction -->
    <section class="grid-system-2 w-900 padding">
        <section class="center align-center">
            <img class="max-width" src="assets/about-me1.png" alt="picture-of-me">
        </section>
        <section class="justify">
            <h2 class="main-title-large">Who Am I?</h2>
            <p>I am XY</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias laborum deserunt doloribus impedit dolores
                modi exercitationem similique cumque officiis facere distinctio voluptates obcaecati eum praesentium
                nemo, libero natus reiciendis ipsam. Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
            <p class="quote uppercase center"><span class="colorful-letter">This is important</span> a quote or
                something else.</p>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatem deleniti id possimus dicta eaque?
                Quis, fugiat minus similique nemo ipsam ut delectus voluptates dolorem, consectetur rerum et rem, cumque
                officia.</p>
        </section>
    </section>


    <!-- section2 - background story -->
    <!-- use this section to tell, why did you choose programming -->
    <section class="grid-system-2 w-900 padding">
        <section class="justify">
            <h2 class="main-title-large center">How it all started...</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolore voluptatum a officiis commodi dicta,
                dolor vitae eligendi quos recusandae saepe, asperiores deleniti cumque, sed repudiandae aut alias
                voluptates amet optio!</p>
            <p class="italic">- Lorem, ipsum dolor sit.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio impedit eius totam, iste unde ad
                inventore error quis! Quasi, libero fuga harum a inventore totam minus quibusdam et voluptate ea!
            </p>
        </section>
        <section class="center align-center">
            <img class="max-width" src="assets/about-me2.png" alt="story-of-myself">
        </section>
    </section>


    <!-- section3 - future plans -->
    <!-- great way to show that you are always involved -->
    <section class="w-900">
        <section class="baby-pink-light">
            <h3 class="main-title center">Future plans</h3>
            <ul class="justify padding-list-10">
                <li class="no-padding-list-item">
                    Write here about the courses you may attend at the moment, etc. <span
                        class="bold colorful-letter">Something you learn</span> through <span
                        class="bold colorful-letter"><a class="link" href="https://academy.zerotomastery.io/"
                            target="_blank">a school's link</a></span>
                    an esteemed online school.
                </li>
                <li class="no-padding-list-item">
                    Maybe you have something else in your plate at the moment. Share that too <span
                        class="bold colorful-letter">Something important</span>
                </li>
                <li class="no-padding-list-item">
                    Do you have ongoing projects? Tell more about them <span class="bold uppercase colorful-letter">two
                        ongoing
                        projects</span>. One involves bla bla bla, while the other is
                    bla blabla bla. Both projects are bla bla...
                </li>
                <li class="no-padding-list-item">
                    Something you are already proud of? A great project, or achievement? Don't forget to mention it. Maybe
                    you may speak about the most important concepts you have encountered so far <span class="bold">bla bla,
                        bla blabla, blabla bla, bla and the bla</span>. And some other stuff..
                </li>
                <p>Something important here, <span class="italic">what you beleive in, etc.</span> </p>
            </ul>
        </section>
    </section>

    <!-- section4 - hobbies -->
    <!-- this is a 4 grid hobby-system, maybe you have more hobbies, then double it...
     or double it and modify it to the class "grid-system-2" so you can have 6 hobbies all together, it's all your choice  -->
    <section class="margin-trbl10">
        <section>
            <h3 class="main-title center padding">Hobbies and Free Time Activities</h3>
        </section>
        <section class="grid-system-4 w-900">
            <section class="card small-card justify">
                <img class="box margin-auto hobbies" src="assets/dog.png" alt="hobbies1">
                <p class="bold center">My dog</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur eum rerum provident laudantium
                    modi veniam accusamus reiciendis id itaque iure qui, corrupti repellendus ipsam neque! Fuga
                    architecto laborum vitae quibusdam?</p>
            </section>
            <section class="card small-card justify">
                <img class="box margin-auto hobbies" src="assets/board-game.png" alt="hobbies2">
                <p class="bold center">Playing</p>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Maxime dignissimos et, magnam aperiam
                    distinctio, asperiores est laborum deserunt reprehenderit, praesentium accusamus dolorum illum.
                    Voluptatum non mollitia in neque dolore corporis!</p>
            </section>
            <section class="card small-card justify">
                <img class="box margin-auto hobbies" src="assets/coding.png" alt="hobbies3">
                <p class="bold center">Coding</p>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem, provident? Amet quam id veritatis,
                    similique distinctio quibusdam, velit ex sed impedit natus corporis vel. Iste iusto nobis veritatis
                    inventore quibusdam.</p>
            </section>
            <section class="card small-card justify">
                <img class="box margin-auto hobbies" src="assets/plot-reading.png" alt="hobbies4">
                <p class="bold center">Wierd stuff</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus facilis, repellat animi eum ab
                    dolores neque, pariatur, molestias inventore soluta voluptatum a deleniti fugit natus ullam modi
                    debitis sunt sapiente.</p>
            </section>
        </section>
    </section>

    <!-- footer -->
    <footer>@iluskaland 2024</footer>
</body>

</html>
