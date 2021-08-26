<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Mr Cartoon</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Sections</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Cartoons</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Family</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
        </ul>
        <div class="left d-flex justify-content-around align-items-center">
          <form class="d-flex position-relative">
            <input
              class="form-control me-2 position-relative"
              type="search"
              placeholder="Search"
              aria-label="Search"
            />
            <i
              class="
                bi bi-search
                position-absolute
                d-flex
                justify-content-center
                align-items-center
              "
            ></i>
          </form>
          <button
            class="
              btn btn-outline-dark
              align-items-center
              d-flex
              justify-content-center
              align-items-center
            "
            type="button"
          >
            <i class="bi bi-circle-square m-1"></i> LOGIN
          </button>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
nav {
  .navbar-brand {
    font-weight: 900;
  }
  .left {
    form {
      input {
        border-radius: 20px;
        box-shadow: 3px 3px 5px rgba(153, 153, 153, 0.2),
          -3px -3px 5px rgba(153, 153, 153, 0.2);
        border: none;
      }
      .bi-search {
        top: 2px;
        right: 15px;
        padding: 5px;
        width: 30px;
        height: 30px;
        border-radius: 50%;
        background-color: #111;
        color: #fff;
        cursor: pointer;
      }
    }

    .btn {
      border-radius: 20px;
      height: 35px;
    }
  }
}
</style>
