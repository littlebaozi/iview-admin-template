<template>
  <div class="login">
    <div class="login-con">
      <div class="login-cover">
        {{$config.title}}
      </div>
 
      <div class="form-con">
        <login-form @on-success-valid="handleSubmit"></login-form>
      </div>

    </div>
  </div>
</template>

<script>
import LoginForm from './login-form'
import { mapActions } from 'vuex'
export default {
  components: {
    LoginForm
  },
  methods: {
    ...mapActions([
      'handleLogin',
      'getUserInfo'
    ]),
    handleSubmit ({ userName, password }) {
      this.handleLogin({ userName, password }).then(res => {
        this.getUserInfo().then(res => {
          this.$router.push({
            name: this.$config.homeName
          })
        })
      })
    }
  }
}
</script>

<style lang="less">
  @import './login.less';
</style>