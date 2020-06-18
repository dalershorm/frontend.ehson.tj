<template>
  <div class="">
    <div class="header flex w-full" :style="{ backgroundImage: 'url(' + require('@/assets/img/bg.jpg') + ')', backgroundSize: 'cover', backgroundPosition: 'center' }"> </div>
    <div class="flex justify-center">
      <div class="w-90">
        <div class="flex lg:flex-row flex-wrap">
          <div class="lg:w-1/2 w-full p-6">
            <div class="bg-blue-200 p-4">
              <h3 class="text-2xl">Served Over</h3>
              <h2 class="text-5xl">1,321,901</h2>
              <p class="text-2xl">Children in 150 Countries</p>
            </div>
          </div>
          <div class="lg:w-1/2 w-full">
            <div class="p-4">
              <h1 class="text-2xl">Who Are We?</h1>
              <p class="mt-5">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.</p>
              <p class="mt-6">
                <a href="#" class="border bg-teal-100 hover:bg-teal-200 rounded p-3 shadow">Подробнее</a>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="flex justify-center border-t-2 border-gray-300">
      <div class="w-90">
        <div class="flex lg:flex-row flex-wrap">
          <div class="lg:w-1/3 w-full p-6">
            <div class="p-4 relative">
              <div class="absolute left-25">
                <i class="fa fa-user"></i>
              </div>
              <h1 class="text-2xl">Who Are We?</h1>
              <p class="mt-5">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.</p>
            </div>
          </div>
          <div class="lg:w-1/3 w-full p-6">
            <div class="p-4 relative">
              <div class="absolute left-25">
                <i class="fa fa-user-friends"></i>
              </div>
              <h1 class="text-2xl">Who Are We?</h1>
              <p class="mt-5">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.</p>
            </div>
          </div>
          <div class="lg:w-1/3 w-full p-6">
            <div class="p-4 relative">
              <div class="absolute left-25">
                <i class="fa fa-heart"></i>
              </div>
              <h1 class="text-2xl">Who Are We?</h1>
              <p class="mt-5">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="flex justify-center shadow bg-gray-100">
      <div class="flex justify-center flex-wrap w-90">
          <div class="flex flex-wrap w-full justify-center">
            <h1 class="text-4xl p-3 text-center w-full">Latest Donations</h1>
            <p class="">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        <div class="flex lg:flex-row flex-wrap w-full ">
          <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4">
            <div class="m-3 text-center relative rounded bg-white card-hover">
              <img src="@/assets/img/card-image.svg" alt="" class="w-full rounded-t">
              <div class="opacity-0 absolute top-0 right-0 mr-3 mt-3 bg-gray-700 w-6 h-6 rounded heart-block">
                <i class="fa fa-heart text-white"></i>
              </div>
              <div class="text-left p-3">
                <h2 class="text-blue-400 hover:text-orange-600 font-bold"><a href="#"><a href="#">Lorem ipsum dolor sit.</a></a></h2>
                <p class="font-bold py-2">3 000 c.</p>
                <span class="text-gray-600 text-sm">Душанбе</span>
              </div>
            </div>
          </div>
          <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4">
            <div class="m-3 text-center relative rounded bg-white card-hover">
              <img src="@/assets/img/card-image.svg" alt="" class="w-full rounded-t">
              <div class="opacity-0 absolute top-0 right-0 mr-3 mt-3 bg-gray-700 w-6 h-6 rounded heart-block">
                <i class="fa fa-heart text-white"></i>
              </div>
              <div class="text-left p-3">
                <h2 class="text-blue-400 hover:text-orange-600 font-bold"><a href="#"><a href="#">Lorem ipsum dolor sit.</a></a></h2>
                <p class="font-bold py-2">3 000 c.</p>
                <span class="text-gray-600 text-sm">Душанбе</span>
              </div>
            </div>
          </div>
          <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4">
            <div class="m-3 text-center relative rounded bg-white card-hover">
              <img src="@/assets/img/card-image.svg" alt="" class="w-full rounded-t">
              <div class="opacity-0 absolute top-0 right-0 mr-3 mt-3 bg-gray-700 w-6 h-6 rounded heart-block">
                <i class="fa fa-heart text-white"></i>
              </div>
              <div class="text-left p-3">
                <h2 class="text-blue-400 hover:text-orange-600 font-bold"><a href="#"><a href="#">Lorem ipsum dolor sit.</a></a></h2>
                <p class="font-bold py-2">3 000 c.</p>
                <span class="text-gray-600 text-sm">Душанбе</span>
              </div>
            </div>
          </div>
          <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4">
            <div class="m-3 text-center relative rounded bg-white card-hover">
              <img src="@/assets/img/card-image.svg" alt="" class="w-full rounded-t">
              <div class="opacity-0 absolute top-0 right-0 mr-3 mt-3 bg-gray-700 w-6 h-6 rounded heart-block">
                <i class="fa fa-heart text-white"></i>
              </div>
              <div class="text-left p-3">
                <h2 class="text-blue-400 hover:text-orange-600 font-bold"><a href="#"><a href="#">Lorem ipsum dolor sit.</a></a></h2>
                <p class="font-bold py-2">3 000 c.</p>
                <span class="text-gray-600 text-sm">Душанбе</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  },
   data() {
      return {
          showModal: true
      }
   }
}
</script>

<style>
  .header{
    height: 567px;
  }
  .left-25{
    margin-left: -25px;
    margin-top: 5px;
  }
</style>