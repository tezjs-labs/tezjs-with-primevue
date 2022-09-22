<script>
import ScrollPanel from 'primevue/scrollpanel';
export default {
  layoutName: "default",
  components:{
    ScrollPanel
  }
};
</script>

<template>
  <div class="grid mt-6">
    <div class="col-2"></div>
    <div class="col-8">
      <div class="card bg-gray-100">
        <OrderList>
          <h1 class="text-gray-800">List of Products</h1>
          <hr />
          <ScrollPanel style="width: 100%; height: 400px" class="custom">
            <div class="grid">
              <div class="col-6 md:col-10">
                <div class="grid">
                  <div class="col-6 lg:col-2">
                    <img
                      class="border-round"
                      src="../assets/images/game-controller.jpg"
                      width="100"
                      height="100"
                    />
                  </div>
                  <div class="col-6 ml-2 lg:col-2 lg:ml-4">
                    <span class="md:text-xl font-bold">Game Controller</span>
                    <p>Electronics</p>
                  </div>
                </div>
              </div>
              <div class="col-6 md:col-2">
                <p>$99</p>
                <div class="bg-yellow-300 w-max p-1 border-round md:text-lg">
                  LOWSTOCK
                </div>
              </div>
            </div>
            <hr />
            <div class="grid">
              <div class="col-6 md:col-10">
                <div class="grid">
                  <div class="col-6 lg:col-2">
                    <img
                      class="border-round"
                      src="../assets/images/blue-t-shirt.jpg"
                      width="100"
                      height="100"
                    />
                  </div>
                  <div class="col-6 ml-2 lg:col-2 lg:ml-4">
                    <span class="md:text-xl font-bold">Blue T-Shirt</span>
                    <p>Clothing</p>
                  </div>
                </div>
              </div>
              <div class="col-6 md:col-2">
                <p>$29</p>
                <div class="bg-green-300 w-max p-1 border-round md:text-lg">
                  INSTOCK
                </div>
              </div>
            </div>
            <hr />
            <div class="grid">
              <div class="col-6 md:col-10">
                <div class="grid">
                  <div class="col-6 lg:col-2">
                    <img
                      class="border-round"
                      src="../assets/images/black-watch.jpg"
                      width="100"
                      height="100"
                    />
                  </div>
                  <div class="col-6 ml-2 lg:col-2 lg:ml-4">
                    <span class="md:text-xl font-bold">Black Watch</span>
                    <p>Accessories</p>
                  </div>
                </div>
              </div>
              <div class="col-6 md:col-2">
                <p>$72</p>
                <div class="bg-green-300 w-max p-1 border-round md:text-lg">
                  INSTOCK
                </div>
              </div>
            </div>
            <hr/>
            <div class="grid">
              <div class="col-6 md:col-10">
                <div class="grid">
                  <div class="col-6 lg:col-2">
                    <img
                      class="border-round"
                      src="../assets/images/blue-band.jpg"
                      width="100"
                      height="100"
                    />
                  </div>
                  <div class="col-6 ml-2 lg:col-2 lg:ml-4">
                    <span class="md:text-xl font-bold">Blue Band</span>
                    <p>Fitness</p>
                  </div>
                </div>
              </div>
              <div class="col-6 md:col-2">
                <p>$79</p>
                <div class="bg-green-300 w-max p-1 border-round md:text-lg">
                  LOWSTOCK
                </div>
              </div>
            </div>
            <hr/>
            <div class="grid">
              <div class="col-6 md:col-10">
                <div class="grid">
                  <div class="col-6 lg:col-2">
                    <img
                      class="border-round"
                      src="../assets/images/brown-purse.jpg"
                      width="100"
                      height="100"
                    />
                  </div>
                  <div class="col-6 ml-2 lg:col-2 lg:ml-4">
                    <span class="md:text-xl font-bold">Brown Purse</span>
                    <p>Accessories</p>
                  </div>
                </div>
              </div>
              <div class="col-6 md:col-2">
                <p>$120</p>
                <div class="bg-red-300 w-max p-1 border-round md:text-lg">
                  OUTOFSTOCK
                </div>
              </div>
            </div>
          </ScrollPanel>
        </OrderList>
      </div>
    </div>
    <div class="col-2"></div>
  </div>
</template>

<style>
.card {
  background: #ffffff;
  padding: 2rem;
  box-shadow: 0 2px 1px -1px rgba(0, 0, 0, 0.2), 0 1px 1px 0 rgba(0, 0, 0, 0.14),
    0 1px 3px 0 rgba(0, 0, 0, 0.12);
  border-radius: 4px;
  margin-bottom: 0rem;
}

.custom .p-scrollpanel-wrapper {
    border-right: 9px solid #f4f4f4;
}

.custom .p-scrollpanel-bar {
    background-color: #1976d2;
    opacity: 1;
    transition: background-color .3s;
}

.custom .p-scrollpanel-bar:hover {
    background-color: #135ba1;
}
</style>