<template>
  <section class="scene-intro" id="intro">
    <div class="static-container">
      <h1 class="title">
        <span class="bhaumik">bhaumik</span>
        <span class="func">.is()</span>
      </h1>

      <TextBlock>
        <p class="-red">Bhaumik Soni</p>
        <p class="-gray">Cloud Data Engineer</p>
        <p class="-gray">Devops Engineer</p>
      </TextBlock>
    </div>
  </section>
</template>

<script>
import TextBlock from '../TextBlock.vue'

export default {
  name: 'IntroScene',
  components: { TextBlock },
}
</script>
