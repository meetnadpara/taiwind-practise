<template>
  <div class="container">
    <Header></Header>
    <firstpage class="first-page"></firstpage>
    <secondpage class="first-page"></secondpage>
    <plans class="first-page"></plans>
    <global class="first-page"></global>
    <review class="first-page"></review>
    <subscribe class="firstpage"></subscribe>
    <footerpage class="firstpage"></footerpage>
    
  </div>
</template>

<script>	
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import firstpage from '@/components/first-page.vue'
import secondpage from '@/components/second-page.vue'
import plans from '@/components/plans.vue'
import global from '@/components/global.vue'
import review from '@/components/review.vue'
import subscribe from '@/components/subscribe.vue'
import footerpage from '@/components/footer.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Header,
    firstpage,
    secondpage,
    plans,
    global,
    review,
    subscribe,
    footerpage
  }
}
</script>
