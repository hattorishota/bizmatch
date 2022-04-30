<template>
  <div class="p-5">
    <!-- page-wrapper Start-->
    <div class="page-wrapper">
      <!-- error-404 start-->
      <div class="error-wrapper">
        <div class="container">
          <div class="error-heading">
            <h2 class="headline font-danger">404</h2>
          </div>
          <div class="col-md-8 offset-md-2">
            <p class="sub-content">ご希望のページはございません。おそらく削除されたか現状存在いたしません。</p>
          </div>
          <div><router-link class="btn btn-danger-gradien btn-lg" :to="{ name: 'top' }">トップページへ</router-link></div>
        </div>
      </div>
      <!-- error-404 end-->
    </div>
  </div>
</template>