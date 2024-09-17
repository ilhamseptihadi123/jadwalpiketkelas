<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">RIWAYAT Piket Kelas</h2>
        <div class="my-3">
          <form>
            <input type="search" class="form-control form-control-lg rounded-3" placeholder="Filter...">
          </form>
          </div>
        <div class="my-3 text-muted"> menampilkan dari  </div>
        <table class="table">
          <thead>
            <tr>
              <td>Hari/tgl</td>
              <td>NAMA</td>
              <td>Tugas Piket</td>
              <td>Email</td>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>senin,....</td>
              <td>senin,....</td>
              <td>senin,....</td>
              <td>senin,....</td>
            </tr>
            <tr>
              <td>senin,....</td>
              <td>senin,....</td>
              <td>senin,....</td>
              <td>senin,....</td>
            </tr>
            <tr>
              <td>senin,....</td>
              <td>senin,....</td>
              <td>senin,....</td>
              <td>senin,....</td>
            </tr>
            <tr>
              <td>senin,....</td>
              <td>senin,....</td>
              <td>senin,....</td>
              <td>senin,....</td>
            </tr>
            <tr>
              <td>senin,....</td>
              <td>senin,....</td>
              <td>senin,....</td>
              <td>senin,....</td>
            </tr>
          </tbody>
          </table>

      </div>
      <NuxtLink to="/walikelas/">
      <button type="button" class="btn btn-success">Kembali</button>
    </NuxtLink>
    </div>
  
  </div>
</template>
<style scoped>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
</style>