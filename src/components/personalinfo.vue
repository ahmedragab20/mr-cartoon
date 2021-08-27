<template>
  <section class="personal-info mt-5">
    <div class="container">
      <h2 class="text-center d-none d-sm-block h1 mb-5">
        Let's know each other <i class="bi bi-emoji-smile-upside-down"></i>
      </h2>
      <h3 class="text-center d-block d-sm-none mb-5">
        Let's know each other <i class="bi bi-emoji-smile-upside-down"></i>
      </h3>
      <div class="row">
        <div class="col-lg-5 offset-lg-1 mb-4">
          <div class="personal-card">
            <div class="container">
              <div
                class="
                  card-header
                  h-50
                  d-flex
                  justify-content-between
                  align-items-center
                "
              >
                <div class="image w-25">
                  <img src="../assets/john.jpg" class="img-fluid" />
                </div>
                <div class="info w-75">
                  <h3>John Henderson</h3>
                  <button class="btn btn-outline-primary">View Profile</button>
                </div>
              </div>
              <div class="card-context h-50 p-3">
                <p>
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum
                  nesciunt placeat dicta expedita, dolor numquam consectetur
                  cumque dolores nihil, quam voluptas magni magnam quae maxime
                  minima suscipit, tempora delectus saepe.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-5">
          <div class="personal-card">
            <div class="container">
              <div
                class="
                  card-header
                  h-50
                  d-flex
                  justify-content-between
                  align-items-center
                "
              >
                <div class="image w-25">
                  <img src="../assets/mikle.jpg" class="img-fluid" />
                </div>
                <div class="info w-75">
                  <h3>Mickle Lawrence</h3>
                  <button class="btn btn-outline-primary">View Profile</button>
                </div>
              </div>
              <div class="card-context h-50 p-3">
                <p>
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum
                  nesciunt placeat dicta expedita, dolor numquam consectetur
                  cumque dolores nihil, quam voluptas magni magnam quae maxime
                  minima suscipit, tempora delectus saepe.
                </p>
              </div>
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
.personal-info {
  h2,
  h3 {
    font-weight: 900;
  }

  .personal-card {
    border-radius: 20px;
    box-shadow: 5px 5px 5px rgba(153, 153, 153, 0.2),
      -5px -5px 5px rgba(153, 153, 153, 0.2);
    margin: 0 15px;

    h3 {
      font-weight: 900;
    }

    .image {
      img {
        border-radius: 15px;
        transform: scale(0.7);
      }
    }

    .card-header {
      background: none;

      .info {
        padding-left: 10px;
        .btn {
          border-radius: 20px;
        }
      }
    }
    .card-context {
      p {
        font-size: 0.9rem;
      }
    }
  }
}
@media (max-width: 555px) {
  .personal-info {
    .personal-card {
      .card-header {
        .info {
          padding-top: 20px;
          h3 {
            font-size: 0.9rem;
          }
          .btn {
            font-size: 0.75rem;
          }
        }
      }
      .card-context {
        p {
          font-size: 0.6rem;
        }
      }
    }
  }
}
</style>
