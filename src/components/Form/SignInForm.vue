<template>
    <div class="signup-flow on-flow-start">
        <div class="login" data-component-bound="true">
            <div class="signup-form-container">
                <div class="header">
                    <h2>Log In to Yelp</h2>
                    <p class="subheading">New to Yelp? <a class="signup-link u-pseudo-link" href="/signup">Sign up</a></p>
                    <p class="legal-copy">
                        By logging in, you agree to Yelp’s <a class="legal-link" href="https://www.yelp.com/static?p=tos">Terms of Service</a>                        and <a class="legal-link" href="https://www.yelp.com/tos/privacy_policy">Privacy Policy</a>.
                    </p>
                </div>
                <div class="js-biz-owner-alert alert u-hidden">
                    Want Yelp for Business Owners? <a href="https://biz.yelp.com/">Go there now »</a></div>
                <ul class="ylist">
                    <li class="fb-login" data-component-bound="true">
                        <button type="submit" value="submit" class="ybtn ybtn--social ybtn--facebook ybtn-full"><span><div class="u-text-centered"><span aria-hidden="true" style="width: 24px; height: 24px;" class="icon icon--24-facebook icon--size-24 icon--currentColor">
    <svg role="img" class="icon_svg">
        <use xlink:href="#24x24_facebook"></use>
    </svg>
</span> Log In with Facebook</div></span></button>
                    </li>

                    <li class="google-login" data-component-bound="true">
                        <button type="submit" value="submit" class="ybtn ybtn--social ybtn--google ybtn-full"><span><div class="u-text-centered"><span class="icon--png"><img height="24" width="24" src="https://s3-media0.fl.yelpcdn.com/assets/srv0/yelp_styleguide/cae242fd3929/assets/img/structural/24x24_google_rainbow.png" srcset="https://s3-media0.fl.yelpcdn.com/assets/srv0/yelp_styleguide/c193df424e16/assets/img/structural/24x24_google_rainbow@2x.png 2x"></span> Log In with Google</div></span></button>
                    </li>


                </ul>
                <fieldset class="login-separator hr-line">
                    <legend align="center">OR</legend>
                </fieldset>

                <form @submit.prevent="logIn()" class="yform" id="ajax-login">
                    <input type="hidden" name="csrftok" class="csrftok" value="aacbed32796d63f377e07ed968a4a97f8369019ca23bb5306214824280e4ca1f">
                    <label class="placeholder-sub">Email</label>
                    <input id="email" name="email" placeholder="Email" required="required" type="email" value="">
                    <label class="placeholder-sub">Password</label>
                    <input id="password" name="password" placeholder="Password" required="required" type="password" value="">
                    <div class="forgot-password">
                        <small><a class="forgot-link">Forgot password?</a></small>
                    </div>
                    <div class="captcha login-captcha"></div>
                    <button type="submit" value="submit" class="ybtn ybtn--primary ybtn--big submit ybtn-full"><span>Log In</span></button>
                </form>
            </div>
            <div class="sub-text-box">
                <small class="subtle-text">New to Yelp? <a class="signup-link" href="/signup">Sign up</a></small>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "SignInForm",
  components: {
  },
  data () {
    return {
    }
  },
  methods: {
    logIn() {
    }
  }
};
</script>

<style lang="scss">

</style>