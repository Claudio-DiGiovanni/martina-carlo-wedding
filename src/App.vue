<template>
  <div>
    <headerPage />
    <usPage />
    <infoPage />
    <locationPage />
    <contactsPage />
    <footerPage />
  </div>
</template>

<script>
import headerPage from '@/components/header.vue';
import usPage from '@/components/usPage.vue';
import infoPage from '@/components/infoPage.vue';
import locationPage from '@/components/locationPage.vue';
import contactsPage from '@/components/contactsPage.vue';
import footerPage from '@/components/footerPage.vue';

export default {
  components: {
    headerPage,
    usPage,
    infoPage,
    locationPage,
    contactsPage,
    footerPage,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";

div{
  overflow: hidden;
}
</style>
