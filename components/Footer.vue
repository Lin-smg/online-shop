<template>
<div class="font-small lighten-3 pt-4 mt-4">
    <b-container class="text-center text-md-left">
      <b-row class="my-4">
        <b-col md="4" lg="4">
          <h5 class="text-uppercase mb-4 font-weight-bold">Footer Content</h5>
          <p>Here you can use rows and columns here to organize your footer content.</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit, error amet numquam iure provident
              voluptate esse quasi, veritatis totam voluptas nostrum. </p>
        </b-col>
        <hr class="clearfix w-100 d-md-none"/>
        <b-col md="2" lg="2" class="ml-auto">
          <h5 class="text-uppercase mb-4 font-weight-bold">About</h5>
          <ul class="list-unstyled">
            <p><a href="#!">PROJECTS</a></p>
            <p><a href="#!">ABOUT US</a></p>
            <p><a href="#!">BLOG</a></p>
            <p><a href="#!">AWARDS</a></p>
          </ul>
        </b-col>
        <hr class="clearfix w-100 d-md-none"/>
        <b-col md="5" lg="3">
          <h5 class="text-uppercase mb-4 font-weight-bold">Address</h5>
          <p><b-icon icon="home" class="mr-3" /> New York, NY 10012, US</p>
          <p><b-icon icon="envelope" class="mr-3" /> info@example.com</p>
          <p><b-icon icon="phone" class="mr-3" /> + 01 234 567 88</p>
          <p><b-icon icon="print" class="mr-3" /> + 01 234 567 89</p>
        </b-col>
        <hr class="clearfix w-100 d-md-none"/>
        <b-col md="2" lg="2" class="text-center">
          <h5 class="text-uppercase mb-4 font-weight-bold">About</h5>
          <div class="mt-2 ">
            <a type="button" class="btn-floating btn-small btn-fb"><b-icon icon="facebook"/></a>
            <a type="button" class="btn-floating btn-small btn-tw"><b-icon icon="twitter" /></a>
            <a type="button" class="btn-floating btn-small btn-gplus"><b-icon fab icon="google-plus" /></a>
            <a type="button" class="btn-floating btn-small btn-dribbble"><b-icon fab icon="dribbble" /></a>
          </div>
        </b-col>
        <hr class="clearfix w-100 d-md-none"/>
      </b-row>
    </b-container>
    <div class="footer-copyright text-center py-3">
      <b-container fluid>
          &copy; 2020 Copyright: <a href="https://www.MDBootstrap.com"> MDBootstrap.com </a>
      </b-container>
    </div>
</div>
  
   <!-- <b-footer color="stylish-color-dark" class="font-small pt-4 mt-4">
    <b-container class="text-center text-md-left">
      <b-row class="text-center text-md-left mt-3 pb-3">
        <b-col md="3" lg="3" xl="3" class="mx-auto mt-3">
          <h6 class="text-uppercase mb-4 font-weight-bold">Company name</h6>
          <p>Here you can use rows and columns here to organize your footer content. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit.</p>
        </b-col>
        <hr class="w-100 clearfix d-md-none" />
        <b-col md="2" lg="2" xl="2" class="mx-auto mt-3">
          <h6 class="text-uppercase mb-4 font-weight-bold">Products</h6>
          <p><a href="#!">MDBootstrap</a></p>
          <p><a href="#!">MDWordPress</a></p>
          <p><a href="#!">BrandFlow</a></p>
          <p><a href="#!">Bootstrap Angular</a></p>
        </b-col>
        <hr class="w-100 clearfix d-md-none" />
        <b-col md="3" lg="2" xl="2" class="mx-auto mt-3">
          <h6 class="text-uppercase mb-4 font-weight-bold">Useful links</h6>
          <p><a href="#!">Your Account</a></p>
          <p><a href="#!">Become an Affiliate</a></p>
          <p><a href="#!">Shipping Rates</a></p>
          <p><a href="#!">Help</a></p>
        </b-col>
        <hr class="w-100 clearfix d-md-none" />
        <b-col md="4" lg="3" xl="3" class="mx-auto mt-3">
          <h6 class="text-uppercase mb-4 font-weight-bold">Contact</h6>
          <p><i class="fas fa-home mr-3"></i> New York, NY 10012, US</p>
          <p><i class="fas fa-envelope mr-3"></i> info@gmail.com</p>
          <p><i class="fas fa-phone mr-3"></i> + 01 234 567 88</p>
          <p><i class="fas fa-print mr-3"></i> + 01 234 567 89</p>
        </b-col>
      </b-row>
      <hr />
      <b-row class="d-flex align-items-center">
        <b-col md="8" lg="8">
          <p class="text-center text-md-left grey-text">&copy; 2020 Copyright: <a href="https://www.MDBootstrap.com">
              MDBootstrap.com </a></p>
        </b-col>
        <b-col md="4" lg="4" class="ml-lg-0">
          <div class="text-center text-md-right">
            <ul class="list-unstyled list-inline">
              <li class="list-inline-item"><a class="btn-floating btn-sm rgba-white-slight mx-1"><i class="fab fa-facebook"></i></a></li>
              <li class="list-inline-item"><a class="btn-floating btn-sm rgba-white-slight mx-1"><i class="fab fa-twitter"></i></a></li>
              <li class="list-inline-item"><a class="btn-floating btn-sm rgba-white-slight mx-1"><i class="fab fa-google-plus"></i></a></li>
              <li class="list-inline-item"><a class="btn-floating btn-sm rgba-white-slight mx-1"><i class="fab fa-linkedin-in"></i></a></li>
            </ul>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </b-footer> -->
</template>

<style scoped>
.fluid-container.footer{
  background: blue;
}
.fluid-container.footer > *:last-child {
    margin-bottom: 0px;
    color: #fff;
}
</style>