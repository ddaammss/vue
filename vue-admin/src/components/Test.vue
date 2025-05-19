<!-- <template>
    <div>
        <p>원본 메시지: "{{ message }}"</p>
        <p>역순으로 표시한 메시지: "{{ reversedMessage }}"</p>
        {{ howAreyou() }}
    </div>
</template>

<script>
export default {
    name: 'test',
    data() {
        return {
            message: '안녕하세요'
        }
    },
    computed: {
        reversedMessage() {
            return this.message.split('').reverse().join('')
        }
    },
    methods: {
        howAreyou() {
            return "i'm fine!"
        }
    }
}
</script> -->

<template>
  <div>
    <input v-model.number="width" type="number" placeholder="너비" />
    <input v-model.number="height" type="number" placeholder="높이" />
    <p>넓이: {{ area }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      width: 0,
      height: 0
    }
  },
  computed: {
    area() {
      return this.width * this.height;
    }
  }
}
</script>
