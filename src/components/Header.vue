<template>
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
</template>

<script>
export default {
  name: 'Header'
}
</script>
<style lang="scss">

$base-color: #91842f;
$base-color-hover: darken($base-color, 10%);
$background: #fff;

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
</style>