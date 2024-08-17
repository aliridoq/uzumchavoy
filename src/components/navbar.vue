<template>
  <div data-v-3a87e086="" class="suggestion-priority">
    <div data-v-3a87e086="" class="ui-wrapper">
      <div
        data-v-3a87e086=""
        id="mhrc-header"
        class="middle-header row center between-mbs middle-mbs noselect"
      >
        <navbarlogo/>
        <katalog/>
        <qidiruv/>
        <actionknopka/>
      </div>
      <fastpast/>
    </div>
    <div
      data-v-5608b972=""
      data-v-3a87e086=""
      class="catalog-transition"
      style="display: none"
    > 
      <div data-v-5608b972="" class="wrapper-transition"><!----></div>
      <!---->
    </div>
    <div
      data-v-5608b972=""
      data-v-3a87e086=""
      class="catalog-transition"
      style="display: none"
    >
      <div data-v-5608b972="" class="wrapper-transition"><!----></div>
      <!---->
    </div>
  </div>
</template>
<script>
import navbarlogo from './navbarLogo.vue'
import katalog from './katalog.vue'
import qidiruv from './qidiruv.vue'
import actionknopka from './actionknopka.vue'
import fastpast from './fastpast.vue'
export default {
  components: {
    navbarlogo,
    katalog,
    qidiruv,
    actionknopka,
    fastpast,
  }
}
</script>

<style>
.suggestion-priority {
  box-sizing: border-box;
  margin: 0;
  border: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  background-color: #fff;
  box-shadow: none;
  padding: 17px 0 0;
  position: relative;
  transition: transform 0.3s ease, margin 0.05s linear,
    -webkit-transform 0.3s ease;
  width: 100%;
  z-index: 2;
}
.ui-wrapper {
  box-sizing: border-box;
  padding: 0;
  border: 0;
  font-size: 100%;
  vertical-align: baseline;
  outline: none;
  font-style: inherit;
  margin: 0 auto;
  max-width: 1240px;
  min-width: 320px;
  width: 95%;
}
#mhrc-header{
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    text-align: center;
    user-select: none;
    -webkit-box-flex: 0;
    -webkit-box-direction: normal;
    box-sizing: border-box;
    display: flex;
    flex: 0 1 auto;
    flex-direction: row;
    flex-wrap: wrap;
    -webkit-box-orient: horizontal;
    -webkit-box-align: center;
    align-items: center;
    -webkit-box-pack: justify;
    justify-content: space-between;
    margin: 0;
    position: relative;
    width: 100%;
}
.middle-header-main-logo{
    text-align: center;
    user-select: none;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    -webkit-box-align: center;
    align-items: center;
    display: flex;
}

#uzumlogo{
    text-align: center;
    user-select: none;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    text-decoration: none;
    -webkit-box-align: center;
    align-items: center;
    display: flex;
    margin-left: 0;
    margin-right: 32px;
    color:#1f2026;;
    font-weight: 500; 
}
.ui-icon.logo{
    text-align: center;
    user-select: none;
    font-size: 100%;
    font-style: inherit;
    color: #1f2026;
    font-weight: 500;
    fill: none;
    box-sizing: border-box;
    outline: 0;
    border: 0;
    height: 32px;
    width: 215px;
}
#catalog-button{
    user-select: none;
    box-sizing: border-box;
    outline: 0;
    margin: 0;
    align-items: center;
    align-self: center;
    border: none;
    cursor: pointer;
    display: inline-flex;
    justify-content: center;
    text-decoration: none;
    transition: all .2s;
    background-color:#e5e5ff;
    border-radius: 4px;
    color: #7f4dff ;
    height: 40px!important;
    margin-right: 7px;
    width: 120px;
    --border-radius: 10px;
    column-gap: 6px;
    font-family: Inter;
    font-size: 14px;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    padding: 0 12px;
    text-align: center;
}
#catalog-button:hover{
    user-select: none;
    box-sizing: border-box;
    outline: 0;
    margin: 0;
    --bg-color: transparent;
    --color: #4b4a50;
    align-items: center;
    align-self: center;
    border: none;
    cursor: pointer;
    display: inline-flex;
    justify-content: center;
    text-decoration: none;
    transition: all .2s;
    border-radius: 4px;
    color: #7f4dff;
    height: 40px!important;
    margin-right: 7px;
    width: 120px;
    --border-radius: 10px;
    column-gap: 6px;
    font-family: Inter;
    font-size: 14px;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    padding: 0 12px;
    text-align: center;
    background: #ceccff;
}
.slot.default{
    user-select: none;
    cursor: pointer;
    color: #7f4dff ;
    border-radius: 10px;
    font-family: Inter;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    text-align: center;
    box-sizing: border-box;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    align-items: center;
    display: flex;
    height: 100%;
    margin: 0 4px;
}
.slot.default:hover{
    user-select: none;
    --bg-color: transparent;
    cursor: pointer;
    color: 7f4dff;
    --border-radius: 10px;
    font-family: Inter;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    text-align: center;
    box-sizing: border-box;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    align-items: center;
    display: flex;
    height: 100%;
    margin: 0 4px;
}
.catalog-icon{
    user-select: none;
    color: #7f4dff;
    --border-radius: 10px;
    font-family: Inter;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    text-align: center;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    cursor: pointer;
    height: 24px;
    position: relative;
    width: 24px;
    margin-right: 8px;
}
#rectvoy{
    user-select: none;
    --bg-color: transparent;
    --color:#4b4a50;
    color:#7f4dff;
    --border-radius: 10px;
    font-family: Inter;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    text-align: center;
    --out: #eaeaf9;
    margin: 0;
    padding: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    cursor: pointer;
    background: #7f4dff;
    border: 2px solid #7f4dff;
    border-radius: 2px;
    box-sizing: border-box;
    height: 12px;
    left: 50%;
    position: absolute;
    top: 9px;
    transform: translate(-50%);
    transition: all .11s ease-out .11s,transform .11s ease-out .001ms,-webkit-transform .11s ease-out .001ms;
    width: 18px;
}
.inner{
    user-select: none;
    --bg-color: transparent;
    --color: #4d4f59;
    color: #7f4dff;
    --border-radius: 10px;
    font-family: Inter;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    text-align: center;
    --out: #eaeaf9;
    box-sizing: border-box;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    cursor: pointer;
    background-color: #e5e5ff ;
    border-radius: 1px;
    height: 100%;
    margin: auto;
    transition: all .11s ease-out .11s;
    width: 100%;
}
.top-cat{
    user-select: none;
    --bg-color: transparent;
    --color: #4b4a50;
    color: #7f4dff;
    --border-radius: 10px;
    font-family: Inter;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    text-align: center;
    --out: #eaeaf9;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    cursor: pointer;
    border-top: 2px solid #7f4dff;
    border-top-left-radius: 2px;
    border-top-right-radius: 2px;
    height: 0;
    left: 50%;
    position: absolute;
    transform: translate(-50%);
    top: 3px;
    transition: all .11s ease-out .11s,opacity .001ms .11s;
    width: 13.991999999999999px;
}
.bottom-cat{
    user-select: none;
    --bg-color: transparent;
    --color: #4b4a50;
    color: #7f4dff;
    --border-radius: 10px;
    font-family: Inter;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    text-align: center;
    --out: #eaeaf9;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    cursor: pointer;
    background: #7f4dff;
    top: 6px;
    transition: all .11s ease-out .11s,transform .11s ease-out .001ms,-webkit-transform .11s ease-out .001ms;
    width: 15.984000000000002px;
    border-top: 2px solid #7f4dff;
    border-top-left-radius: 2px;
    border-top-right-radius: 2px;
    height: 0;
    left: 50%;
    position: absolute;
    transform: translate(-50%);
}



.search-header-parts{
    text-align: center;
    user-select: none;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    align-items: center;
    display: flex;
    flex-grow: 1;
}


.search-form{
    text-align: center;
    user-select: none;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    border-radius: 2px;
    display: flex;
    transition: border .1s ease;
    flex-grow: 1;
    font-family: Inter,sans-serif;
    margin-right: 24px;
    position: relative;
}


.search-input-component{
    text-align: center;
    user-select: none;
    font-family: Inter,sans-serif;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    border-radius: 0 4px 4px 0;
    width: 100%;
    height: 40px;
}

.input-line{    
    text-align: center;
    user-select: none;
    font-family: Inter,sans-serif;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    height: 100%;
    width: 100%;
}

#search-icon{
    text-align: center;
    user-select: none;
    font-family: Inter,sans-serif;
    font-size: 100%;
    font-style: inherit;
    width: 20;
    height: 20;
    fill: none;
    box-sizing: border-box;
    outline: 0;
    border: 0;
    display: none;
}

.default-input{
    user-select: none;
    box-sizing: border-box;
    background:#fff;
    border: 1px solid rgba(54,55,64,.2);
    border-radius: 4px;
    box-shadow: 0 0 0 0 rgba(54,55,64,.2),0 0 0 0 rgba(54,55,64,.08);
    color: var(--text-primary);
    font-family: Inter,sans-serif;
    font-size: .875rem;
    font-weight: 400;
    height: 100%;
    margin: 0;
    outline: none;
    padding: 0 calc(15% + 38px) 0 16px;
    transition: box-shadow .2s ease;
    vertical-align: top;
    width: 100%;
}
#suggests-block-list{
    text-align: center;
    font-family: Inter,sans-serif;
    margin: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    overflow-y: auto;
    scrollbar-width: none;
    user-select: none;
    transform: translateZ(0);
    background-color: #fff;
    border-radius: 0 0 12px 12px;
    box-sizing: border-box;
    left: 0;
    opacity: 1;
    position: absolute;
    right: 0;
    top: 100%;
    transition: all .4s;
    z-index: 10;
    border: 1px solid #fff;
    border-top: none;
    box-shadow: none;
    max-height: 0;
    padding: 0;
}

.blocks{
    text-align: center;
    font-family: Inter,sans-serif;
    user-select: none;
    box-sizing: border-box;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    list-style: none;
    margin: 0;
}


#searchcha{
    user-select: none;
    outline: 0;
    -webkit-box-flex: 0;
    -webkit-box-direction: normal;
    box-sizing: border-box;
    flex: 0 1 auto;
    flex-direction: row;
    flex-wrap: wrap;
    -webkit-box-orient: horizontal;
    -webkit-box-pack: center;
    --bg-color: transparent;
    align-items: center;
    align-self: center;
    color: #4b4a50;
    cursor: pointer;
    justify-content: center;
    text-decoration: none;
    display: block;
    background: #edeff2;
    border: 1px solid rgba(54,55,64,.2);
    border-left-width: 0;
    border-radius: 0 4px 4px 0;
    margin: 0;
    transition: background-color .1s ease;
    --border-radius: 10px;
    column-gap: 6px;
    font-family: Inter;
    font-size: 14px;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    padding: 0 12px;
    text-align: center;
    height: 100%;
    position: absolute;
    right: 0;
    top: 0;
    width: 15%;
    z-index: 1;
}

.slotdefault{
    user-select: none;
    --bg-color: transparent;
    color: var(#4d4f59);
    cursor: pointer;
    --border-radius: 10px;
    font-family: Inter;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    text-align: center;
    box-sizing: border-box;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    align-items: center;
    display: flex;
    height: 100%;
    margin: 0 4px;
}

.ui-icon.magnifying-glass{
    user-select: none;
    --bg-color: transparent;
    color: #4d4f59;
    cursor: pointer;
    --border-radius: 10px;
    font-family: Inter;
    font-weight: 500;
    letter-spacing: .006em;
    line-height: 18px;
    text-align: center;
    font-size: 100%;
    font-style: inherit;
    fill: black;
    box-sizing: border-box;
    outline: 0;
    border: 0;
    margin: 0 auto;
    height: 24px;
    width: 24px;
}


.store-action-buttons{
    text-align: center;
    user-select: none;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    position: relative;
}
#button_auth{
    text-align: center;
    user-select: none;
    box-sizing: border-box;
    margin: 0;
    border: 0;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    -webkit-box-align: center;
    align-items: center;
    color:#1f2026;
    cursor: pointer;
    display: inline-flex;
    font-family: Inter,sans-serif;
    font-size: .875rem;
    font-weight: 500;
    min-height: 42px;
    min-width: 42px;
    padding: 0 8px;
    position: relative;
    margin-right: 8px;
}

#button_auth:hover{
    text-align: center;
    user-select: none;
    box-sizing: border-box;
    margin: 0;
    border: 0;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    -webkit-box-align: center;
    align-items: center;
    color:#1f2026;
    cursor: pointer;
    display: inline-flex;
    font-family: Inter,sans-serif;
    font-size: .875rem;
    font-weight: 500;
    min-height: 42px;
    min-width: 42px;
    padding: 0 8px;
    position: relative;
    background: #dee0e5;
    border-radius: 4px;
    margin-right: 8px;
}
#odamcha{
    text-align: center;
    user-select: none;
    font-style: inherit;
    color:#1f2026;
    cursor: pointer;
    font-family: Inter,sans-serif;
    font-size: .875rem;
    font-weight: 500;
    width: 24;
    height: 24;
    box-sizing: border-box;
    outline: 0;
    border: 0;
    fill: #1f2026;
    margin-right: 9px;
}
#kirish{
    text-align: center;
    user-select: none;
    color: #1f2026;
    cursor: pointer;
    font-family: Inter,sans-serif;
    font-weight: 500;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    display: initial;
}

#yurak{
    text-align: center;
    user-select: none;
    font-style: inherit;
    color: #1f2026;
    cursor: pointer;
    font-family: Inter,sans-serif;
    font-size: .875rem;
    font-weight: 500;
    width: 24;
    height: 24;
    box-sizing: border-box;
    outline: 0;
    border: 0;
    fill: #1f2026;
    margin-right: 9px;
}

#saralangan{
    text-align: center;
    user-select: none;
    color: #1f2026;
    cursor: pointer;
    font-family: Inter,sans-serif;
    font-weight: 500;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    display: initial;
}

.ui-link.action-button{
    text-align: center;
    user-select: none;
    box-sizing: border-box;
    margin: 0;
    border: 0;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    text-decoration: none;
    -webkit-box-align: center;
    align-items: center;
    color: #1f2026;
    cursor: pointer;
    display: inline-flex;
    font-family: Inter,sans-serif;
    font-size: .875rem;
    font-weight: 500;
    min-height: 42px;
    min-width: 42px;
    padding: 0 8px;
    position: relative;
    margin-right: 8px;
}

.ui-link.action-button:hover{
    text-align: center;
    user-select: none;
    box-sizing: border-box;
    margin: 0;
    border: 0;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    text-decoration: none;
    -webkit-box-align: center;
    align-items: center;
    color:#1f2026;
    cursor: pointer;
    display: inline-flex;
    font-family: Inter,sans-serif;
    font-size: .875rem;
    font-weight: 500;
    min-height: 42px;
    min-width: 42px;
    padding: 0 8px;
    position: relative;
    background:#dee0e5;
    border-radius: 4px;
    margin-right: 8px;
}

#cart-button{
    text-align: center;
    user-select: none;
    box-sizing: border-box;
    margin: 0;
    border: 0;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    text-decoration: none;
    -webkit-box-align: center;
    align-items: center;
    color:#1f2026;
    cursor: pointer;
    display: inline-flex;
    font-family: Inter,sans-serif;
    font-size: .875rem;
    font-weight: 500;
    min-height: 42px;
    min-width: 42px;
    padding: 0 8px;
    position: relative;
}

.cart-enter{
    text-align: center;
    user-select: none;
    color:#1f2026;
    cursor: pointer;
    font-family: Inter,sans-serif;
    font-weight: 500;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    height: 100%;
    left: 0;
    position: absolute;
    right: 0;
    width: 100%;
}

#korzinka{
    text-align: center;
    user-select: none;
    color:#1f2026;
    cursor: pointer;
    font-size: .875rem;
    width: 24;
    height: 24;
    box-sizing: border-box;
    outline: 0;
    border: 0;
    font-family: 'icomoon' !important;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    opacity: 0.87;
    fill:#1f2026;
    margin-right: 9px;
}

#savat{
    text-align: center;
    user-select: none;
    color:#1f2026;
    cursor: pointer;
    font-family: Inter,sans-serif;
    font-weight: 500;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    display: initial;
}



.bottom-header-wrapper{
    box-sizing: border-box;
    margin: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    display: flex;
    padding: 10px 0 12px;
    width: 100%;
}

.bottom-header.block-sm{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    display: block;
    overflow: hidden;
    position: relative;
}

#tovarlar{
    box-sizing: border-box;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    list-style: none;
    user-select: none;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-box-pack: justify;
    backface-visibility: hidden;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    height: 38px;
    justify-content: space-between;
    margin: 0 -10px;
    -webkit-perspective: 1000;
    position: relative;
    transform: translateZ(0);
    transition: transform .3s ease-in-out,-webkit-transform .3s ease-in-out;
    white-space: nowrap;
    width: 100%;
    z-index: 4;
}
.category-promo-category-link{
    list-style: none;
    user-select: none;
    white-space: nowrap;
    box-sizing: border-box;
    padding: 0;
    border: 0;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    line-height: 1.5rem;
    display: flex;
    font-size: .875rem;
    margin: 0 10px;
    overflow: hidden;
    position: relative;
}
.category__body{
    list-style: none;
    user-select: none;
    white-space: nowrap;
    line-height: 1.5rem;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    -webkit-box-align: center;
    align-items: center;
    border-bottom: 2px solid transparent;
    cursor: pointer;
    display: flex;
    margin-bottom: -1px;
    padding-bottom: 6px;
    padding-top: 7px;
}

.imagecat{
    list-style: none;
    user-select: none;
    white-space: nowrap;
    line-height: 1.5rem;
    cursor: pointer;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    height: 24px;
    width: 24px;
}

.fast_cat{
    list-style: none;
    user-select: none;
    white-space: nowrap;
    line-height: 1.5rem;
    cursor: pointer;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    height: 24px;
    width: 24px;
}

.fast-title{
    list-style: none;
    user-select: none;
    cursor: pointer;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    display: inline-block;
    color: #1f2026 !important;
    font-family: Inter;
    font-size: .8rem;
    font-weight: 600;
    line-height: 1.2em;
    margin-left: 4px;
    white-space: nowrap;
}
.category{
    list-style: none;
    user-select: none;
    white-space: nowrap;
    box-sizing: border-box;
    padding: 0;
    border: 0;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    line-height: 1.5rem;
    display: flex;
    font-size: .875rem;
    margin: 0 10px;
    overflow: hidden;
    position: relative;
}
.category:hover:after{
    opacity: 1;
    -webkit-transform: translateX(0);
    transform: translateX(0);
}
.category:after{
    -webkit-backface-visibility: hidden;
    backface-visibility: hidden;
    background: #1f2026;
    bottom: 0;
    content: "";
    height: 2px;
    left: 0;
    opacity: 0;
    -webkit-perspective: 1000;
    perspective: 1000;
    position: absolute;
    text-align: center;
    -webkit-transform: translateX(-100%);
    transform: translateX(-100%);
    -webkit-transition: opacity .5s ease, -webkit-transform .5s ease;
    transition: opacity .5s ease, -webkit-transform .5s ease;
    transition: transform .5s ease, opacity .5s ease;
    transition: transform .5s ease, opacity .5s ease, -webkit-transform .5s ease;
    width: 100%;
}
.category:hover{
    list-style: none;
    user-select: none;
    white-space: nowrap;
    box-sizing: border-box;
    padding: 0;
    border: 0;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    line-height: 1.5rem;
    display: flex;
    font-size: .875rem;
    margin: 0 10px;
    overflow: hidden;
    position: relative;
}
.ui-link.category__body{
    list-style: none;
    user-select: none;
    white-space: nowrap;
    line-height: 1.5rem;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    opacity: 0.87;
    text-decoration: none;
    -webkit-box-align: center;
    align-items: center;
    border-bottom: 2px solid transparent;
    cursor: pointer;
    display: flex;
    margin-bottom: -1px;
    padding-bottom: 6px;
    padding-top: 7px;
    color: #4d4f59;
}
.ui-link.category__body:hover{
    list-style: none;
    user-select: none;
    white-space: nowrap;
    line-height: 1.5rem;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    outline: none;
    font-style: inherit;
    text-decoration: none;
    -webkit-box-align: center;
    align-items: center;
    border-bottom: 2px solid transparent;
    cursor: pointer;
    display: flex;
    margin-bottom: -1px;
    padding-bottom: 6px;
    padding-top: 7px;
    color:#1f2026;
    opacity: 1;
}

</style>
