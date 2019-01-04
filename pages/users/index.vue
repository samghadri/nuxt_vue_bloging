<template>
    <div>
        <input type="text" v-model="userId">
        <button @click="onLoaderCLick">load user </button>
    </div>

</template>

<script>
export default {
    data(){
        return{
            userId:""
        }
    },
    methods:{
       onLoaderCLick(){
           this.$router.push('/users/' + this.userId)
       }
    },
    layout: 'users',
}
</script>