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
        <v-col>
          <v-card class="mx-auto" color="#EAF3FA">
            <v-card-text>
              <v-row>
                <v-col>
                  <v-card-title class="h1">Um pouco sobre nós</v-card-title>
                  <v-spacer></v-spacer>
                  <v-card-text style="font-size: 25px; line-height: 1.2">
                    O projeto Hear-me surgiu-se da necessidade de algumas
                    pessoas com deficiência auditiva e de fala. Visando ajudar
                    essas pessoas e milhares de outras, nas quais passam
                    diariamente por dificuldades de comunicação, decidimos
                    uni-las com pessoas que saibam falar a lingua de sinais.
                    Através de um aplicativo, além de incentivar as pessoas a
                    ajudarem umas as outras, abrimos a oportunidade de gerar
                    grandes amizades. Nossa missão é garantir que todas as
                    pessoas tenham a facilidade de se comunicarem umas com as
                    outras, independente de seus obstaculos.
                  </v-card-text>
                </v-col>
                <v-col>
                  <v-card-text>
                    <v-img
                      :src="require('../../assets/history.jpg')"
                      style="margin-left: auto; margin-right: auto"
                      class="img-fluid rounded-circle"
                      max-height="500"
                      max-width="500"
                    ></v-img>
                  </v-card-text>
                </v-col>
              </v-row>
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-col
          class="d-flex align-end justify-center flex-column"
          md="5"
          sm="12"
        >
          <h1></h1>
          <p class="teste1">
            <b class="h1">A comunicação é um direito de todos!</b> <br />
          </p>

          <p style="font-size: 24px">
            Não tenha mais medo de se comunicar. Nós iremos garantir a você, a
            possibilidade de encontrar com pessoas que saibam a linguagem de
            sinais sem dificuldades. Podendo marcar encontros em nosso
            aplicativo.
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
          </p>

          <p style="font-size: 24px">
            Nosso publico alvo são as pessoas que possuem deficiência de fala e
            auditiva, bem como pessoas que saibam falar a linguagem de sinais.
            Com a união dessas pessoas, garantimos a comunicação basica do seu
            dia a dia. Seja com um atendente em um banco, ou uma consulta
            médica, ou até mesmo em um supermercado
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
              <p class="display-1 text--primary">Encontros virtuais</p>
              <div class="text--primary">
                Não podem se encontrar presencialmente? Não se preocupe, com a
                nossa tecnologia, permitiremos que você faça o contato
                totalmente online através da camera do celular o tablet.
              </div>
            </v-card-text>
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
              <p class="display-1 text--primary">Suporte 24HS</p>
              <div class="text--primary">
                Caso tenha alguma emergência referente a comunicação, você
                poderá contar com nosso suporte 24 horas, no qual iremos
                garantir toda a assistência necessária.
              </div>
            </v-card-text>
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
              <p class="display-1 text--primary">Tradutor Amigo</p>
              <div class="text--primary">
                O processo de comunicação, se dará com a ajuda de seu
                acompanhante, no qual você agendou o encontro pelo nosso
                aplicativo. Sendo o mesmo responsável por realizar a tradução
                para quem não entende a linguagem de sinais.
              </div>
            </v-card-text>
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
          <p class="teste1"><b class="h1">Xô COVID!!</b> <br /></p>

          <p style="font-size: 24px">
            Aqui o Corona Vírus não tem vez. Verificamos se ambos os usuários
            estão devidamente protegidos. Fazendo uma verificação com a câmera,
            além de orientações sobre os cuidados da COVID. Assim, você poderá
            realizar os encontros de forma segura e tranquila.
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
          <p class="teste1"><b class="h1">Suporte Eficiente</b> <br /></p>

          <p style="font-size: 24px">
            Problemas para acessar o aplicativo? Dúvidas ou dificuldades? Sem
            problemas, nosso suporte estará a sua disposição para qualquer
            eventualidade. Seja para sanar suas dúvidas ou corrigir algum erro.
          </p>
        </v-col>
      </v-row>
    </v-container>
    <v-container
      class="d-flex justify-center"
      fluid
      style="background-color: #a0b9cf"
    >
      <v-carousel
        v-model="model"
        height="200"
        :hide-delimiter-background="true"
        :hide-delimiters="true"
        style="max-width: 800px"
      >
        <v-carousel-item v-for="avatar in avatares" :key="avatar.id">
          <v-sheet style="height: 200px" color="#a0b9cf">
            <v-row
              align="center"
              justify="center"
              style="height: 200px; width: 100%"
              class="px-16"
            >
              <v-list color="#a0b9cf">
                <v-list-item style="text-align: center">{{
                  avatar.menssagem
                }}</v-list-item>
                <v-list-item>
                  <v-list-item-avatar size="70">
                    <v-img :src="avatar.img"></v-img>
                  </v-list-item-avatar>
                  <v-list-item-content>
                    <v-list-item-title>{{ avatar.nome }}</v-list-item-title>
                    <v-list-item-subtitle>{{
                      avatar.cargo
                    }}</v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
            </v-row>
          </v-sheet>
        </v-carousel-item>
      </v-carousel>
    </v-container>
    <v-container class="mtp">
      <v-snackbar
      v-model="snackbar"
      shaped  
      relative
      right
      top
      min-width="22%"
      height="5%"
      color="#a0b9cf"
    >
      <span>Mensagem Enviada!</span>
      <v-icon dark>
        mdi-checkbox-marked-circle
      </v-icon>
    </v-snackbar>
      <v-form ref="form" @submit.prevent="submit">
        <v-row justify="center">
          <v-col cols="12" sm="10" md="8" lg="6">
            <v-card
              class="d-flex flex-column align-center"
              rounded
              style="border: 1px solid #a0b9c7"
            >
              <v-card-title style="color: #a0b9c7">Contate-nos</v-card-title>
              <v-text-field
                v-model="form.nome"
                color="#a0b9cf"
                label="Nome"
                :rules="rules.nome"
                placeholder="Informe seu nome"
                outlined
                shaped
                style="width: 60%"
              ></v-text-field>
              <v-text-field
                v-model="form.sobrenome"
                color="#a0b9cf"
                label="Sobrenome"
                :rules="rules.sobrenome"
                placeholder="Informe seu sobrenome"
                outlined
                shaped
                style="width: 60%"
              ></v-text-field>
              <v-text-field
                v-model="form.email"
                color="#a0b9cf"
                label="E-mail"
                :rules="rules.email"
                placeholder="Informe seu email"
                outlined
                shaped
                style="width: 60%"
              ></v-text-field>
              <v-textarea
                v-model="form.mensagem"
                color="#a0b9cf"
                label="mensagem..."
                :rules="rules.mensagem"
                outlined
                shaped
                style="width: 60%"
                row-height="30"
                no-resize
              ></v-textarea>
              <v-btn
                depressed
                color="#a0b9cf"
                min-width="20%"
                class="ma-2"
                :disabled="!formIsValid"
                type="submit"
                               
              >
                <span style="color: #FFF;">Enviar</span>
              </v-btn>
            </v-card>
          </v-col>
        </v-row>
      </v-form>
    </v-container>
    <v-footer dark padless class="mtp">
      <v-card class="flex" flat tile>
        <v-card-title style="background-color: #a0b9c7">
          <strong class="subheading"
            >Sigam as nossas redes sociais para novidades!</strong
          >

          <v-spacer></v-spacer>

          <v-btn v-for="icon in icons" :key="icon" class="mx-4" dark icon>
            <v-icon size="24px">
              {{ icon }}
            </v-icon>
          </v-btn>
        </v-card-title>
      </v-card>
    </v-footer>
  </v-container>
</template>

<script>
export default {
  data () {

    const defaultForm = Object.freeze({
      nome: "",
      sobrenome: "",
      email: "",
      mensagem: "",
    })

    return {
      model: 0,
      avatares: [
        {
          id: 1,
          nome: "John Leider",
          cargo: "Gerente de Projetos",
          img: "https://cdn.vuetifyjs.com/images/john.png",
          menssagem:
            "Incrível como um simples aplicativo poderá transformar a vida de muitas pessoas. Não me arrependo de ter investido neste projeto",
        },
        {
          id: 2,
          nome: "Roger Kruhm",
          cargo: "Analista de Sistemas",
          img: "https://avatars0.githubusercontent.com/u/9064066?v=4&s=460",
          menssagem:
            "Ja desenvolvi muitos aplicativos, porém nunca imaginei algo desse tipo. Acredito no potencial da Hear-me",
        },
        {
          id: 3,
          nome: "Louise Lagradge",
          cargo: "Corretora",
          img:
            "https://image.freepik.com/fotos-gratis/mulher-moderna-tomando-uma-selfie_23-2147893976.jpg",
          menssagem:
            "Ja atendi clientes com deficiência auditiva e sei o quanto é importante a comunicação. Como Steakholder, acredito no potencial da Hear-me.",
        },
      ],
      form: {
        nome: "",
        sobrenome: "",
        email: "",
        mensagem: "",
      },
      icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
      snackbar: false,
      defaultForm,
      rules: {          
          nome: [val => (val || '').length > 0 || 'Campo nome obrigatório!'],
          sobrenome: [val => (val || '').length > 0 || 'Campo sobrenome obrigatório!'],
          email: [val => (val || '').length > 0 || 'Campo email obrigatório!'],
          mensagem: [val => (val || '').length > 0 || 'Campo mensagem obrigatório!'],
        },
    }
  },

  computed: {
      formIsValid () {
        return (
          this.form.nome &&
          this.form.sobrenome &&
          this.form.email &&
          this.form.mensagem
        )
      },
    },

  methods: {
      resetForm () {
        this.form = Object.assign({}, this.defaultForm)
        this.$refs.form.reset()
      },
      submit () {
        this.snackbar = true
        this.resetForm()
      },
    },  
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