<template>
    <div id="experience" class="background-alt">
        <h2 class="heading">Where I've been working on</h2>
        <div id="experience-timeline">
            <div>
                <h3>Software Developer</h3>
                <h4><b>Redsys</b> (2018-Actually)</h4>
                <p>
                    Development of applications with Java (JEE) and Spring Framework in an environment of agile methodologies
                </p>
            </div>

            <div>
                <h3>Software Developer</h3>
                <h4><b>Signlab</b> (2018)</h4>
                <p>
                    Web apps development with PHP (CodeIgniter), JS (VueJS), and corporate websites with Wordpress
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
$heading: #333333;
$text: #74808a;

#experience {
    padding: 50px 15px;
    text-align: center;
    border-bottom: 1px solid $border;
}

#experience-timeline {
    margin: 30px auto 0 auto;
    position: relative;
    max-width: 1000px;
    display: flex;
    > div {
            background: $background;
            padding: 15px;
            margin: 10px;
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
@media only screen and (max-width : 480px){
    #experience-timeline{
        flex-direction: column;
    }
}

</style>