<script setup>
import { ref } from 'vue'

const inputValue = ref('')
const message = ref('')

const showMessage = () => {
  message.value = inputValue.value
}
</script>

<template>
  <div class="practice-section">
    <h2>v-html XSS 학습</h2>
    <input v-model="inputValue" placeholder="내용을 입력하세요" />
    <button @click="showMessage">확인</button>
    <div v-html="message"></div>
    <p>※ 사용자가 입력한 값을 v-html로 출력하면 XSS 공격에 노출될 수 있습니다.</p>
  </div>
</template>
