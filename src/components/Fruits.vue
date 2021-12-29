<template>
    <div>과일목록</div>
    <ul>
        <li 
            v-for="fruit in fruits"
            :key="fruit" >
            {{ fruit }}
        </li>
    </ul>
</template>
<script>
export default{
    data(){
        return{
            fruits:['Apple','Banana','Cherry']
        }
    }
}
</script>
