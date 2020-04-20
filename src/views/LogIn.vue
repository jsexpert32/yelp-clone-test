<template>
  <div class="wrap">
    <Header></Header>
    <div class="main-content-wrap main-content-wrap--full">
        <div class="content-container">
            <div class="clearfix layout-block layout-h row--responsive">
                <div class="column column-alpha column--responsive">
                    <div class="signup-wrapper">
                        <SignInForm></SignInForm>
                    </div>
                </div>
                <div class="column column-beta responsive-visible-large-block">
                    <div class="picture-container">
                        <img src="https://s3-media0.fl.yelpcdn.com/assets/2/www/img/7922e77f338d/signup/signup_illustration.png">
                    </div>
                </div>
            </div>
        </div>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>

import Header from '@/components/Common/header'
import Footer from '@/components/LandingPage/Footer'
import SignInForm from '@/components/Form/SignInForm'

export default {
  name: "LogIn",
  components: {
      Header,
      Footer,
      SignInForm
  },
  data () {
    return {
    }
  },
  methods: {
  }
};
</script>
