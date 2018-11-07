<template>
<div id="home">
  <simple></simple>
  <pill></pill>
  <bordered></bordered>
  <disabled></disabled>
  <three-d></three-d>
  <elevated></elevated>
  <groups></groups>
  <icons></icons>
</div>
</template>

<script>
/* buttons */
import Simple from '@/components/buttons/Simple'
import Pill from '@/components/buttons/Pill'
import Bordered from '@/components/buttons/Bordered'
import Disabled from '@/components/buttons/Disabled'
import ThreeD from '@/components/buttons/ThreeD'
import Elevated from '@/components/buttons/Elevated'
import Groups from '@/components/buttons/Groups'
import Icons from '@/components/buttons/Icons'

export default {
  name: 'Home',
  components: {
    Simple, Pill, Bordered, Disabled, ThreeD, Elevated, Groups, Icons
  }
}
</script>
