<template>
    <div id="app">
        
          <v-app>
    <v-content class="bgr">
        <v-card  class="trslc">
            <v-img class="d-block mx-auto" src="/logo.png" width="200"></v-img>
            <v-card-title>Login</v-card-title>
            <v-card-text >
                <v-container fluid>
                <v-combobox
                clearable
                dense
                outlined
                :value="selectedItem"
                :items="items"
                :item-text="item => item.label.toUpperCase()"
                label="Type"
                filled
                ></v-combobox>
                </v-container>
                <v-text-field label="Username"/>
                <v-text-field label="Password" type="password"/>
            </v-card-text>
            <v-divider></v-divider>
            <v-card-actions>
               <v-btn color="green" nuxt to="/home" width="300" class="mx-auto mt-9">Login</v-btn> 
            </v-card-actions>
            
        </v-card>
    </v-content>
  </v-app>         
    </div>
</template>

<style scoped>

.bgr{
    background: url(../static/bgrd.png);
    background-size: cover;
    width: cover;
}
.trslc{
    border-radius: 10px;
    position: absolute;
    top: 50%;
    left: 50%;
    z-index: 999;
    text-align: center;
    padding: 60px 32px;
    width: 600px;
    transform: translate(-50%, -50%);
    background: rgba(255, 255, 255, 0.133);

    border: 1px solid #fff;
    backdrop-filter: blur(30px);
    box-shadow: 0 0 6px 0 rgba(29, 29, 29, 0.203);
}
</style>

<script>
export default{
    
}
</script>

<style>

</style>