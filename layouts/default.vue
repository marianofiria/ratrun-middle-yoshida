<template>
 <div>
   <AppHeader />
   <NuxtPage />
   <AppFooter />
 </div>
</template>


<script>

import { AppHeader } from "../components/organisms/AppHeader";
import { AppFooter } from "../components/organisms/AppFooter";

export default {

components: {AppHeader,AppFooter}

};
</script>

<style lang='scss' scoped>

</style>
