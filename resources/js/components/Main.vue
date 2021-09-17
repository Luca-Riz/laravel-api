<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-6">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Special title treatment</h5>
            <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
  data() {
    return {
      chiamataApi: 'http://127.0.0.1:8000/api/posts'
    }
  },
  created(){
    console.log(this.chiamataApi);
  },
  methods:{

  }
}
</script>

<style lang="sass" scoped>

</style>