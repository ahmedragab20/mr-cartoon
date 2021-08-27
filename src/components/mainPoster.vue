<template>
  <div class="poster"></div>
</template>

<style lang="scss" scoped>
.poster {
  height: 50vh;
  width: 90%;
  margin: 30px auto;
  position: relative;
  background: url(../assets/poster.jpg) center no-repeat;
  background-size: cover;
  border-radius: 20px;

  &:hover::after {
    transform: scale(1);
  }

  &::after {
    content: "Go To The Store?!";
    min-width: 160px;
    padding: 20px;
    text-align: center;
    border-radius: 20px;
    background-color: rgba(17, 17, 17, 0.7);
    box-shadow: 5px 5px 10px rgba(153, 153, 153, 0.5),
      -5px -5px 10px rgba(153, 153, 153, 0.5);
    color: #fff;
    position: absolute;
    top: 50%;
    left: 65%;
    font-size: 1.2rem;
    font-weight: 600;
    transition: 0.3s;
    cursor: pointer;
    transform: scale(0);
  }
}

@media (max-width: 768px) {
  .poster {
    height: 15vh;

    &::after {
      content: "Click To Go To Our Store";
      font-size: 0.9rem;
      background-color: rgba(17, 17, 17, 0.6);
      box-shadow: 5px 5px 10px rgba(153, 153, 153, 0.3),
        -5px -5px 10px rgba(153, 153, 153, 0.3);
      inset: 0;
      transform: scale(1);
      display: flex;
      justify-content: center;
      align-items: center;
    }
  }
}
</style>
