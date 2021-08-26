<template>
  <section class="banner mt-4">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 order-lg-last">
          <div class="image">
            <img src="../assets/welcome.jpg" class="img-fluid" />
          </div>
        </div>
        <div class="col-lg-4 order-lg-first">
          <div
            class="
              h-100
              content
              d-flex
              justify-content-center
              align-items-center align-items-lg-start
              flex-column
            "
          >
            <h2 class="d-none d-sm-block">
              Hey, Welcome to Mr Cartoon World...
            </h2>
            <p class="d-none d-sm-block">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit.
              Exercitationem, officia. Minima ipsa magni itaque voluptatem hic?
              Asperiores eligendi nisi architecto iusto dolores.
            </p>
            <h3 class="d-block d-sm-none text-center mt-3">
              Hey, Welcome to Mr Cartoon World...
            </h3>
            <p class="d-block d-sm-none text-center">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit.
              Exercitationem, officia. Minima ipsa magni itaque voluptatem hic?
              Asperiores eligendi nisi architecto iusto dolores.
            </p>
            <button class="btn btn-outline-danger">Learn more</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.banner {
  .content {
    h2,
    h3 {
      font-weight: 900;
    }
    h2 {
      font-size: 3.5rem;
    }

    p {
      font-size: 0.75rem;
    }
    .btn {
      border-radius: 8px;
      background-color: #fb736d;
      color: #fff;
      border: none;
    }
  }
}
</style>
