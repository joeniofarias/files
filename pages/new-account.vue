<template>
  <div>
    <PageHeader title="Nova Conta" />
    <NewAccount />
  </div>
</template>
<script>
import NewAccount from "~/components/NewAccount.vue";
import PageHeader from "~/components/PageHeader.vue";
export default {
  components: {
    PageHeader,
    NewAccount
  },
  head(){
    return {
      title: "Best Box USA | Cadastrar Conta"
    }
  }
}
</script>
