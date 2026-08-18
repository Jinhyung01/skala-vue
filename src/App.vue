<script setup>
import BindBasic from './components/practices/directive/BindBasic.vue'
import BindClass from './components/practices/directive/BindClass.vue'
import BindShorthand from './components/practices/directive/BindShorthand.vue'
import BindStyle from './components/practices/directive/BindStyle.vue'
import DirectiveHtml from './components/practices/directive/DirectiveHtml.vue'
import DirectiveHtmlXss from './components/practices/directive/DirectiveHtmlXss.vue'
import DirectiveText from './components/practices/directive/DirectiveText.vue'
</script>

<template>
  <div style="padding: 20px">
    <DirectiveHtml />
    <DirectiveHtmlXss />
    <DirectiveText />
    <BindBasic />
    <BindClass />
    <BindStyle />
    <BindShorthand />
  </div>
</template>
