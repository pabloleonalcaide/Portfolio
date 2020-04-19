<template>
    <div>
        <div id="mobile-menu-open" class="shadow-large">
            <i class="fa fa-bars" aria-hidden="true"></i>
        </div>
        <Header/>

        <Lead/>

        <About/>

        <Experience/>

        <Education/>

        <Projects/>

        <Articles/>

        <Skills/>

        <Contact/>

        <Footer/>
    </div>
</template>
<script>
import About from './About'
import Articles from './Articles'
import Contact from './Contact'
import Education from './Education'
import Experience from './Experience'
import Footer from './Footer'
import Header from './Header'
import Lead from './Lead'
import Projects from './Projects'
import Skills from './Skills'
export default {
  name: 'Portfolio',
  components: {
      About,
      Articles,
      Contact,
      Education,
      Experience,
      Header,
      Footer,
      Lead,
      Projects,
      Skills
  }
}
</script>

<style lang="scss">

$base-color: #3498db;
$base-color-hover: darken($base-color, 10%);
$secondaryColor: #91842f;
$background: #fff;
$background-alt: rgba(115, 42, 140, 0.8);

$border: #dcd9d9;

$heading: #333333;
$text: #74808a;

html {
    scroll-behavior: smooth !important;
}
body {
    font-family: 'Lato', sans-serif;
    font-size: 16px;

    &.active {
        overflow: hidden;
        z-index: -1;
    }
    a {
        color: $secondaryColor;
        &:hover{
            color: darken($secondaryColor, 10%);
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
    font-weight: 400;
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
        background: $secondaryColor;
    }
}

.background-alt {
    background: $background-alt;
    .heading{
        color: #fff;
    }
}

@keyframes scaleAnimation {
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

#projects, #articles {
    padding: 50px 15px;
    border-bottom: 1px solid $border;
    h2 {
        margin-bottom: 50px;
    }
}

.no-image {
    .project-info {
        position: relative;
        margin: 0;
        padding: 30px 15px;
        transform: none;
    }
}

@media only screen and (max-width: 750px) {

    #experience-timeline {
        &:before, &:after {
            left: 23px;
        }
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
    .article-image,
    .project-image {
        display: none;
    }
    .article-info
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

@media only screen and (max-width : 996px) {
    #about {
        .profilePhoto {
            img{
                display: none;
            }
        }
    }

}

</style>