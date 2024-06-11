<template>
  <div>
    <h1>Öğrenciler</h1>
    <div v-for="student in students" :key="student.id">
        <p>{{student.name}}</p>
    </div>
  </div>
</template>

<script>
export default {
    data(){
        return{
        students: [
            {id:1, name: "Leo", not: 55},
            {id:2, name: "Adam", not: 75},
            {id:3, name: "Seth", not: 35}
    ]}
        
}

}
</script>

<style>

</style>