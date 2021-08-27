<template>
  <section class="personal-info mt-5">
    <div class="container">
      <h2 class="text-center d-none d-sm-block h1 mb-5">
        Lorem ipsum dolor sit amet
      </h2>
      <h3 class="text-center d-block d-sm-none mb-5">
        Lorem ipsum dolor sit amet
      </h3>
      <div class="row">
        <div class="col-lg-5 offset-lg-1 mb-4">
          <div class="personal-card-1">
            <img src="../assets/1.gif" class="img-fluid" />
            <div class="context">
              <div class="text">
                <h3>consectetur adipisicing elit</h3>
                <p>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                  Maxime, rerum illo accusamus mollitia sint ducimus impedit.
                </p>
                <small class="text-center mt-3">Tap To Read More</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-5">
          <div class="personal-card-2">
            <img src="../assets/2.gif" class="img-fluid" />
            <div class="context">
              <div class="text">
                <h3>consectetur adipisicing elit</h3>
                <p>
                  Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                  Maxime, rerum illo accusamus mollitia sint ducimus impedit.
                </p>
                <small class="text-center mt-3">Tap To Read More</small>
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
.personal-card-1,
.personal-card-2 {
  padding: 20px;
  min-height: 400px;
  border-radius: 20px;
  background-color: #f1f1f1;
  position: relative;

  img {
    border-radius: 20px;
    box-shadow: 5px 5px 7px rgba(190, 190, 190, 0.9),
      -5px -5px 7px rgba(190, 190, 190, 0.9);
  }

  .context {
    position: absolute;
    left: 0px;
    bottom: 0px;
    margin: 0px;
    width: 100%;
    height: 100%;
    padding: 20px;

    .text {
      background-color: rgba(0, 0, 0, 0.2);
      box-shadow: 0 -10px 5px rgba(0, 0, 0, 0.2);
      border-radius: 20px;
      height: 300px;
      width: 100%;
      position: absolute;
      bottom: 0;
      left: 0;
      color: #f1f1f1;
      display: flex;
      justify-content: center;
      align-content: center;
      flex-direction: column;
      text-align: center;
      padding: 0 10%;

      h3 {
        font-size: 3rem;
        font-weight: 900;
        text-transform: uppercase;
      }
      p {
        font-size: 0.75rem;
      }

      small {
        padding: 8px 10px;
        border-radius: 10px;
        background-color: rgba(153, 153, 153, 0.3);
        width: 150px;
        margin: 10px auto;
        cursor: pointer;
        transition: 0.3s;

        &:hover {
          background-color: rgba(153, 153, 153, 0.6);
        }
      }
    }
  }
}

@media (max-width: 555px) {
  .personal-card-1,
  .personal-card-2 {
    .context {
      .text {
        h3 {
          font-size: 2rem;
        }

        small {
          padding: 5px 8px;
          border-radius: 8px;
          width: 120px;
          font-size: 0.75rem;
        }
      }
    }
  }
}
</style>
