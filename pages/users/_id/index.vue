<template>
    <div>
     <h1>This is a Single Page for User id: {{ $route.params.id }}</h1>   
    </div>
</template>

<script>
export default {
    validate(data){
        console.log(data);
        return /^\d+$/.test(data.params.id)
    },
    layout:'users'
}
</script>