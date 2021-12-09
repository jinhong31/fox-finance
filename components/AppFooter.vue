<template>
  <footer id="footer" class="footer has-text-centered has-text-white">
    <div class="content">
      <div class="section">
        <a href="https://discord.com/invite/9XZNnTnhqp" rel="noopener" target="_blank">
          <!-- <b-icon class="mr-2" icon="discord" pack="fab" size="is-large" /> -->
          <Discord />
        </a>
        <a href="https://reddit.com/r/foxfinance" rel="noopener" target="_blank">
          <Reddit />
        </a>
        <a href="https://t.me/foxfinancebsc" rel="noopener" target="_blank">
          <Telegram />
        </a>
        <a href="https://twitter.com/foxfinancebsc" rel="noopener" target="_blank">
          <Twitter />
        </a>
      </div>
      <p>
        Copyright © 2021, Fox Finance By Fox Fi Token s.r.o. <br><br>
        All trademarks and copyrights belong to their respective owners.
      </p>
      <a class="terms-and-conditions" href="https://drive.google.com/file/d/17gcZMctKRILWcdZBwMgFrsQCso-V7uO7/view?usp=sharing">Terms and conditions</a>
    </div>
  </footer>
</template>

<script>
import Discord from './Icons/Discord'
import Reddit from './Icons/Reddit'
import Telegram from './Icons/Telegram'
import Twitter from './Icons/Twitter'

export default {
  name: 'AppFooter',
  components: { Discord, Reddit, Telegram, Twitter }
}
</script>

<style lang="scss">
#footer {
  background-color: #050e1d;
  padding-top: 50px;
  padding-bottom: 100px;
  p{
    color: #fff;
  }
}

#footer .icon {
  color: white !important;
}

#footer .section a {
  color: #fff;
}

#footer .icon:hover {
  color: #ff8936 !important;
}

.terms-and-conditions {
  color: #fff;
}

</style>
