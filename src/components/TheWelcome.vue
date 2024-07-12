<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>O Que é ?</template>

    Vue’s
    <a href="https://vuejs.org/" target="_blank" rel="noopener">official documentation</a>
    O Vue.js é um framework JavaScript progressivo para construir interfaces de usuário. Ele facilita a criação de aplicativos web dinâmicos com uma arquitetura baseada em componentes reutilizáveis. Oferece uma curva de aprendizado suave e integra-se facilmente com outras bibliotecas ou projetos existentes.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Onde Usar ?</template>

    Você deve usar Vue.js em projetos web onde deseja criar interfaces de usuário interativas e dinâmicas, facilitando o desenvolvimento de componentes reutilizáveis e a gestão eficiente do estado da aplicação. É especialmente útil em aplicações que exigem atualizações de conteúdo em tempo real e manipulação direta do DOM de forma simplificada.
   

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Vantagens</template>
    Você deve usar Vue.js em projetos web onde deseja criar interfaces de usuário interativas e dinâmicas, facilitando o desenvolvimento de componentes reutilizáveis e a gestão eficiente do estado da aplicação. É especialmente útil em aplicações que exigem atualizações de conteúdo em tempo real e manipulação direta do DOM de forma simplificada.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Comunidade</template>

    A comunidade Vue oferece suporte através de fóruns como Vue Land, o servidor oficial no Discord, e StackOverflow. Recursos oficiais incluem Pinia para gerenciamento de estado, Vue Router para roteamento, Vue Test Utils para testes, e Vue Dev Tools para depuração. Inscreva-se na mailing list e siga @vuejs no Twitter para atualizações e novidades.
  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Como instalar</template>

    1. Usando o comando npm create vite@latest: <br>
 <code style="color:gainsboro">npm create vite@latest my-vue-app</code><br>
 Siga as instruções na linha de comando e escolha "Vue" quando solicitado. Isso criará um novo projeto Vue com Vite. 
 <br>
<code style="color: gainsboro;">cd my-vue-app
npm install
npm run dev
</code>
  
  </WelcomeItem>
</template>
