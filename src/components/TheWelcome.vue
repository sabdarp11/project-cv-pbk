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
    <a href="https://vuejs.org/" target="_blank" rel="noopener">Islamic University Of Riau (2022-2026)</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Project</template>

    Once created a website as a substitute for UTS and UAS in<br>
    <a href="#" target="_blank" rel="noopener">Web Programming</a>courses. and created a website-based project called 
    <a href="#" target="_blank" rel="noopener">Lungo,</a>in the
    <a href="#" target="_blank" rel="noopener">Software Engineering</a>courses
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Expertise</template>
    <a href="#" target="_blank" rel="noopener">Python</a>,
    <a href="#" target="_blank" rel="noopener">Java</a>,
    <a href="#" target="_blank" rel="noopener">SQL</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Languages</template>

    Indonesia
    <a href="#" target="_blank" rel="noopener">100%</a><br>English
    <a href="#" target="_blank" rel="noopener"
      >50%</a
    >.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>
Email:
    <a href="#" target="_blank" rel="noopener">sabdarp@gmail.com</a>
  </WelcomeItem>
</template>
