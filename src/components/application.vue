<template>
  <section class="application mt-5">
    <div class="container">
      <div class="row">
        <div class="col-md-6 order-md-last">
          <div class="image overflow-hidden">
            <img src="../assets/app.jpg" class="img-fluid" />
          </div>
        </div>
        <div class="col-md-6 order-md-first">
          <div class="context mt-3">
            <h2 class="d-none d-sm-block h1 text-uppercase">
              We have an Application!!!
            </h2>
            <h3 class="text-center d-block d-sm-none text-uppercase">
              We have an Application!!!
            </h3>
            <p>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              Voluptatibus eius possimus praesentium eum error velit assumenda
              perferendis tempora sit. Quod delectus soluta nostrum? Illo
              ratione quaerat repellat minima recusandae officia.
            </p>
            <div class="download">
              <img src="../assets/apple-store.svg" width="150" />
              <img src="../assets/play-store.png" width="150" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>
<style lang="scss" scoped>
.application {
  .image {
    border-radius: 20px;
    height: 100%;
    img {
      height: 100%;
      width: 100%;
      object-fit: cover;
      transition: 0.3s;

      &:hover {
        transform: scale(1.3) rotate(3deg);
      }
    }
  }

  .context {
    h2,
    h3 {
      font-weight: 900;
    }
    h2 {
      font-size: 4.1rem;
      letter-spacing: 2px;
    }

    .download {
      display: flex;
      justify-content: space-around;
      align-items: flex-start;
      gap: 5px;
      flex-direction: column;

      img {
        cursor: pointer;
        box-shadow: 5px 5px 10px rgba(153, 153, 153, 0.3),
          -5px -5px 10px rgba(153, 153, 153, 0.3);
        transition: 0.3s;
        height: 45px;

        &:hover {
          transform: scale(1.1);
        }
      }
    }
  }
}

@media (max-width: 555px) {
  h3 {
    font-size: 2.3rem;
    letter-spacing: 2px;
  }
  p {
    text-align: center;
    font-size: 0.7rem;
  }
  .download {
    flex-direction: row !important;
  }
}
</style>
