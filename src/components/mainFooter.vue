<template>
  <footer class="mt-5 p-5 text-center">
    <div class="container">
      <div class="links">
        <a href="#" class="btn">Home</a>
        <a href="#" class="btn">Info</a>
        <a href="#" class="btn">Brands</a>
      </div>
      <h6 class="text-uppercase m-3">Created By Ahmed Ragab &copy; 2021</h6>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  position: relative;

  &:after {
    content: "";
    position: absolute;
    top: 0;
    width: 90%;
    left: 5%;
    margin: auto;
    height: 1px;
    background-color: #999;
  }
}
</style>
