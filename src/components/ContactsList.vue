<template>
  <h2>Contact list</h2>
  <ul class="list-group">
      <li class="list-group-item" v-for="contact in contacts" :key="contact.id">
          {{ contact.name }}
      </li>
  </ul>
</template>

<script>
export default {
    name: "ContactsList",
    props: {
        contacts: Array
    }
}
</script>