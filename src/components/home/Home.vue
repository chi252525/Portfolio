<template>
  <div id="home">
      <banner></banner>
      <Section></Section>
      <MidSection></MidSection>
      <EndFooter></EndFooter>
  </div>
</template>

<script>
import Banner from '@/components/home/Banner'
import EndFooter from '@/components/home/EndFooter'
import Section from '@/components/home/Section'
import MidSection from '@/components/home/MidSection'
export default {
  name: 'App',
  components: {
    Banner, Section, MidSection, EndFooter
  }
}
</script>

<style leng="scss">

</style>
