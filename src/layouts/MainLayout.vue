<template>
  <q-layout view="lHr lpR fFf"  >

    <q-header  class="text-white" style="background-color: #9070FC">
     <q-toolbar></q-toolbar>
    </q-header>


    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>



</template>

<script>
export default {
  name: "MainLayout",
  data () {
    return {
    }
  }
}
</script>
