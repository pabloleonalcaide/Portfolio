<template>
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
</template>
<script>
export default {
  name: 'Experience'
}
</script>
<style lang="scss" scoped>

$background: #fff;
$base-color: #3498db;
$border: #dcd9d9;
$heading: #374054;
$text: #74808a;

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

</style>