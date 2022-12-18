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
    <template #heading>Документация</template>

    Vue’s
    <a target="_blank" href="https://vuejs.org/">официальная документация
    </a>
    предоставляет вам всю информацию, необходимую для начала работы.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Набор инструментов</template>

    Этот проект обслуживается и поставляется в комплекте с
    <a href="https://vitejs.dev/guide/features.html" target="_blank">Vite</a>. Рекомендованая IDE
    установить <a href="https://code.visualstudio.com/" target="_blank">VSCode</a> +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>. Если вам нужно протестировать
    свои компоненты и веб-страницы, ознакомьтесь
    <a href="https://www.cypress.io/" target="_blank">Cypress</a> and
    <a href="https://docs.cypress.io/guides/component-testing/introduction" target="_blank"
      >Cypress Component Testing</a
    >.

    <br />

    Дополнительные инструкции доступны в <code>README.md</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Экосистема</template>

    Получите официальные инструменты и библиотеки для вашего проекта:
    <a target="_blank" href="https://pinia.vuejs.org/">Pinia</a>,
    <a target="_blank" href="https://router.vuejs.org/">Vue Router</a>,
    <a target="_blank" href="https://test-utils.vuejs.org/">Vue Test Utils</a>, and
    <a target="_blank" href="https://github.com/vuejs/devtools">Vue Dev Tools</a>. Если вам нужно больше
    ресурсов, мы предлагаем оплатить
    <a target="_blank" href="https://github.com/vuejs/awesome-vue">Потрясающий Vue</a>
    визит.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Сообщество</template>

    Застрял? Задайте свой вопрос на
    <a target="_blank" href="https://chat.vuejs.org">Vue Land</a>, наш официальный сервер Discord, или
    <a target="_blank" href="#">Стековый поток</a>.
    Вы также должны подписаться на
    <a target="_blank" href="https://news.vuejs.org">наш список рассылки</a> и следуйте официальному
    <a target="_blank" href="https://twitter.com/vuejs">@vuejs</a>
    аккаунт в Твиттере для получения последних новостей в мире Vue
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    Как независимый проект, Vue полагается на поддержку сообщества для обеспечения своей устойчивости. Вы можете помочь
    нам,
    <a target="_blank" href="https://vuejs.org/sponsor/">стать спонсором</a>.
  </WelcomeItem>
</template>
