<template>
  <div class="container-fluid d-flex justify-content-center align-items.center" style="background-color: aliceblue;">
    <div class="row">
    <div class="col-2 p-2 m-5">
      <div class="card shadow p-3 rounded-4">
        <h1 class="text-center">Login</h1>
        
        <form action="#" method="post">
          <div class="mb-3">
            <label>username</label>
          <input type="text" name="username" class="rounded-3" >
          </div>
          <div class="mb-3">
            <label>password</label>
          <input type="password" name="password" class="rounded-3"><br>
          </div>
          <div class="mb-3">
            <nuxt-link to="/siswa">
            <button type="button" class="btn btn-success btn-sm">siswa</button>
          </nuxt-link>
          <nuxt-link to="/walikelas">
            <button type="button" class="btn btn-success btn-sm float-end">wali kelas</button>
          </nuxt-link>
          </div>
          <div class="text-center m-3">
          <input type="button" name="login" id="button" value="login" class="m-1 col-7 rounded-3"  >
        </div>
      </form>
      
    </div>
  </div>
  </div>
  </div>
</template>

<style scoped>
.container-fluid{
  height: 100vh;
}

.card{
  height: 300px;
  width: 300px;
  background-color: #6EAF72;
}
</style>