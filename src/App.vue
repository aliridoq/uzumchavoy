<template>
    <header class="app-header">
    <TopHeader/>
    <navbar/>
  </header> 
  <div class="main-page-builder" data-v-36aa2aca="">
    <bannerblock/>
    <extendableofferwrapper/>
  </div>
</template>
<script>
import TopHeader from './components/TopHeader.vue'
import navbar from './components/navbar.vue'
import bannerblock from './components/bannerblock.vue'
import extendableofferwrapper from './components/extendableofferwrapper.vue'
export default {
  components: {
    TopHeader,
    navbar,
    bannerblock,
    extendableofferwrapper,
  }
}
</script>
<style scoped>
.app-header {
  margin-top:0px;
  font-family: Roboto, sans-serif;
  -webkit-font-smoothing: antialiased;
  ---transparent: hsla(0,0%,100%,0);
  --background-overlay-default: var(--black-a30);
  --background-overlay-blurred: var(--black-a20);
  --background-skeleton-onprimary: var(--gray-98);
  --background-skeleton-onsecondary: var(--white-a90);
  --background-primary: var(--white-a100);
  --background-secondary: var(--gray-96);
  --background-tertiary: var(--white-a100);
  --background-quaternary: var(--gray-96);
  --background-dark: var(--gray-15);
  --background-popover-default: var(--white-a100);
  --background-popover-defaultconstant: var(--white-a100);
  --background-popover-inverted: var(--gray-15);
  --background-popover-invertedconstant: var(--gray-15);
  --surface-primary-rest: var(--white-a100);
  --surface-primary-hovered: var(--gray-94);
  --surface-primary-pressed: var(--gray-91);
  --surface-primary-dark-rest: var(--gray-15);
  --surface-primary-dark-hovered: var(--gray-30);
  --surface-primary-dark-pressed: var(--gray-20);
  --surface-dark-default: var(--gray-15);
  --surface-dark-blurred: var(--gray-a80);
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  display: block;
  --header-primary-color: var(--text-accented);
  z-index: 2;
}
.main-page-builder{
  line-height: 1;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
}
</style>
