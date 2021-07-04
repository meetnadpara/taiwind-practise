<template>
  <div>
    <Header></Header>
    <firstpage class=""></firstpage>
    <secondpage class=""></secondpage>
    <plans class=""></plans>
    <global class=""></global>
    <review class=""></review>
    <subscribe class="-mb-5/6"></subscribe>
    <footerpage class=""></footerpage>
    
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
