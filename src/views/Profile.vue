<template>
  <div class="profile">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <div class="media">
            <img src="../assets/images.jpg" class="user-pic mr-3" />
            <div class="media-body">
              <h5 class="mt-0">Enoge Cakep</h5>
              <p>
                Will you do the same for me? It's time to face the music I'm no
                longer your muse.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "Profile",
  components: {},
};
</script>

<style scoped>
.user-pic {
  width: 80px;
  height: 80px;
  border-radius: 200%;
}
</style>