<template>
  <v-container id="mainc" class="text-white">
    <div class="tier">
      <div class="tier-list">
        <a class="character-img">
          <img
            src="https://lh4.googleusercontent.com/pUmkKR9cFvz1zY7tj8L3kjwkcf-S5i3x3_yeDnSyGKwdZrW2fnrZwqUfPg3H2aUZwefXy28mzjRrl61dLvg7f8c6iZ-l8sq0DRvEqkDmTJeUWexeQ7xrh6UpZRFbD1ZqggkchGRI-w"
            class="character-icon" 
          />
          <img
            src="https://yt3.ggpht.com/U3TkbpoMof4xGHZ_L6JmcYDOv6LVhzewGFy_8thMDvwv-62NqeGxK94_E-kzO7MpVO1l6AcWLA=w48-h48-c-k-nd"
            class="character-type" alt="SSR"
          />

          <h2 class="character-name">tangGG</h2>
        </a>

        <a class="character-img"
          ><img
            src="https://lh5.googleusercontent.com/Gh16XUwD-6vE_zM_cChr4Fm3j2yKMfpaA5yKFTrWUpBrHth8IKqPbrdUOC9gWrNY3FnB4BORD7VaD5pIEDRAoog16C1J2UdSqHK6TEmeh9M3vRINKdnaWE7cp_DGhPwqw-4RBGswKQ"
            class="character-icon"
          />
          <img
            src="https://yt3.ggpht.com/U3TkbpoMof4xGHZ_L6JmcYDOv6LVhzewGFy_8thMDvwv-62NqeGxK94_E-kzO7MpVO1l6AcWLA=w48-h48-c-k-nd"
            class="character-type" alt="SSR"
          />
          <h2 class="character-name">posaisea</h2>
        </a>

        <a class="character-img"
          ><img
            src="https://lh4.googleusercontent.com/pUmkKR9cFvz1zY7tj8L3kjwkcf-S5i3x3_yeDnSyGKwdZrW2fnrZwqUfPg3H2aUZwefXy28mzjRrl61dLvg7f8c6iZ-l8sq0DRvEqkDmTJeUWexeQ7xrh6UpZRFbD1ZqggkchGRI-w"
            class="character-icon"
          />
          <img
            src="https://yt3.ggpht.com/U3TkbpoMof4xGHZ_L6JmcYDOv6LVhzewGFy_8thMDvwv-62NqeGxK94_E-kzO7MpVO1l6AcWLA=w48-h48-c-k-nd"
            class="character-type"
          />
          <h2 class="character-name">posaisea</h2>
        </a>
        <a class="character-img"
          ><img
            src="https://lh5.googleusercontent.com/skPi5VxuzZXKy9KW6RAaf1DKC3aJ_COTtP91s594GpLeCQtdES0LBHJBbbDdqmC2PNQn71ATBRTGNZLq-MmFaCDUvDK4Hs4YgY6SunS4PMr9f5GrIe7cijpjEHLtgltxUao7abT_ag"
            class="character-icon"
          />
          <img
            src="https://yt3.ggpht.com/U3TkbpoMof4xGHZ_L6JmcYDOv6LVhzewGFy_8thMDvwv-62NqeGxK94_E-kzO7MpVO1l6AcWLA=w48-h48-c-k-nd"
            class="character-type"
          />
          <h2 class="character-name">posaisea</h2>
        </a>
        
      </div>
    </div>
  </v-container>
</template>

<script>
export default {};
</script>

<style>
#mainc {
  background-color: rgb(47, 45, 45);
}
.tier-title {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 70px;
  min-width: 70px;
  color: #28211f;
  font-size: 18px;
  font-weight: 700;
  background: rgb(228, 8, 8);
}
.tier {
  display: flex;
  width: 100%;
  min-height: 70px;
  background: #272937;
  border-radius: 4px;
  overflow: hidden;
  box-shadow: 0 1px 2pxrgba (0, 0, 0, 0.24), 0 1px 3pxrgba (0, 0, 0, 0.12);
  margin-bottom: 20px;
}
.tier-list {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  flex-grow: 1;
  padding: 5px;
}
.character-img {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 8%;
  padding: 10px;
}
.character-name {
  width: 100%;
  color: #fff;
  font-size: 14px;
  text-align: center;
  margin: 10px 0 0;
  overflow: hidden;
  text-overflow: ellipsis;
  transition: color 0.3s;
}
.character-type {
  position: absolute;
  top: 142px;
  /* right: 80%; */
  width: 40px;
  height: 30px;
  background: #36384a;
  border-radius: 100px;
  padding: 2px;
}
.character-icon {
  /* width: 50px; */
  /* height: 50px; */
  /* background: #36384a; */
  /* border-radius: 4px; */
}
img{
    border-style: none;
}
</style>