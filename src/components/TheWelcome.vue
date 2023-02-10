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
      <DocumentationIcon/>
    </template>
    <template #heading>Teamleden</template>

    De
    <a href="https://app.teambeheer.nl/feeds/31/22-23/team/8198" target="_blank" rel="noopener">spelers</a>
    van 'Barretje 1' vind je hier.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon/>
    </template>
    <template #heading>Uitslagen</template>

    'Barretje 1' gooit in de
    <a href="https://acdcdarts.nl/" target="_blank" rel="noopener">Arnhem Centrum Dart Competitie</a>.

    <br />
    Hier vind je de
    <a href="https://app.teambeheer.nl/feeds/31/22-23/team/8198#matches" target="_blank">uitslagen</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon/>
<!--      <EcosystemIcon/>-->
    </template>
    <template #heading>Boekjes</template>

    Hier vind je de
    <a href="https://app.teambeheer.nl/feeds/31/22-23/team/8198#sr" target="_blank" rel="noopener">boekjes</a>
    (bijzondere individuele resultaten).
  </WelcomeItem>

<!--  <WelcomeItem>-->
<!--    <template #icon>-->
<!--      <CommunityIcon/>-->
<!--    </template>-->
<!--    <template #heading>Community</template>-->

<!--    Got stuck? Ask your question on-->
<!--    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>, our official-->
<!--    Discord server, or-->
<!--    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"-->
<!--    >StackOverflow</a-->
<!--    >. You should also subscribe to-->
<!--    <a href="https://news.vuejs.org" target="_blank" rel="noopener">our mailing list</a> and follow-->
<!--    the official-->
<!--    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">@vuejs</a>-->
<!--    twitter account for latest news in the Vue world.-->
<!--  </WelcomeItem>-->

<!--  <WelcomeItem>-->
<!--    <template #icon>-->
<!--      <SupportIcon/>-->
<!--    </template>-->
<!--    <template #heading>Support Vue</template>-->

<!--    As an independent project, Vue relies on community backing for its sustainability. You can help-->
<!--    us by-->
<!--    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.-->
<!--  </WelcomeItem>-->
</template>
