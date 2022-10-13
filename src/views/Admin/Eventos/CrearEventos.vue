<template>
    <div>
       Estoy en Eventos
   <nav>
   </nav>
      <siderbar>
      </siderbar>
    </div>
    
</template>
<script>
    import axios from 'axios'
    import nav from '../../../components/NavAdmin.vue' 
import siderbar from '../../../components/Siderbar.vue'  
    export default{
      name:'',
      data(){},
      components:{ 
        nav,
        siderbar
         
    },
      methods:{
         CrearEvento()
         {
            this.$router.push('/CrearEventos')
         }
      },
      computed:{},
      mounted:{}
      } 
          
  </script>