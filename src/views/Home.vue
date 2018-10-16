<template>
  <div class="home">
    
  <div>
      
  </div>

  <div v-for="person in peoples">
    <h2>{{ people.name }} - {{ people.bioVisible }}</h2>
    <p>{{ people.bio }}</p>
  </div>

</div>
</template>

<style>
</style>

<script>
export default {
  data: function() {
    return {
      message: "Welcome to Vue.js!",
      people: [
      {
        name: "Daisy",
        bio: "Loves to dance",
        bioVisible: false
      },
      {
        name: "James",
        bio: "Favorite hobby is to eat out",
        bioVisible: false
      },
      {
        name: "James",
        bio: "Favorite hobby is to eat out",
        bioVisible: false
      }
      ],
      addPerson: {name: "", bio:""}
    };
  },
  created: function() {},
  methods: {},
  computed: {}
};
</script>