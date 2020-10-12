<template>
  <div>
    <b-card-group deck>
      <b-card
        title="Dead"
        img-src="https://image.tmdb.org/t/p/w342/eu40V59ULl92GIWfRGLAuzu5EYb.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>
          Enredo: Marbles, um drogado infeliz, pode ver fantasmas. Tagg, um
          aspirante recentemente morto super-policial, precisa encontrar um
          serial killer. Pode um policial fantasma crítico e um drogado sem rumo
          superar seus preconceitos e trabalhar juntos para salvar vidas – e as
          mortes?
        </b-card-text>
        <template v-slot:footer>
          <div>
            <b-button variant="success">Disponivel </b-button>
          </div>
        </template>
      </b-card>

      <b-card
        title="Escolhida"
        img-src="https://image.tmdb.org/t/p/w342/irkse1FMm9dWemwlxKJ7RINT9Iy.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>
          Veronica é uma autora bem sucedida que se encontra presa em dois
          diferentes períodos: Os dias atuais e o Antebellum, a era das
          plantações no sul. Imersa nesta horrorizante realidade, ela deve
          descobrir o mistério por trás desse acontecimentos e fugir, antes que
          seja tarde demais.
        </b-card-text>
        <template v-slot:footer>
          <div>
            <b-button variant="danger"> indisponível</b-button>
          </div>
        </template>
      </b-card>

      <b-card
        title="2067"
        img-src="https://image.tmdb.org/t/p/w342/7D430eqZj8y3oVkLFfsWXGRcpEG.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>
          Um grupo de humanos busca respostas no futuro após as florestas, vida
          selvagem e plantas do planeta serem devastados pela mudança climática.
        </b-card-text>
        <template v-slot:footer
          ><div>
            <b-button variant="success">Disponivel </b-button>
          </div>
        </template>
      </b-card>

      <b-card
        title="Morte Súbita 2"
        img-src="https://image.tmdb.org/t/p/w342/elZ6JCzSEvFOq4gNjNeZsnRFsvj.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>
          Jesse Freeman é um ex-oficial das forças especiais e especialista em
          explosivos agora trabalhando regularmente como segurança em uma arena
          de basquete de última geração. Problemas irromperem quando um grupo de
          terroristas sequestra o dono da equipe e a filha de Jesse durante a
          noite de estreia.
        </b-card-text>
        <template v-slot:footer>
          <div>
            <b-button variant="danger"> indisponível</b-button>
          </div>
        </template>
      </b-card>

      <b-card
        title="A Gangue: Uma Noite de Sangue "
        img-src="https://image.tmdb.org/t/p/w342/sxDoeVZBWVqaDpJ6NDh7SGPQvBK.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>
          A Wright Firm tem sinal verde para seu maior empreendimento até hoje:
          ‘O Projeto Grove Street’. Ao transformar um bairro atingido por crimes
          e pobreza por anos em um ambiente seguro e limpo, a empresa espera
          receber apoio e compreensão. Este não é o caso.
        </b-card-text>
        <template v-slot:footer
          ><div>
            <b-button variant="success">Disponivel </b-button>
          </div>
        </template>
      </b-card>
    </b-card-group>
  </div>
</template>

<script>
export default {
  name: 'card',
}
</script>
