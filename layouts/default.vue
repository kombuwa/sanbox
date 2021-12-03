<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>
 

<<style >
 body{
   font-family: 'Yaldevi', sans-serif;
 }
</style>

<script>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'
 
export default {
  components: {
    Header,
    Footer
  }
}
</script>