<template>
  <div>
    <Header />

    <v-container class="d-flex justify-center my-4">
      <div class="content">
        <div class="my-4" id="general">
          <h3 class="section-title">Visão geral</h3>

          <span class="section-text my-4">
            A Pineapple é uma empresa que oferece cursos de aprendizagem na área
            de tecnologia e linguas, visando formar novos profissionais
            qualificados para o mercado de trabalho.
          </span>

          <br />
          <br />

          <span class="section-text my-4">
            A pineapple oferece cursos de aprendizagem na área de tecnologia e
            linguas.
          </span>
        </div>

        <div class="my-4">
          <h3 class="section-subtitle">Perfeita para você</h3>

          <span class="section-text">
            A pineapple se preocupa com sua aprendizagem não só em termos de
            conhecimento, mas também de conforto para entender os conceitos de
            forma leve e concisa, dessa forma, absovendo melhor as ideias e
            termos passados.
          </span>
        </div>

        <v-img src="../assets/students1.jpg" class="image my-3"></v-img>

        <span class="image-legend ml-3">Para sua realidade</span>

        <br />
        <br />

        <div class="my-4">
          <h3 class="section-subtitle">Valores</h3>

          <span class="section-text">
            Nós seguimos uma série de valores que acreditamos que impulsiona o
            seu desenvolvimento.
          </span>
        </div>

        <div class="mb-6">
          <v-list>
            <v-list-item class="d-flex align-center">
              <v-icon class="mr-2" small color="#1E0E62">
                mdi-checkbox-blank-circle
              </v-icon>

              <v-list-item-content class="list-item-text">
                <v-list-item-title>
                  Acreditamos que todo conhecimento deve ser passado de forma
                  especifica para cada aluno.
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-list-item class="d-flex align-center">
              <v-icon class="mr-2" small color="#1E0E62">
                mdi-checkbox-blank-circle
              </v-icon>

              <v-list-item-content class="list-item-text">
                <v-list-item-title>
                  A ideia é que você esteja em um ambiente que se sinta
                  confortável o tempo todo.
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-list-item class="d-flex align-center">
              <v-icon class="mr-2" small color="#1E0E62">
                mdi-checkbox-blank-circle
              </v-icon>

              <v-list-item-content class="list-item-text">
                <v-list-item-title>
                  O bem estar no aprendizado é o mais importante, a nossa ideia
                  é que você se sinta bem enquanto aprende!
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-list>

          <span class="section-text mt-2">
            Para cada pesssoa, um método e métrica diferente, feito
            especialmente para você!
          </span>
        </div>

        <div id="prices">
          <PricingTable />
        </div>

        <v-divider class="my-6"></v-divider>

        <h3 class="section-title my-4" id="courses">Cursos</h3>

        <v-parallax
          style="width: 100%; border-radius: 20px"
          src="https://images.unsplash.com/photo-1521737711867-e3b97375f902?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxjb2xsZWN0aW9uLXBhZ2V8MXw0Nzg3Nzg2fHxlbnwwfHx8fA%3D%3D&w=1000&q=80"
        ></v-parallax>

        <v-card class="ma-4" elevation="0">
          <div class="my-4">
            <h3 class="section-subtitle">Combo Software</h3>

            <span class="section-text">
              Nesse curso você irá aprender a utilizar bem os sistemas
              operacionais (Windows e linux), desenvolvendo os conhecimentos
              adquiridos para otimizar seu aprendizado no curso de programação.
            </span>

            <div class="mb-6">
              <br />
              <strong> Para quem é esse curso? </strong>
              <v-list>
                <v-list-item class="d-flex align-center">
                  <v-icon class="mr-2" small color="#1E0E62">
                    mdi-checkbox-blank-circle
                  </v-icon>

                  <v-list-item-content class="list-item-text">
                    <v-list-item-title>
                      Para as pessoas que tem algum ou nenhum conhecimento de
                      sistemas operacionais e como usá-los e tem como objetivo
                      entrar no mercado de trabalho com a programação.
                    </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
            </div>
          </div>

          <div class="my-4">
            <h3 class="section-subtitle">Combo Técnico</h3>

            <span class="section-text">
              Nesse curso você irá aprender sobre a arquitetura de um
              computador, como montar e desmontar, além de entender como os
              componentes do computador se comportam. Como alguns sabem o
              conhecimento de outra língua é um diferencial, na área de
              tecnologia é indispensável, foi pensando nisso que nesse combo
              implementamos o inglês técnico.
            </span>

            <div class="mb-6">
              <br />
              <strong> Para quem é esse curso? </strong>
              <v-list>
                <v-list-item class="d-flex align-center">
                  <v-icon class="mr-2" small color="#1E0E62">
                    mdi-checkbox-blank-circle
                  </v-icon>

                  <v-list-item-content class="list-item-text">
                    <v-list-item-title>
                      Esse curso é designado para as pessoas que sempre tivera a
                      curiosidade de saber como um computador é montado e como o
                      sistema computacional funciona.
                    </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
            </div>
          </div>

          <div class="my-4">
            <h3 class="section-subtitle">Combo Redes</h3>

            <span class="section-text">
              No Curso de Infra de redes você irá adquirir diversas habilidades
              novas para acrescentar no seu currículo desde aprendera projetar
              até conhecer sobre padrões de cabeamento e protocolos de rede, sem
              falar do inglês técnico que vai ajudar muito na sua jornada no
              mundo da tecnologia.
            </span>

            <div class="mb-6">
              <br />
              <strong> Para quem é esse curso? </strong>
              <v-list>
                <v-list-item class="d-flex align-center">
                  <v-icon class="mr-2" small color="#1E0E62">
                    mdi-checkbox-blank-circle
                  </v-icon>

                  <v-list-item-content class="list-item-text">
                    <v-list-item-title>
                      Pra todos aqueles que sempre quiseram entender o que
                      realmente é a internet e como ela funciona. Se você já viu
                      projetos de interiores de casas, apartamentos e empresar e
                      se encantou, vai gostar mais ainda dos módulos de
                      infraestrutura onde você vai aprender a desenvolver as
                      plantas para seu projeto.
                    </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
            </div>
          </div>

          <div class="my-4">
            <h3 class="section-subtitle">Combo Design</h3>

            <span class="section-text">
              Nesse curso você irá aprender a utilizar bem os sistemas
              operacionais (Windows e linux) de maneira dedicada para otimizar
              seus futuros aprendizados no Design gráfico. Na parte de design
              você vai adquirir senso de estética e aprender as técnicas para
              colocar sua criatividade para trabalhar para você, a serviço das
              empresas.
            </span>

            <div class="mb-6">
              <br />
              <strong> Para quem é esse curso? </strong>
              <v-list>
                <v-list-item class="d-flex align-center">
                  <v-icon class="mr-2" small color="#1E0E62">
                    mdi-checkbox-blank-circle
                  </v-icon>

                  <v-list-item-content class="list-item-text">
                    <v-list-item-title>
                      Para as pessoas que tem algum ou nenhum conhecimento de
                      sistemas operacionais e como usá-los e querem entrar no
                      mercado de trabalho pelo Design gráfico. plantas para seu
                      projeto.
                    </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
            </div>
          </div>
        </v-card>

        <v-divider class="my-6"></v-divider>

        <div
          class="
            mt-8
            d-flex
            flex-column
            justify-center
            align-center
            text-center
          "
          id="witnesses"
        >
          <h3 class="section-title my-4">Testemunhos</h3>

          <v-icon x-large>mdi-format-quote-open-outline</v-icon>

          <v-carousel
            cycle
            :show-arrows="false"
            hide-delimiter-background
            delimiter-icon="mdi-minus"
            height="300"
          >
            <v-carousel-item v-for="(witness, index) in witnesses" :key="index">
              <span class="my-4 list-item-text">
                {{ witness.message }}
              </span>

              <div class="d-flex flex-column align-center justify-center">
                <v-img
                  :src="witness.image"
                  height="100"
                  width="100"
                  class="image-testimonial"
                ></v-img>

                <span class="mt-4 list-item-text">{{ witness.name }}</span>
                <span class="image-legend">Cherry</span>
              </div>
            </v-carousel-item>
          </v-carousel>
        </div>
      </div>
    </v-container>

    <Footer />
  </div>
</template>

<style scoped>
.content {
  margin-top: 40px;
  max-width: 70%;
}

.section-title {
  font-weight: bold;
  font-size: 42px;
  line-height: 52px;
  letter-spacing: -0.4px;
  color: #1e0e62;
}

.section-text {
  font-weight: normal;
  font-size: 16px;
  line-height: 26px;
  color: rgba(21, 20, 57, 0.4);
  mix-blend-mode: normal;
}

.section-subtitle {
  font-weight: 500;
  font-size: 22px;
  line-height: 32px;
  color: #1e0e62;
}

.image {
  border-radius: 20px;
}

.image-legend {
  font-weight: bold;
  font-size: 14px;
  line-height: 26px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: rgba(21, 20, 57, 0.4);
  mix-blend-mode: normal;
}

.list-item-text {
  font-weight: 500;
  font-size: 18px;
  line-height: 28px;

  color: #1e0e62;
}

.image-testimonial {
  background: #ccc5;
  border-radius: 50%;
}

@media (max-width: 500px) {
  .content {
    max-width: 90%;
  }
}
</style>

<script>
import Header from "./components/header";
import PricingTable from "./components/pricing-table";
import Footer from "./components/footer";

export default {
  name: "Home",

  components: {
    Header,
    PricingTable,
    Footer,
  },

  data: () => ({
    witnesses: [
      {
        name: "João Cruzick",
        message:
          "Minha experiência nos cursos da pineapple foram muito satisfatórias, sempre fazia questão de me despedir dos professores no fim das aulas",
        image: require("../assets/joao.png"),
      },
      {
        name: "David Alvez",
        message:
          "Minha paixão por servidores e informatica me fez chegar aos curos da pineapple, logo me inscrevi com o Combo Redes e aproveitei cada parte da aprendizagem",
        image: require("../assets/davi.jpeg"),
      },
    ],
  }),
};
</script>
