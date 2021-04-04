<template>
  <v-container fluid style="margin: 0; padding: 0">
    <v-row>
      <v-col class="bg-banner">
        <v-img
          :src="require('../../assets/logo2.jpg')"
          style="margin-left: auto; margin-right: auto"
          class="img-fluid"
          max-height="500"
          max-width="600"
        ></v-img>
      </v-col>
    </v-row>
    <v-container class="mtp">
      <v-row>
        <v-col
          class="d-flex align-end justify-center flex-column"
          md="5"
          sm="12"
        >
          <h1></h1>
          <p class="teste1">
            <b class="h1">Um jeito fácil de se comunicar.</b> <br />
            Aqui ficará uma breve descrição sobre os problemas. Aqui ficará uma
            breve descrição sobre os problemas. Aqui ficará uma breve descrição
            sobre os problemas. Aqui ficará uma breve descrição sobre os
            problemas.
          </p>
        </v-col>
        <v-col md="7" sm="12">
          <v-img
            :src="require('../../assets/header.jpg')"
            style="margin-left: auto; margin-right: auto"
            class="img-fluid"
            max-height="500"
            max-width="600"
          ></v-img>
        </v-col>
      </v-row>
      <v-row class="mtp">
        <v-col md="7" sm="12">
          <v-img
            :src="require('../../assets/deafness-1.jpg')"
            style="margin-left: auto; margin-right: auto"
            class="img-fluid"
            max-height="500"
            max-width="600"
          ></v-img>
        </v-col>
        <v-col
          class="d-flex align-end justify-center flex-column"
          md="5"
          sm="12"
        >
          <h1></h1>
          <p class="teste1">
            <b class="h1">Um jeito fácil de se comunicar.</b> <br />
            Aqui ficará uma breve descrição sobre os problemas. Aqui ficará uma
            breve descrição sobre os problemas. Aqui ficará uma breve descrição
            sobre os problemas. Aqui ficará uma breve descrição sobre os
            problemas.
          </p>
        </v-col>
      </v-row>
    </v-container>
    <v-container fluid style="background-color: #eaf3fa">
      <v-row class="mt-16">
        <v-col>
          <v-card class="mx-auto" max-width="344">
            <v-img
              :src="require('../../assets/19198752.jpg')"
              style="margin-left: auto; margin-right: auto"
              class="img-fluid"
            ></v-img>
            <v-card-text>
              <p class="display-1 text--primary">be•nev•o•lent</p>
              <p>adjective</p>
              <div class="text--primary">
                well meaning and kindly.<br />
                "a benevolent smile"
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn text color="deep-purple accent-4"> Learn More </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col>
          <v-card class="mx-auto" max-width="344">
            <v-img
              :src="require('../../assets/Wavy_Ppl-06_Single-11.jpg')"
              style="margin-left: auto; margin-right: auto"
              class="img-fluid"
            ></v-img>
            <v-card-text>
              <div>Word of the Day</div>
              <p class="display-1 text--primary">be•nev•o•lent</p>
              <p>adjective</p>
              <div class="text--primary">
                well meaning and kindly.<br />
                "a benevolent smile"
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn text color="deep-purple accent-4"> Learn More </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col>
          <v-card class="mx-auto" max-width="344">
            <v-img
              :src="require('../../assets/Wavy_Ppl-12_Single-02.jpg')"
              style="margin-left: auto; margin-right: auto"
              class="img-fluid"
            ></v-img>
            <v-card-text>
              <div>Word of the Day</div>
              <p class="display-1 text--primary">be•nev•o•lent</p>
              <p>adjective</p>
              <div class="text--primary">
                well meaning and kindly.<br />
                "a benevolent smile"
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn text color="deep-purple accent-4"> Learn More </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
    <v-container class="mtp">
      <v-row>
        <v-col
          class="d-flex align-end justify-center flex-column"
          md="5"
          sm="12"
        >
          <h1></h1>
          <p class="teste1">
            <b class="h1">Um jeito fácil de se comunicar.</b> <br />
            Aqui ficará uma breve descrição sobre os problemas. Aqui ficará uma
            breve descrição sobre os problemas. Aqui ficará uma breve descrição
            sobre os problemas. Aqui ficará uma breve descrição sobre os
            problemas.
          </p>
        </v-col>
        <v-col md="7" sm="12">
          <v-img
            :src="require('../../assets/5014802.jpg')"
            style="margin-left: auto; margin-right: auto"
            class="img-fluid"
            max-height="500"
            max-width="500"
          ></v-img>
        </v-col>
      </v-row>
      <v-row class="mtp">
        <v-col md="7" sm="12">
          <v-img
            :src="require('../../assets/5032757.jpg')"
            style="margin-left: auto; margin-right: auto"
            class="img-fluid"
            max-height="500"
            max-width="500"
          ></v-img>
        </v-col>
        <v-col
          class="d-flex align-end justify-center flex-column"
          md="5"
          sm="12"
        >
          <h1></h1>
          <p class="teste1">
            <b class="h1">Um jeito fácil de se comunicar.</b> <br />
            Aqui ficará uma breve descrição sobre os problemas. Aqui ficará uma
            breve descrição sobre os problemas. Aqui ficará uma breve descrição
            sobre os problemas. Aqui ficará uma breve descrição sobre os
            problemas.
          </p>
        </v-col>
      </v-row>
    </v-container>
    <v-container class="d-flex justify-center" fluid style="background-color: #a0b9cf">
      <v-carousel v-model="model" height="200"  :hide-delimiter-background="true" :hide-delimiters="true" style="max-width: 800px;">
        <v-carousel-item v-for="avatar in avatares" :key="avatar.id"  >
          <v-sheet style="height: 200px;" color="#a0b9cf" >
            <v-row  align="center" justify="center"  style="height: 200px; width: 100%;" class="px-16">
              <v-list color="#a0b9cf">
                <v-list-item style="text-align: center;">{{avatar.menssagem}}</v-list-item>
                <v-list-item>
                  <v-list-item-avatar size="70">
                    <v-img
                      :src="avatar.img"                      
                    ></v-img>
                  </v-list-item-avatar>
                  <v-list-item-content>                    
                    <v-list-item-title>{{avatar.nome}}</v-list-item-title>
                    <v-list-item-subtitle>{{avatar.cargo}}</v-list-item-subtitle>
                  </v-list-item-content>                  
                </v-list-item>
              </v-list>              
            </v-row>
          </v-sheet>
        </v-carousel-item>
      </v-carousel>
    </v-container>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    model: 0,
    avatares: [
        {id: 1, nome: 'John Leider', cargo: 'Gerente de Projetos', img: 'https://cdn.vuetifyjs.com/images/john.png',  menssagem: "bla bla bla.bla bla bla.bla bla bla.bla bla bla.bla bla bla.bla bla.bla bla.bla bla.bla bla.bla bla.bla bla.bla bla.bla bla.bla bla.bla bla." },
        {id: 2, nome: 'Roger Kruhm', cargo: 'Analista de Sistemas', img: 'https://avatars0.githubusercontent.com/u/9064066?v=4&s=460',  menssagem: "bla bla bla bla blu." },
        {id: 3, nome: 'Louise Lagradge', cargo: 'Corretora', img: 'https://image.freepik.com/fotos-gratis/mulher-moderna-tomando-uma-selfie_23-2147893976.jpg',  menssagem: "bla bla bla bla blu." },        
      ],
  }),
};
</script>
<style>
.teste1 {
  width: 100%;
}
.h1 {
  font-size: 40px;
}
.bg-banner {
  background-color: #a0b9cf;
}
.mtp {
  margin-top: 200px !important;
}
</style>