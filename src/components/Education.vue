<template>
    <div id="education">
        <h2 class="heading">Education</h2>
        <div class="education-block">
            <h3>IES Gran Capitán</h3>
            <span class="education-date">Sept 2016 - Jun 2018</span>
            <h4>Certificate of Higher Education in Web Applications development</h4>
            <p>I studied this higher education, learning languages such as Java, Python, PHP and Javascript, as well as working with version control (Git), preprocessors (scss, stylus...), code debugging and test development</p>
        </div>
        <div class="education-block">
            <h3>UNED</h3>
            <span class="education-date">Jun 2016</span>
            <h4>University Degree Psychology</h4>
            <p>I studied this university degree in order to better understand the emotions of other people and help them as much as possible</p>
        </div>
    </div>
</template>
<script>
export default {
  name: 'Education'  
}
</script>
<style lang="scss" scoped>

$border: #dcd9d9;
$heading: #374054;
$text: #74808a;

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
</style>