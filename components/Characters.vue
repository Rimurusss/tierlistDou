<template>
  <v-container id="mainc" class="text-white">
    <div v-for="d in data" :key="d" >
    <div class="tier">
      <div class="tier-list" >
        <a class="character-img"  v-for="x in d" :key="x" >
              <img :src="x.profileimg" class="character-name"/>
              <!-- <img
            src=""
            class="character-type" alt="SSR"
            />
            </div>-->
            <h2 class="character-name">{{x.id}}</h2> 
            <!-- </div> -->
        </a>
        </div>
          </div>
      
    </div>
  </v-container>
</template>

<script>
import datalist from "~/data/datalist.json";
export default {
  data() {
    return {
      data: datalist,
    };
  },
};
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
  width: 5%;
  padding: 10px;
}
.character-name {
  /* width: 100%;
  color: #fff;
  font-size: 14px;
  text-align: center;
  margin: 10px 0 0;
  overflow: hidden;
  text-overflow: ellipsis;
  transition: color 0.3s; */
}
/* .character-type {
  position: absolute;
  top: 25%;
  right: 80%;
  width: 40px;
  height: 30px;
  background: #36384a;
  border-radius: 100px;
  padding: 2px;
} */
.character-icon {
  /* width: 50px; */
  /* height: 50px; */
  /* background: #36384a; */
  /* border-radius: 4px; */
}
img {
  border-style: none;
}
</style>