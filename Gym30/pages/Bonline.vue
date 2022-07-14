<template>
    <div class="bga"> 
      <v-row class="bgsd">
        <NDraw />
        </v-row>
      <h1>Manage Online Booking</h1>
      <div class="cont">
        <v-card>
          <h2>List Online Booking</h2>
          <div class="tbl-cont">
            <table class="tbl">
              <tr>
                <th>No</th>
                <th>Name</th>
                <th>Name Class</th>
                <th>Date</th>
                <th>Status</th>
                <th>Action</th>
              </tr>
            </table>
          </div>
          page 1 of 2
        </v-card>
      </div>
      <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
      <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
      <br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
      </div>
</template>



<script>
export default {
  name: 'MemberPage',
}
</script>


<style scoped>
.tbl-cont{
  margin: 20px;
}
.tbl{
  border-collapse: collapse;
  width: 100%;
}
.tbl th td{
  border: 1px solid #ddd;
  padding: 8px;
  
}
.tbl th{
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #4fbdba;
  color: white;
}
h1{
  margin: 100px 270px 50px;
  font-size: 50px;
}
h2{
  margin: 10px 50px 10px;
  font-size: 35px;
}
.cont{
  margin: 100px 270px 50px;

}
.bga{
  background: #f4f4f4;
}
.home-section .home-content{
  position: relative;
  padding-top: 100px;
}
.home-content .overview-boxes{
  display: flex;
  width: 100%;
  justify-content: space-between;
  padding: 0px 20px;
}
.home-content .overview-boxes .box{
  width: calc(100% / 4 - 15px);
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 15px 14px;
  background: #4fbdba;
  color: white;
  border-radius: 12px;
}
.home-content .overview-boxes .box-topic{
  font-size: 20px;
  font-weight: 500;
}
.home-content .overview-boxes .number{
  font-size: 35px;
  font-weight: 800;
}
.overview-boxes .box .cart{
  font-size: 40px;
  font-weight: 500;
  height: 50px;
  width: 50px ;
}
</style>