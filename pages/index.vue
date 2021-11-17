<template>
  <div>
    <div class="row m-0">
      <div class="col-md d-flex align-items-center justify-content-center">
        <h1 class="display-3 fw-normal text-center">
          <img
            :src="require('@/assets/images/haf-logo.png')"
            alt="haf logo"
            class="mb-1"
            style="height: 1em"
          />
          Hellenic Armed Forces
        </h1>
      </div>
      <div class="col-md">
        <div class="box-container text-center">
          <a href="https://haf.dkatsios.ml" target="_blank" class="box-link">
            <div class="box box--1">
              <h3 class="display-6 fw-bold mb-0">Air Force</h3>
            </div>
          </a>
          <a href="https://hn.dkatsios.ml" target="_blank" class="box-link">
            <div class="box box--2">
              <h3 class="display-6 fw-normal mb-0">Navy</h3>
            </div>
          </a>
          <a href="https://ha.dkatsios.ml" target="_blank" class="box-link">
            <div class="box box--3">
              <h3 class="display-6 fw-normal mb-0">Army</h3>
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
