<script>

</script>

<section>
    <div class="container">
        <div class="panel pricing-table">
          
          <div class="pricing-plan">
            <img src="https://s22.postimg.cc/8mv5gn7w1/paper-plane.png" alt="" class="pricing-img">
            <h2 class="pricing-header">Basic Bot</h2>
            <ul class="pricing-features">
              <li class="pricing-features-item">Basic Features</li>
              <li class="pricing-features-item">Moderation, Server Management</li>
            </ul>
            <span class="pricing-price"><span class="pricing-discount">$1.99</span> $1.00</span>
            <a href="/contact" class="pricing-button">Buy Now</a>
          </div>
          
          <div class="pricing-plan">
            <img src="https://s28.postimg.cc/ju5bnc3x9/plane.png" alt="" class="pricing-img">
            <h2 class="pricing-header">Utility Bot</h2>
            <ul class="pricing-features">
              <li class="pricing-features-item">3 Main Features</li>
              <li class="pricing-features-item">All features from the Basic Bot</li>
            </ul>
            <span class="pricing-price">$3.99</span>
            <a href="/contact" class="pricing-button is-featured">Free trial</a>
          </div>
          
          <div class="pricing-plan">
            <img src="https://s21.postimg.cc/tpm0cge4n/space-ship.png" alt="" class="pricing-img">
            <h2 class="pricing-header">Custom Bot</h2>
            <ul class="pricing-features">
              <li class="pricing-features-item">Full Custom Bot</li>
              <li class="pricing-features-item">Activities, Databases, Web Integration etc</li>
            </ul>
            <span class="pricing-price">$4.99</span>
            <a href="/contact" class="pricing-button">Free trial</a>
          </div>
        </div>
        <span class="disclaimer">*All Bots have a 1 week free trial, thereafter the bot ceases its functions if payment is due.</span>
        <a href="/" class="go-back-button">Go back</a>
      </div>
</section>

<style>

section {
  height: 100dvh;
  background-color: #016ff9;
}

*,
*:before,
*:after {
  box-sizing: inherit;
}

.container {
  margin: 0 auto;
  padding: 50px 0 0;
  max-width: 960px;
  width: 100%;
}

.panel {
  background-color: #fff;
  border-radius: 10px;
  padding: 15px 25px;
  position: relative;
  width: 100%;
  z-index: 10;
}

.pricing-table {
  box-shadow: 0px 10px 13px -6px rgba(0, 0, 0, 0.08),
    0px 20px 31px 3px rgba(0, 0, 0, 0.09), 0px 8px 20px 7px rgba(0, 0, 0, 0.02);
  display: flex;
  flex-direction: column;
}

@media (min-width: 900px) {
  .pricing-table {
    flex-direction: row;
  }
}

.pricing-table * {
  text-align: center;
  text-transform: uppercase;
}

.pricing-plan {
  border-bottom: 1px solid #e1f1ff;
  padding: 25px;
}

.pricing-plan:last-child {
  border-bottom: none;
}

@media (min-width: 900px) {
  .pricing-plan {
    border-bottom: none;
    border-right: 1px solid #e1f1ff;
    flex-basis: 100%;
    padding: 25px 50px;
  }

  .pricing-plan:last-child {
    border-right: none;
  }
}

.pricing-img {
  margin-bottom: 25px;
  max-width: 100%;
}

.pricing-header {
  color: #888;
  font-weight: 600;
  letter-spacing: 1px;
}

.pricing-features {
  color: #016ff9;
  font-weight: 600;
  letter-spacing: 1px;
  margin: 50px 0 25px;
}

.pricing-features-item {
  border-top: 1px solid #e1f1ff;
  font-size: 12px;
  line-height: 1.5;
  padding: 15px 0;
}

.pricing-features-item:last-child {
  border-bottom: 1px solid #e1f1ff;
}

.pricing-price {
  color: #016ff9;
  display: block;
  font-size: 32px;
  font-weight: 700;
}

.pricing-discount {
    color: red;
    text-decoration:line-through;
}

.pricing-button {
  border: 1px solid #9dd1ff;
  border-radius: 10px;
  color: #348efe;
  display: inline-block;
  margin: 25px 0;
  padding: 15px 35px;
  text-decoration: none;
  transition: all 150ms ease-in-out;
}

.pricing-button:hover,
.pricing-button:focus {
  background-color: #e1f1ff;
}

.pricing-button.is-featured {
  background-color: #48aaff;
  color: #fff;
}

.pricing-button.is-featured:hover,
.pricing-button.is-featured:active {
  background-color: #269aff;
}

.disclaimer {
    color: gray;
}

.go-back-button {
  font-size: 20px;
}

</style>