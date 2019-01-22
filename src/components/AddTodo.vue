<template>

  <div>

    <form>
      <input type="text" name="title" placeholder="Add Todo...">

      <input type="submit" value="submit" class="btn">

    </form>

  </div>

</template>

<script>
export default{
  name:'AddTodo'
}

</script>


<style scoped>
form{
  display: flex;
}
input[type="text"]{
  flex: 10;
  padding: 5px;
}

input[type="submit"]{
  flex: 2;
}

.btn{
  display: inline-block;
  border: none;
  background: #555;
  color:#fff;
  padding: 7px 20px;
  cursor: pointer;
}

.btn:hover{
  background: #666;
}
</style>
