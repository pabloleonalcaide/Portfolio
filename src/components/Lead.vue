<template>
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
</template>
<script>
export default {
  name: 'Lead'
}
</script>
<style lang="scss" scoped>

$base-color: #3498db;
$base-color-hover: darken($base-color, 10%);

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
        animation: scaleAnimation 1.5s ease;
        animation-iteration-count: infinite;
        padding-top: 5px;;
    }
}
</style>