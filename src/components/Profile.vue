<template>
  <div class="data-container m-auto w-[1250px] flex py-10">
    <div class="profile-information-container w-[250px]">
        <div class="avatar-container">
            <div>
                <img class="rounded-full w-full h-[250px]" src="../assets/images/7.jpg" alt="">
            </div>
            <div>
              <div class=""></div>
            </div>
        </div>
        <div class="py-5">
          <h1 class="text-white text-3xl font-bold">
            @Username
          </h1>
        </div>
        <button class="bg-gray-700 w-full px-2 py-1 text-center text-white rounded-lg">
          Edit Profile
        </button>
        <div class="followers-section-container">
          <div class="flex">
            <a href="/followers"> -followers</a>
            <div class="separation">·</div>
            <a href="/following"> -following</a>
          </div>
            <div>
              <a href="">-games</a>
            </div>
        </div>
        <div class=""></div>
        <div class=""></div>
    </div>
    <div class="data-information-container w-[1000px]">
      <div class="header-container-data pt-10 px-2">
        <ul class="flex justify-between border p-2">
          <li>Profile</li>
          <li>Activity</li>
          <li>Games</li>
          <li>WatchLists</li>
        </ul>
      </div>
      <div class="favourite-container pt-20 px-2">
        <h1>
          Favourites games
        </h1>
        <div class=" ">
          <ul class="poster-list flex justify-between my-2">
              <li class="hover:scale-125"><a href="/PROFILE"><img class="w-[150px] h-[225px] rounded-lg" src="../assets/images/1.jpg" alt=""></a></li>
              <li class="hover:scale-125"><a href="/PROFILE"><img class="w-[150px] h-[225px] rounded-lg" src="../assets/images/2.jpg" alt=""></a></li>
              <li class="hover:scale-125"><a href="/PROFILE"><img class="w-[150px] h-[225px] rounded-lg" src="../assets/images/3.jpg" alt=""></a></li>
              <li class="hover:scale-125"><a href="/PROFILE"><img class="w-[150px] h-[225px] rounded-lg" src="../assets/images/4.jpg" alt=""></a></li>
              <li class="hover:scale-125"><a href="/PROFILE"><img class="w-[150px] h-[225px] rounded-lg" src="../assets/images/5.jpg" alt=""></a></li>
          </ul>
        </div>
      </div>
      <div class="recent-container">

      </div>
      <div class="inprogress-container"></div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>