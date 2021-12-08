<template>
  <section class="account-form">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 col-md-6">
          <label class="font-weight-bold text-dark">Nome</label>
          <input
            id="name"
            name="name"
            type="text"
            class="form-control"
            placeholder=""
          />
        </div>
        <div class="col-lg-4 col-md-6">
          <label class="font-weight-bold text-dark">Sobrenome</label>
          <input
            id="name"
            name="name"
            type="text"
            class="form-control"
            placeholder=""
          />
        </div>
        <div class="col-lg-4 col-md-6">
          <label class="font-weight-bold text-dark">E-Mail</label>
          <input
            id="name"
            name="name"
            type="email"
            class="form-control"
            placeholder=""
          />
        </div>
      </div>
    </div>
    <!-- /.container -->
  </section>
</template>

<script>
export default {
    name: "NewAccount"
}
</script>

<style scoped></style>
