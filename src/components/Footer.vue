<template>
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
                      <SocialIcoList
                        v-for="(icon, index) in socialIcons"
                        :key=index
                        :link="icon.link"
                        :iconClass="icon.iconClass"
                      />
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
import SocialIcoList from './SocialIcoList'
export default {
  name: 'Footer',
  components: {
    SocialIcoList
  },
  props: {
    socialIcons: [
      {link: "https://github.com/pabloleonalcaide", iconClass:"fa-github"},
      {link: "https://stackoverflow.com/users/8029716/pablo-león", iconClass:"fa-stack-overflow"},
      {link: "https://www.linkedin.com/in/pablo-leon-alcaide/", iconClass:"fa-linkedin"},
      {link: "https://twitter.com/PabloLeonPsi", iconClass:"fa-twitter"}
    ]
  }
}
</script>
<style lang="scss">

$base-color: #3498db;
$text: #74808a;

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
</style>