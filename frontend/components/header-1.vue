<template>
  <header>
    <div class="centered">
      <nav>
        <n-link to="/">Главная</n-link>
        <n-link to="/uslugi">Услуги</n-link>
        <n-link to="/keisi">Кейсы</n-link>
        <n-link to="/blog">Блог</n-link>
        <n-link to="/obo-mne">Контакты</n-link>
        <n-link to="/wiki">SEO энциклопедия</n-link>
      </nav>
      <div class="header-contacts">
        <div class="header-contacts-name">Машка Клюкина</div>
        <div class="header-contacts-phone">
          <a href="tel:14872834859">+1 487 283-48-59</a>
          <a href="mailto:kukina.m@gmail.com" target="_blank">
            kukina.m@gmail.com</a
          >
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header1',
}
</script>

<style></style>
