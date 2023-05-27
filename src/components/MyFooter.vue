<template>
  <div>
    <footer class="section-p1">
      <div class="col">
        <img
          class="logo"
          src="https://marcas-logos.net/wp-content/uploads/2019/11/Nike-Logo.png"
          alt=""
        />
        <h4>Contact</h4>
        <p>
          <strong>Address : </strong>Jl.Kelapa Gading, Jakarta Utara, Jakarta
        </p>
        <p><strong>Phone : </strong>(+62)8118131010</p>
        <p><strong>Hours : </strong>10:00 - 22:00, Mon - Sat</p>
        <div class="follow">
          <h4>Follow Us</h4>
          <div class="icon">
            <img
              src="https://solciotyfitness.com/wp-content/uploads/2018/01/IG-ICON.png"
              alt=""
            />
            <img
              src="https://clipground.com/images/facebook-black-clipart-9.jpg"
              alt=""
            />
            <img
              src="https://th.bing.com/th/id/R.8eb68c7065e5057c9314f335d1bcb4a6?rik=jN4%2f3c2j9%2fNquA&riu=http%3a%2f%2fpluspng.com%2fimg-png%2ftwitter-png-twitter-icon-1600.png&ehk=cfVuY5vaxmKssnSiLi2qsApgVuOQ2a3R0fEel7T0mJk%3d&risl=&pid=ImgRaw&r=0"
              alt=""
            />
            <img
              src="https://th.bing.com/th/id/R.9f705111f037ae799f0bcf9633be3ca1?rik=S1APAPrO4DitgA&riu=http%3a%2f%2fcdn.onlinewebfonts.com%2fsvg%2fimg_427156.png&ehk=gaOCv7%2fvVMvnvRnnXlwM6oMhJy4rgItgQs7c8WTNijA%3d&risl=&pid=ImgRaw&r=0"
              alt=""
            />
            <img
              src="https://th.bing.com/th/id/R.d7f036fe6751d31a62a90ab78b9d656c?rik=sb%2b0kh%2fk56yCpw&riu=http%3a%2f%2fcdn.onlinewebfonts.com%2fsvg%2fimg_106006.png&ehk=lV1zZNQZrZ7OvaopxN615mouKUya68bLlp8tzllb9WM%3d&risl=&pid=ImgRaw&r=0"
              alt=""
            />
          </div>
        </div>
      </div>
      <div class="col">
        <h4>About</h4>
        <a href="#">About Us</a>
        <a href="#">Delivery Information</a>
        <a href="#">Privacy Policy</a>
        <a href="#">Terms & Conditions</a>
        <a href="#">Contact Us</a>
      </div>
      <div class="col">
        <h4>My Account</h4>
        <a href="#">Sign In</a>
        <a href="#">View Cart</a>
        <a href="#">My Wishlist</a>
        <a href="#">Track My Order</a>
        <a href="#">Help</a>
      </div>
      <div class="col install">
        <h4>Install App</h4>
        <p>From App Store or Google Play</p>
        <div class="row">
          <img
            src="https://leadpedalradio.com/wp-content/uploads/2021/04/338_Z29vZ2xlIHBsYXkgYW5kIGFwcCBzdG9yZSBidXR0b25z-1.jpg"
            alt=""
          />
        </div>
        <div class="payment">
          <p>Secured Payment Gateways</p>
          <img
            src="https://th.bing.com/th/id/R.c4bd375e38d9eec842b9cd15607e233b?rik=gvs9nYhGi3wnKg&riu=http%3a%2f%2fvippayment.asia%2flogo%2fvisa.png&ehk=C3H%2fwYw1SXMDNBq%2b6uGbPRhTdK1VJH9Ojao9wu9CuRA%3d&risl=&pid=ImgRaw&r=0"
            alt=""
          />
          <img
            src="https://th.bing.com/th/id/R.4029a955c02e580933415bf057e77cdb?rik=ruO8CZEosbo1Og&riu=http%3a%2f%2f3.bp.blogspot.com%2f_HXdYEMKoVg0%2fTSOlZY_AF_I%2fAAAAAAAAABo%2fZ4UezUTjms4%2fs1600%2fmastercard.jpg&ehk=vDz6udwY45ev3YbW%2bFOv3eh4MpxxP2Ui6xuMsPJiwFA%3d&risl=&pid=ImgRaw&r=0"
            alt=""
          />
        </div>
      </div>
      <div class="copyright">
        <p>&copy; 2023, Tech2 etc - HTML CSS E-commerce Template</p>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
    name:'MyFooter'
};
</script>
<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: sans-serif;
}

h1 {
  font-size: 50px;
  line-height: 64px;
  color: #222;
}

h2 {
  font-size: 46px;
  line-height: 54px;
  color: #222;
}

h4 {
  font-size: 20px;
  color: #222;
}

h6 {
  font-weight: 700;
  font-size: 12px;
}

p {
  font-size: 16px;
  color: #465b52;
  margin: 15px 0 20px 0;
}

.section-p1 {
  padding: 40px 80px;
}

.section-m1 {
  margin: 40px 0;
}

footer {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  background: #e3e6f3;;
}

.logo {
  width: 70px;
  height: fit-content;
}

footer .col {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin-bottom: 20px;
}

footer .logo {
  margin-bottom: 30px;
}

footer h4 {
  font-size: 14px;
  padding-bottom: 20px;
}

footer p {
  font-size: 13px;
  margin: 0 0 8px 0;
}

footer a {
  font-size: 13px;
  text-decoration: none;
  color: #222;
  margin-bottom: 10px;
}

footer .follow {
  margin-top: 20px;
}

footer .follow img {
  width: 20px;
  height: 20px;
  margin: 2px;
}

footer .row img {
  width: 330px;
  height: 110px;
  border: 1px solid #088178;
  padding: 6px 6px 6px 6px;
  border-radius: 6px;
  margin-bottom: 10px;
}

footer .payment img {
  width: 80px;
  height: 40px;
  margin: 10px 0 15px 0;
}

footer .col a:hover {
  color: #088178;
}

footer .copyright {
  width: 100%;
  text-align: center;
}

</style>
