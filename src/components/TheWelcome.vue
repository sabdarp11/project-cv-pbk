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
    <template #heading>Education</template>
    Informatics Engineering 
    <a href="https://vuejs.org/" target="_blank" rel="noopener">UIR (2022-2026)</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Project</template>

    Desingning a project in a <br>
    <a href="#" target="_blank" rel="noopener">Software Engineering</a>courses.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Tools</template>
    <a href="#" target="_blank" rel="noopener">Canva</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>About Me</template>
    My name is Fadhlan Ardanel Razaq, usually called Adan, I come from Pekanbaru. I am the first child of my 2 siblings, my hobby is playing futsal. Apart from playing futsal, I also like photography
    <a href="#" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>
Email:
    <a href="#" target="_blank" rel="noopener">FadhlanAR@gmail.com</a>
  </WelcomeItem>
</template>
