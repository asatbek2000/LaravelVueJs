<template>
  <section class="pricing py-5">
    <div class="container">
      <div class="row">
        <!-- Free Tier -->
        <div class="col-lg-4">
          <div class="card mb-5 mb-lg-0">
            <div class="card-body">
              <h5 class="card-title text-muted text-uppercase text-center">
                Weekly
              </h5>
              <h6 class="card-price text-center">
                $0<span class="period">/week</span>
              </h6>
              <hr />
              <ul class="fa-ul">
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span>Single
                  User
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span>5GB
                  Storage
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  >Unlimited Public Projects
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  >Community Access
                </li>
                <li class="text-muted">
                  <span class="fa-li"><i class="fas fa-times"></i></span
                  >Unlimited Private Projects
                </li>
                <li class="text-muted">
                  <span class="fa-li"><i class="fas fa-times"></i></span
                  >Dedicated Phone Support
                </li>
                <li class="text-muted">
                  <span class="fa-li"><i class="fas fa-times"></i></span>Free
                  Subdomain
                </li>
                <li class="text-muted">
                  <span class="fa-li"><i class="fas fa-times"></i></span>Monthly
                  Status Reports
                </li>
              </ul>
              <a href="#" class="btn btn-block btn-primary text-uppercase"
                >Button</a
              >
            </div>
          </div>
        </div>
        <!-- Plus Tier -->
        <div class="col-lg-4">
          <div class="card mb-5 mb-lg-0">
            <div class="card-body">
              <h5 class="card-title text-muted text-uppercase text-center">
                Monthly
              </h5>
              <h6 class="card-price text-center">
                $1<span class="period">/month</span>
              </h6>
              <hr />
              <ul class="fa-ul">
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  ><strong>5 Users</strong>
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span>50GB
                  Storage
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  >Unlimited Public Projects
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  >Community Access
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  >Unlimited Private Projects
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  >Dedicated Phone Support
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span>Free
                  Subdomain
                </li>
                <li class="text-muted">
                  <span class="fa-li"><i class="fas fa-times"></i></span>Monthly
                  Status Reports
                </li>
              </ul>
              <a href="#" class="btn btn-block btn-primary text-uppercase"
                >Button</a
              >
            </div>
          </div>
        </div>
        <!-- Pro Tier -->
        <div class="col-lg-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title text-muted text-uppercase text-center">
                Yearly
              </h5>
              <h6 class="card-price text-center">
                $10<span class="period">/year</span>
              </h6>
              <hr />
              <ul class="fa-ul">
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  ><strong>Unlimited Users</strong>
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span>150GB
                  Storage
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  >Unlimited Public Projects
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  >Community Access
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  >Unlimited Private Projects
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  >Dedicated Phone Support
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span
                  ><strong>Unlimited</strong> Free Subdomains
                </li>
                <li>
                  <span class="fa-li"><i class="fas fa-check"></i></span>Monthly
                  Status Reports
                </li>
              </ul>
              <a href="#" class="btn btn-block btn-primary text-uppercase"
                >Button</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  mounted() {
    console.log("Component mounted.");
  },
};
</script>

<style scoped>
section.pricing {
  background: #007bff;
  background: linear-gradient(to right, #0062e6, #33aeff);
}

.pricing .card {
  border: none;
  border-radius: 1rem;
  transition: all 0.2s;
  box-shadow: 0 0.5rem 1rem 0 rgba(0, 0, 0, 0.1);
}

.pricing hr {
  margin: 1.5rem 0;
}

.pricing .card-title {
  margin: 0.5rem 0;
  font-size: 0.9rem;
  letter-spacing: 0.1rem;
  font-weight: bold;
}

.pricing .card-price {
  font-size: 3rem;
  margin: 0;
}

.pricing .card-price .period {
  font-size: 0.8rem;
}

.pricing ul li {
  margin-bottom: 1rem;
}

.pricing .text-muted {
  opacity: 0.7;
}

.pricing .btn {
  font-size: 80%;
  border-radius: 5rem;
  letter-spacing: 0.1rem;
  font-weight: bold;
  padding: 1rem;
  opacity: 0.7;
  transition: all 0.2s;
}

/* Hover Effects on Card */

@media (min-width: 992px) {
  .pricing .card:hover {
    margin-top: -0.25rem;
    margin-bottom: 0.25rem;
    box-shadow: 0 0.5rem 1rem 0 rgba(0, 0, 0, 0.3);
  }
  .pricing .card:hover .btn {
    opacity: 1;
  }
}
</style>
