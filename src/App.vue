<script>

import siteHeader from "./components/siteHeader.vue"
import siteMain from "./components/siteMain.vue"
import siteFooter from "./components/SiteFooter.vue"

export default {
  components:{
    siteHeader,
    siteMain,
    siteFooter
  },
  data() {
    return {

    }
  }
}
</script>

<template>

<siteHeader></siteHeader>
<siteMain></siteMain>
<siteFooter></siteFooter>
 
</template>

<style lang="scss" scoped></style>
 