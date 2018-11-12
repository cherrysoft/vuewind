<template>
<div id="home">
    <!-- buttons -->
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <simple></simple><pill></pill><bordered></bordered>
              <disabled></disabled><three-d></three-d><elevated></elevated>
              <groups></groups><icons></icons>
          </div>
      </div>
    </div>
    <!-- alerts -->
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <traditional></traditional>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <modern-badge></modern-badge>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <left-accent-border></left-accent-border>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <danger></danger>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <solid></solid>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <top-accent-border></top-accent-border>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <banner></banner>
          </div>
      </div>
    </div>
    <!-- navigation -->
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <simple-nav></simple-nav>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <responsive-header></responsive-header>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <tabs></tabs>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <pills></pills>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <stretched></stretched>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <justified></justified>
          </div>
      </div>
    </div>
    <!-- cards -->
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <stacked></stacked>
          </div>
      </div>
    </div>
    <div class="flex mb-4">
      <div class="container mx-auto">
          <div class="w-full bg-grey-lightest h-12">
              <horizontal></horizontal>
          </div>
      </div>
    </div>

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
/* alerts */
import Traditional from '@/components/alerts/Traditional'
import ModernBadge from '@/components/alerts/ModernBadge'
import LeftAccentBorder from '@/components/alerts/LeftAccentBorder'
import Danger from '@/components/alerts/Danger'
import Solid from '@/components/alerts/Solid'
import TopAccentBorder from '@/components/alerts/TopAccentBorder'
import Banner from '@/components/alerts/Banner'
/* alerts */
import Stacked from '@/components/cards/Stacked'
import Horizontal from '@/components/cards/Horizontal'
/** navigation */
import SimpleNav from '@/components/navigation/Simple'
import ResponsiveHeader from '@/components/navigation/ResponsiveHeader'
import Tabs from '@/components/navigation/Tabs'
import Pills from '@/components/navigation/Pills'
import Stretched from '@/components/navigation/Stretched'
import Justified from '@/components/navigation/Justified'

export default {
  name: 'Home',
  components: {
    Simple,
    Pill,
    Bordered,
    Disabled,
    ThreeD,
    Elevated,
    Groups,
    Icons,
    Traditional,
    ModernBadge,
    LeftAccentBorder,
    Danger,
    Solid,
    TopAccentBorder,
    Banner,
    Stacked,
    Horizontal,
    SimpleNav,
    ResponsiveHeader,
    Tabs,
    Pills,
    Stretched,
    Justified
  }
}
</script>
