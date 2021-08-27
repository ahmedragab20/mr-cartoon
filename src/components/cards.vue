<template>
  <section class="cards mt-5">
    <div class="container">
      <h2 class="text-center d-none d-sm-block h1 mb-5">
        Some Of Our Categories
      </h2>
      <h3 class="text-center d-block d-sm-none mb-5">Some Of Our Categories</h3>
      <div class="row">
        <div class="col-lg-3 col-md-6 mb-3">
          <div class="card overflow-hidden">
            <div class="image h-50 overflow-hidden">
              <img src="../assets/card-1.jpg" class="card-img-top h-100" />
            </div>
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <a href="#" class="btn btn-primary">Read more</a>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 mb-3">
          <div class="card overflow-hidden">
            <div class="image h-50 overflow-hidden">
              <img src="../assets/card-2.jpg" class="card-img-top h-100" />
            </div>
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <a href="#" class="btn btn-primary">Read more</a>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 mb-3">
          <div class="card overflow-hidden">
            <div class="image h-50 overflow-hidden">
              <img src="../assets/card-3.png" class="card-img-top h-100" />
            </div>
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <a href="#" class="btn btn-primary">Read more</a>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 mb-3">
          <div class="card overflow-hidden">
            <div class="image h-50 overflow-hidden">
              <img src="../assets/card-4.jpg" class="card-img-top h-100" />
            </div>
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <a href="#" class="btn btn-primary">Read more</a>
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
.cards {
  h2,
  h3 {
    font-weight: 900;
  }

  .card {
    height: 400px;
    box-shadow: 5px 5px 10px rgba(153, 153, 153, 0.3),
      -5px -5px 10px rgba(153, 153, 153, 0.3);
    border-radius: 20px;
    border: none;
    margin: 0 10px;
    .image {
      img {
        object-fit: cover;
        transition: 0.3s;

        &:hover {
          transform: scale(1.2) rotate(5deg);
        }
      }
    }

    .card-body {
      a {
        border-radius: 15px;
      }
    }
  }
}
</style>
