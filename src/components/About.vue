<template>
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
</template>
<script>
export default {
  name: 'About'
}
</script>
<style lang="scss">

$border: #dcd9d9;
$heading: #374054;
$text: #74808a;

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
</style>