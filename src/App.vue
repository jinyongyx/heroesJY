<template>
  <div id="app">
    <div class="contanai">
      <span>CRUD</span>
    </div>
    <div class="contanai-center">
      <div class="contanai-center-lift">
        <div class="lift-one">Overview</div>
        <div class="lift-two">Reports</div>
        <div class="lift-three">Analytics</div>
        <div class="lift-four">Export</div>
      </div>
      <div class="contanai-center-right">
        <div class="contanai-center-right-top">
          <span>Hero List</span>
        </div>

        <div class="contanai-center-right-top">
          <button><span>Add</span></button>
        </div>


        <div class="contanai-center-right-contanni">
          <ul>
            <li>#</li>
            <li>Header</li>
            <li>Header</li>
            <li>Header</li>
            <li>Header</li>
            <li>操作</li>
          </ul>
          <ul>
            <li>1,001</li>
            <li>Lorem</li>
            <li>ipsum</li>
            <li>dolor</li>
            <li>sit</li>
            <li><a href="">edit</a> <a href="">delete</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.contanai {
  width: 100%;
  height: 50px;
  border: 1px solid black;
  background-color: black;
  display: flex;
  align-items: center;
}
.contanai span {
  color: #cccccc;
  padding-left: 20px;
}
.contanai-center {
  width: 100%;
  border: 1px solid black;
  display: flex;
  margin-top: 20px;
}
.contanai-center-lift {
  width: 15%;
  color: #3a88c9;
}
.lift-one {
  padding: 5px 15px 5px 5px;
  background: #3a88c9;
  color: aliceblue;
}
.lift-two {
  padding: 5px 15px 5px 5px;
  background: #3a88c9;
  color: aliceblue;
  margin-top: 10px;
}
.lift-three {
  padding: 5px 15px 5px 5px;
  background: #3a88c9;
  color: aliceblue;
  margin-top: 10px;
}
.lift-four {
  padding: 5px 15px 5px 5px;
  background: #3a88c9;
  color: aliceblue;
  margin-top: 10px;
}
.contanai-center-right {
  width: 85%;
}
.contanai-center-right-top {
  width: 100%;
  height: 50px;
  font-size: 24px;
  display: flex;
  align-items: center;
  margin-left: 35px;
}
.contanai-center-right-top button {
  width: 40px;
  height: 30px;
  background: #56A95A;
  border: 0;
  border-radius: 4px;
  color: aliceblue;
}
.contanai-center-right-contanni ul{
  list-style: none;
  display: flex;
  justify-content: flex-start;
}
.contanai-center-right-contanni ul li {
}

</style>



