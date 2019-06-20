<template>
  <div class="container">
    <div>
      <table>
        <tbody>
          <tr v-for="i in 10" :key="i">
            <th>User</th>
            <td>
              <nuxt-link :to="{name: 'profile-id', params: {id: i}}">{{i}}</nuxt-link>
            </td>
          </tr>
        </tbody>
      </table>
      <button @click="incrementCounter">Increment!</button>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      counter: 1
    }
  },
  methods: {
    incrementCounter() {
      this.counter++
    }
  },
  head() {
    return {
      title: this.counter + 'SUPERCALIFRAGILISTICO'
    }
  }
}
</script>
<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
