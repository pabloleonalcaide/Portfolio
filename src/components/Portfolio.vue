<template>
    <div>
    <div id="mobile-menu-open" class="shadow-large">
        <i class="fa fa-bars" aria-hidden="true"></i>
    </div>
    <header>
        <div id="mobile-menu-close">
            <span>Close</span> <i class="fa fa-times" aria-hidden="true"></i>
        </div>
        <ul id="menu" class="shadow">
            <li>
                <a href="#about">About</a>
            </li>
            <li>
                <a href="#experience">Experience</a>
            </li>
            <li>
                <a href="#education">Education</a>
            </li>
            <li>
                <a href="#projects">Projects</a>
            </li>
            <li>
                <a href="#articles">Articles</a>
            </li>
            <li>
                <a href="#skills">Skills</a>
            </li>
            <li>
                <a href="#contact">Contact</a>
            </li>
        </ul>
    </header>

    <div id="lead">
        <div id="lead-content">
            <h1>Pablo León</h1>
            <h2>Software Developer</h2>
        </div>

        <div id="lead-overlay"></div>

        <div id="lead-down">
            <span>
                <i class="fa fa-chevron-down" aria-hidden="true"></i>
            </span>
        </div>
    </div>

    <div id="about">
        <div class="container">
            <div class="row">
                <div class="col-md-3">
                    <h2 class="heading">About Me</h2>
                </div>
                <div class="col-md-7">
                    <p>
                        My name is Pablo León, I currently reside in Córdoba, where I work as a Software Developer in Redsys. 
                        Passionate about web development and its application to improve the quality of life of people. 
                        I dedicate my free time to participate as Organizer in the Google Developers Group (GDG), organizing 
                        and giving talks about Programming and Technology, as well as in other local communities 
                        (Women TechMakers, Python Córdoba, PHP Córdoba ...). 
                        I like to stay in continuous learning and find ways to improve my work day by day.
                    </p>
                </div>
                <div class="col-md-2 profilePhoto">
                        <img src="../assets/me.jpg"/>
                    </div>
            </div>
        </div>
    </div>

    <div id="experience" class="background-alt">
        <h2 class="heading">Experience</h2>
        <div id="experience-timeline">
            <div data-date="October 2018 – March 2019">
                <h3>Software Developer</h3>
                <h4>Redsys</h4>
                <p>
                    Development (backend and frontend) of applications with Java and Spring Framework in an environment of agile methodologies.
                </p>
            </div>

            <div data-date="March 2018 – October 2018">
                <h3>Software Developer</h3>
                <h4>Signlab</h4>
                <p>
                    Web apps development with CodeIgniter (Backend), VueJS (Frontend), and corporate websites with Wordpress
                </p>
            </div>
        </div>
    </div>

    <div id="education">
        <h2 class="heading">Education</h2>
        <div class="education-block">
            <h3>IES Gran Capitán</h3>
            <span class="education-date">Sept 2016 - Jun 2018</span>
            <h4>Certificate of Higher Education in Web Applications development</h4>
            <p>I studied this higher education, learning languages ​​such as Java, Python, PHP and Javascript, as well as working with version control (github), preprocessors (sass, stylus ..), code debugging and test development </p>
        </div>
        <div class="education-block">
            <h3>UNED</h3>
            <span class="education-date">Jun 2016</span>
            <h4>University Degree Psychology</h4>
            <p>
                I studied this university degree in order to better understand the emotions of other people and help them as much as possible
            </p>
        </div>
    </div>

    <div id="projects" class="background-alt">
        <h2 class="heading">Projects</h2>
        <div class="container">
            <div class="row">
                <div class="project shadow-large">
                    <div class="project-image">
                        <img src="../assets/project.jpg" />
                    </div>
                    <div class="project-info">
                        <h3>Tweepy</h3>
                        <p>
                            Project developed together with my study partner @nievesborrero to put into practice our learning about Python, applying it to the treatment of data obtained from Twitter
                        </p>
                        <a href="https://github.com/tweepy-sysmana/sysmana2018">View Project</a>
                    </div>
                </div>

                <div class="project shadow-large">
                    <div class="project-image">
                        <img src="../assets/project.jpg" />
                    </div>
                    <div class="project-info">
                        <h3>Chatbot & Admin Panel</h3>
                        <p>
                            Chatbot developed in Dialogflow, managed in a management panel using NodeJs and Handlebars.js, as well as the APIs of Google Action, Giphy and Dialogflow
                        </p>
                        <a href="https://github.com/Proyecto-chatbot/panel-administracion-chatbot">View Project</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- End #projects -->
    <!-- Articles-->
    <div id="articles">
        <h2 class="heading">Articles</h2>
        <div class="container">
            <div class="row">
                <div class="project shadow-large article">
                    <div class="project-image article-image">
                        <img src="../assets/articles.png" />
                    </div>
                    <div class="project-info">
                        <h3>Una Introducción a la Programación Orientada a Aspectos</h3>
                        <p>
                            Article of the talk made during the <a href="https://informatica.iesgrancapitan.org/sysmanas/sysmana-xi/">Sysmana</a> event in February 2019 about Aspect Oriented Programming and its application in the Spring Framework
                        </p>
                        <a href="https://medium.com/@PabloLeonPsi/una-aproximaci%C3%B3n-a-la-programaci%C3%B3n-orientada-a-aspectos-a62d377ebe79">View Article</a>
                    </div>
                </div>

                <div class="project shadow-large article">
                    <div class="project-image article-image">
                        <img src="../assets/articles.png" />
                    </div>
                    <div class="project-info">
                        <h3>Git histories</h3>
                        <p>
                            Articles about my experience with Git and Github, adding some initial tips and recommendations
                        </p>
                        <a href="https://medium.com/@PabloLeonPsi/mi-primer-d%C3%ADa-con-github-5a11ae2bd250">Mi primer día con Git</a> | 
                        <a href="https://medium.com/@PabloLeonPsi/descubriendo-git-mas-all%C3%A1-del-add-commit-push-6efaed8ae26e">Descubriendo Git</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div id="skills" class="background-alt">
        <h2 class="heading">Skills</h2>
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>Spring</li>
            <li>JavaScript</li>
            <li>Python</li>
            <li>PHP</li>
            <li>CodeIgniter</li>
            <li>Git</li>
        </ul>
    </div>

    <div id="contact">
        <h2>Get in Touch</h2>
        <div id="contact-form">
            <form method="POST" action="https://formspree.io/pabloleonpsico@gmail.com">
                <input type="hidden" name="_subject" value="Contact request from personal website" />
                <input type="email" name="_replyto" placeholder="Your email" required>
                <textarea name="message" placeholder="Your message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </div>

    <footer>
        <div class="container">
            <div class="row">
                <div class="col-sm-5 copyright">
                    <p>
                        Copyright &copy; 2019 Pablo León Alcaide
                    </p>
                </div>
                <div class="col-sm-2 top">
                    <span id="to-top">
                        <i class="fa fa-chevron-up" aria-hidden="true"></i>
                    </span>
                </div>
                <div class="col-sm-5 social">
                    <ul>
                        <li>
                            <a href="https://github.com/pabloleonalcaide" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
                        </li>
                        <li>
                            <a href="https://stackoverflow.com/users/8029716/pablo-león" target="_blank"><i class="fa fa-stack-overflow" aria-hidden="true"></i></a>
                        </li>
                        <li>
                            <a href="https://www.linkedin.com/in/pablo-leon-alcaide/" target="_blank"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
                        </li>
                        <li>
                            <a href="https://twitter.com/PabloLeonPsi" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
    </div>
</template>
<script>
export default {
  name: 'Portfolio'
}
</script>

<style lang="scss">

$base-color: #3498db;
$base-color-hover: darken($base-color, 10%);

$background: #fff;
$background-alt: #f2f2f5;

$border: #dcd9d9;

$heading: #374054;
$text: #74808a;

@mixin transition($duration: 0.5s, $func: ease, $property: all) {
    transition: #{$duration} #{$func} #{$property};
}

@mixin placeholder {
    &::-webkit-input-placeholder {
        @content;
    }

    &:-moz-placeholder {
        @content;
        opacity: 1;
    }

    &::-moz-placeholder {
        @content;
        opacity: 1;
    }

    &:-ms-input-placeholder {
        @content;
    }
}


body {
    font-family: 'Lato', sans-serif;
    font-size: 16px;

    &.active {
        overflow: hidden;
        z-index: -1;
    }
}

.no-js {
    #experience-timeline {
        > div {
            background: $background;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid $border;

            h3 {
                font-size: 1.5em;
                font-weight: 300;
                color: $heading;
                display: inline-block;
                margin: 0;
            }

            h4 {
                font-size: 1.2em;
                font-weight: 300;
                color: #7e8890;
                margin: 0 0 15px 0;
            }

            p {
                color: $text;
                font-size: 0.9em;
                margin: 0;
            }
        }

        &:before, &:after {
            content: none;
        }
    }
}

@keyframes dropHeader {
  0% {
    transform: translateY(-100%);
  }
  100% {
    transform: translateY(0);
  }
}

header {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    text-align: center;
    z-index: 10;
    animation-name: dropHeader;
    animation-iteration-count: 1;
    animation-timing-function: ease;
    animation-duration: 0.75s;

    ul {
        display: inline-block;
        background: $background;
        text-align: center;
        padding: 10px;
        margin: 0;
        border-bottom-right-radius: 4px;
        border-bottom-left-radius: 4px;
    }

    li {
        display: inline-block;
    }

    a {
        display: block;
        color: $base-color;
        padding: 10px;

        &:hover {
            color: $base-color-hover;
            text-decoration: none;
            background: #eee;
            border-radius: 4px;
        }

        &:focus {
            color: $base-color;
            text-decoration: none;
        }
    }

    &.active {
        display: block;
    }

    &.sticky {
        position: fixed;
        z-index: 999;
    }
}

#menu {
    &.active {
        display: block;
    }
}

#mobile-menu-open {
    display: none;
    cursor: pointer;
    position: fixed;
    right: 15px;
    top: 10px;
    color: $base-color;
    font-size: 1.5em;
    z-index: 20;
    padding: 0 7px;
    border-radius: 4px;
    background: $background;
}

#mobile-menu-close {
    display: none;
    text-align: right;
    width: 100%;
    background: $background;
    font-size: 1.5em;
    padding-right: 15px;
    padding-top: 10px;
    cursor: pointer;
    color: $base-color;

    span {
        font-size: 0.5em;
        text-transform: uppercase;
    }

    i {
        vertical-align: middle;
    }
}

footer {
    padding: 50px 0;
}

.copyright {
    padding-top: 20px;

    p {
        margin: 0;
        color: $text;
    }
}

.top {
    text-align: center;

    span {
        cursor: pointer;
        display: block;
        margin: 15px auto 0 auto;
        width: 35px;
        height: 35px;
        border-radius: 50%;
        border: 3px solid lighten($text, 25%);
        text-align:center;
    }

    i {
        color: $text;
    }
}

.social {
    text-align: right;

    ul {
        margin: 5px 0 0 0;
        padding: 0;
    }

    li {
        display: inline-block;
        font-size: 1.75em;
        list-style: none;
    }

    a {
        display: block;
        color: $text;
        padding: 10px;

        &:hover {
            color: $base-color;
        }
    }
}

.btn-rounded-white {
    display: inline-block;
    color: #fff;
    padding: 15px 25px;
    border: 3px solid #fff;
    border-radius: 30px;
    @include transition();

    &:hover {
        color: $base-color;
        background: #fff;
        text-decoration: none;
    }
}

.shadow {
    box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
}

.shadow-large {
    box-shadow: 0 3px 6px rgba(0,0,0,0.08), 0 3px 6px rgba(0,0,0,0.15);
}

.heading {
    position: relative;
    display: inline-block;
    font-size: 2em;
    font-weight: 300;
    margin: 0 0 30px 0;

    &:after {
        position: absolute;
        content: '';
        top: 100%;
        height: 1px;
        width: 50px;
        left: 0;
        right: 0;
        margin: 0 auto;
        background: $base-color;
    }
}

.background-alt {
    background: $background-alt;
}

#lead {
    position: relative;
    height: 100vh;
    min-height: 500px;
    max-height: 1080px;
    background: url(../assets/lead-bg.jpg);
    background-size: cover;
    padding: 15px;
    overflow: hidden;
}

#lead-content {
    position: absolute;
    z-index: 10;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;

    h1, h2 {
        margin: 0;
    }

    h1 {
        color: #fff;
        font-weight: 900;
        font-size: 5em;
        text-transform: uppercase;
        letter-spacing: 0.05em;
        line-height: 0.9em;
    }

    h2 {
        color: lighten($base-color, 25%);
        font-weight: 500;
        font-size: 2.25em;
        margin-bottom: 15px;
    }
}

#lead-overlay {
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background: rgba($base-color-hover, 0.8);
    z-index: 1;
}

#lead-down {
    position: absolute;
    left: 0;
    right: 0;
    width: 100%;
    text-align: center;
    z-index: 10;
    bottom: 15px;
    color: #fff;

    span {
        cursor: pointer;
        display: block;
        margin: 0 auto;
        width: 35px;
        height: 35px;
        border-radius: 50%;
        border: 3px solid lighten($base-color, 25%);
        text-align:center;
    }

    i {
        animation: pulsate 1.5s ease;
        animation-iteration-count: infinite;
        padding-top: 5px;;
    }
}

@keyframes pulsate {
    0% {
        transform: scale(1, 1);
    }

    50% {
        transform: scale(1.2, 1.2);
    }

    100% {
        transform: scale(1, 1);
    }
}


#about {
    padding: 75px 15px;
    border-bottom: 1px solid $border;

    h2 {
        color: $heading;
    }

    p {
        color: $text;
        margin: 0;
    }
    .profilePhoto{
        img{
            border-radius: 50%;
            width: 100%;
            box-shadow: 0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23);
        }
    }
}

#experience {
    padding: 50px 15px;
    text-align: center;
    border-bottom: 1px solid $border;

    h2 {
        color: $heading;
    }
}

#experience-timeline {
    margin: 30px auto 0 auto;
    position: relative;
    max-width: 1000px;

    &:before {
        position: absolute;
        content: '';
        top: 0;
        bottom: 0;
        left: 303px;
        right: auto;
        height: 100%;
        width: 3px;
        background: $base-color;
        z-index: 0;
    }

    &:after {
        position: absolute;
        content: '';
        width: 3px;
        height: 40px;
        background: $base-color;
        background: linear-gradient(to bottom, $base-color, rgba($base-color, 0));
        top: 100%;
        left: 303px;
    }
}

.vtimeline-content {
    margin-left: 350px;
    background: #fff;
    border: 1px solid #e6e6e6;
    padding: 15px;
    border-radius: 3px;
    text-align: left;

    h3 {
        font-size: 1.5em;
        font-weight: 300;
        color: $heading;
        display: inline-block;
        margin: 0;
    }

    h4 {
        font-size: 1.2em;
        font-weight: 300;
        color: #7e8890;
        margin: 0 0 15px 0;
    }

    p {
        color: $text;
        font-size: 0.9em;
        margin: 0;
    }
}

.vtimeline-point {
    position: relative;
    display: block;
    vertical-align: top;
    margin-bottom: 30px;
}

.vtimeline-icon {
    position: relative;
    color: #fff;
    width: 50px;
    height: 50px;
    background: $base-color;
    border-radius: 50%;
    float: left;
    z-index: 99;
    margin-left: 280px;

    i {
        display: block;
        font-size: 2em;
        margin-top: 10px;
    }
}

.vtimeline-date {
    width: 260px;
    text-align: right;
    position: absolute;
    left: 0;
    top: 10px;
    font-weight: 300;
    color: #374054;
}

#education {
    padding: 50px 15px 20px 15px;
    border-bottom: 1px solid $border;
    text-align: center;

    h2 {
        color: $heading;
        margin-bottom: 50px;
    }
}

.education-block {
    max-width: 700px;
    margin: 0 auto 30px auto;
    padding: 15px;
    border: 1px solid $border;
    text-align: left;

    h3 {
        font-weight: 500;
        float: left;
        margin: 0;
        color: $heading;
    }

    span {
        color: $text;
        float: right;
    }

    h4 {
        color: $text;
        clear: both;
        font-weight: 500;
        margin: 0 0 15px 0;
    }

    p, ul {
        margin: 0;
        color: $text;
        font-size: 0.9em;
    }

    ul {
        padding: 0 0 0 15px;
    }
}

#projects, #articles {
    padding: 50px 15px;
    border-bottom: 1px solid $border;
    text-align: center;

    h2 {
        color: $heading;
        margin-bottom: 50px;
    }
}

.project {
    position: relative;
    max-width: 900px;
    margin: 0 auto 30px auto;
    overflow: hidden;
    background: #fff;
    border-radius: 4px;
    display: flex;
}

.project-image {
    flex: 0 0 20em;
    img{
        width: 100%
    }
}

.project-info {
    padding: 15px;

    h3 {
        font-size: 1.5em;
        font-weight: 300;
        color: $heading;
        margin: 0 0 15px 0;
    }

    p {
        color: $text;
        margin: 0 0 15px 0;
        font-size: 0.9em;
    }
}
.article{
    flex-direction:row-reverse;
}
.no-image {
    .project-info {
        position: relative;
        margin: 0;
        padding: 30px 15px;
        transform: none;
    }
}

#more-projects {
    display: none;
}

#skills {
    padding: 50px 15px;
    text-align: center;

    h2 {
        color: $heading;
        margin-bottom: 50px;
    }

    ul {
        display: flex;
        flex-wrap: wrap;
        padding: 0;
    }

    li {
        margin: 10px auto;
        padding: 5px 10px;
        list-style: none;
        overflow: hidden;
      
        border-width: 0;
        outline: none;
        border-radius: 2px;
        box-shadow: 0 1px 4px rgba(0, 0, 0, .6);
        
        background-color:$base-color;
        color: #ecf0f1;
        
        transition: background-color .3s;
        &:hover, &:focus {
            background-color: darken($base-color, 25%);
          }    
    }
}

#contact {
    padding: 50px 15px;
    background: $base-color;
    text-align: center;

    h2 {
        margin: 0 0 15px 0;
        color: #fff;
        font-weight: 500;
    }
}

#contact-form {
    max-width: 500px;
    margin: 0 auto;

    input, textarea {
        display: block;
        width: 100%;
     
        padding: 10px;
        border-radius: 4px;
        border: none;
        margin-bottom: 10px;
        background: darken($base-color, 15%);
        color: #fff;
        @include transition();
        @include placeholder {
            color: #fff;
        }

        &:focus {
            outline: none;
            background: darken($base-color, 25%);
        }
    }

    textarea {
        height: 150px;
        resize: none;
    }

    button {
        display: block;
        width: 100%;
        background: #fff;
        border-radius: 4px;
        padding: 5px 10px;
        border: none;
        color: $base-color;
        font-weight: 700;
        box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
        @include transition();

        &:hover {
            box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
        }
    }
}

.optional-section {
    padding: 50px 15px;
    text-align: center;
    border-top: 1px solid $border;

    h2 {
        color: $heading;
    }
}

.optional-section-block {
    max-width: 700px;
    margin: 0 auto 30px auto;
    padding: 15px;
    border: 1px solid $border;
    background: #fff;
    text-align: left;

    h3 {
        font-weight: 500;
        margin: 0 0 15px 0;
        color: $heading;
    }

    h4 {
        color: $text;
        clear: both;
        font-weight: 500;
        margin: 0 0 15px 0;
    }

    p, ul {
        margin: 0 0 15px 0;
        color: $text;
        font-size: 0.9em;
    }

    ul {
        padding: 0 0 0 15px;
    }
}

@media only screen and (max-width: 750px) {

    #experience-timeline {
        &:before, &:after {
            left: 23px;
        }

    }

    .vtimeline-date {
        width: auto;
        text-align: left;
        position: relative;
        margin-bottom: 15px;
        display: block;
        margin-left: 70px;
    }

    .vtimeline-icon {
        margin-left: 0;
    }

    .vtimeline-content {
        margin-left: 70px;
    }

}

@media only screen and (max-width : 992px) {

    #lead {
        height: auto;
        min-height: auto;
        max-height: auto;
        padding: 100px 15px;
    }

    #lead-content {
        position: relative;
        transform: none;
        left: auto;
        top: auto;

        h1 {
            font-size: 3em;
        }

        h2 {
            font-size: 1.75em;
        }
    }

    #about {
        text-align: center;
        .profilePhoto {
            img{
                width: 30%;
                margin-top: 20px;
            }
        }
        p {
            text-align: left;
        }
    }

}

@media only screen and (max-width : 768px) {

    header {
        position: fixed;
        display: none;
        z-index: 999;
        animation: none;
        bottom: 0;
        height: 100%;
    }

    #mobile-menu-open, #mobile-menu-close {
        display: block;
    }

    #menu {
        height: 100%;
        overflow-y: auto;
        box-shadow: none;
        border-radius: 0;
        width: 100%;

        li {
            display: block;
            margin-bottom: 10px;
        }
    }

    #lead-content {
        h1 {
            font-size: 2em;
        }

        h2 {
            font-size: 1.3em;
        }

        a {
            padding: 10px 20px;
        }
    }

    #lead-down {
        display: none;
    }

    .education-block {
        h3, span {
            float: none;
        }
    }

    .project-image {
        display: none;
    }

    .project-info {
        position: relative;
        margin: 0;
        padding: 30px 15px;
        top: auto;
        transform: none;
    }

    footer {
        text-align: center;
    }

    .social {
        text-align: center;
    }

}

@media only screen and (max-width : 480px) {
    #about {
        .profilePhoto {
            img{
                width: 40%;
            }
        }
    }
    #lead-content {
        h1 {
            font-size: 1.5em;
        }

        h2 {
            font-size: 1em;
        }

        a {
            font-size: 0.9em;
            padding: 5px 10px;
        }
    }

}

</style>