<template>
  <div class="container">
    <h2 class="ui header head">WELCOME TO SPOTUBE WEBAPP</h2>
    <div class="ui input inputted" style="width:95%">
      <input
        type="text"
        placeholder="Please paste the playlist that will converted to a youtube links"
      />
      <button class="ui icon button">
        <i class="search icon"></i>
      </button>
    </div> <br>
    <small>ps : *playlist should be open for everyone</small>
  </div>
</template>

<script>
export default {};
</script>
<style scoped lang="">
.container{
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.inputted{
    margin-left:11px;
}
small {
  font-size: 15px;
  color: brown;
}
.head {
  text-align: center;
  padding: 25px;
}
</style>
