<template>
  <div class="restaurant-card">
    <div class="restaurant-img"></div>
    <div class="restaurant-info">
      <div class="top">
        <p class="name">Subway</p>
        <p class="note">
          <span> 4.5 </span>
        </p>
      </div>
      <p class="time">20-30min</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'RestaurantCard'
}
</script>

<style lang="scss">
.restaurant-card {
  width: 32%;
  height: 30vh;

  p {
    margin: 0px;
  }
  .restaurant-img {
    background-image: url('https://cn-geo1.uber.com/image-proc/resize/eats/format=webp/width=550/height=440/quality=70/srcb64=aHR0cHM6Ly9kMXJhbHNvZ25qbmczNy5jbG91ZGZyb250Lm5ldC8zNzg4MDJiMC1jNTI4LTQ4MjktYjBiNS0wY2M2NDBkZjYzY2QuanBlZw==');
    height: 70%;
    background-size: cover;
    background-position: center;
  }

  .restaurant-info {
    .top {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin: 10px 0px;

      .note {
        background-color: #eee;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 30px;
        width: 30px;
        font-size: 0.8rem;
        border-radius: 50%;
      }
    }

    .time {
      font-size: 0.9rem;
    }
  }
}
</style>
