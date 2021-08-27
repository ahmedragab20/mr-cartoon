<template>
  <section class="poster-2 mt-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 order-lg-last">
          <div class="image overflow-hidden">
            <img src="../assets/poster-2.jpg" class="img-fluid" />
          </div>
        </div>
        <div class="col-lg-4 order-lg-first mt-3">
          <div class="context">
            <h2 class="d-none d-sm-block h1 mb-2 m2-5">
              Did You Hear About Lorem ipsum dolor?
            </h2>
            <p class="d-none d-sm-block mt-5 mb-1">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem
              quibusdam deserunt minima unde eligendi perferendis, illo aut
              ullam eaque officia.
            </p>
            <button class="btn btn-outline-primary d-none d-sm-block">
              Read Now!
            </button>
            <h3 class="text-center d-block d-sm-none mb-2">
              Did You Hear About Lorem ipsum dolor?
            </h3>
            <p class="text-center d-block d-sm-none mt-2 mb-1">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem
              quibusdam deserunt minima unde eligendi perferendis, illo aut
              ullam eaque officia.
            </p>
            <button class="btn btn-outline-primary d-block d-sm-none m-auto">
              Read Now!
            </button>
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
.poster-2 {
  .image {
    border-radius: 20px;
    img {
      border-radius: 20px;
      transition: 0.3s;

      &:hover {
        transform: scale(1.3) rotate(3deg);
      }
    }
  }
  h2,
  h3 {
    font-weight: 900;
  }

  .context {
    .btn {
      border-radius: 10px;
      padding: 10px 25px;
      font-size: 1.1rem;
    }
  }
}

@media (max-width: 555px) {
  .poster-2 {
    .context {
      p {
        font-size: 0.75rem;
      }
      .btn {
        border-radius: 10px;
        padding: 5px 10px;
        font-size: 1rem;
      }
    }
  }
}
</style>
