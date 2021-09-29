
<template>
    <header>

        <div class="brand-name">
          <a href="/">
            <img :src="require(`@/assets/bizzcon1.png`)" href="/" alt="" />
          </a>
            
        </div>

        <div class="drawer-toggle" role="button" @click="$store.dispatch('nav/toggleSidebar')">
            <div class="bar"></div>
            <div class="bar"></div>
            <div class="bar"></div>
        </div>

        <div class="app-links">
            <app-links></app-links>
        </div>

    </header>
</template>

<script>
    import AppLinks from '~/components/AppLinks'
export default {
    components: { AppLinks }
}
</script>

<style scoped>
    header{
        display: grid;
        grid-template: 60px / auto 1fr;
        align-items: center;
        background-color: white;
    }
    .app-links{
        justify-self: end;
    }
    .brand-name {
        margin: 0 10px;
        font-size: 1.3rem;
    }
    .brand-name a {
        text-decoration: none;
        color:  rgba(255,181,17,255);
    }
    .drawer-toggle .bar {
        width: 90%;
        height: 2px;
        background-color: rgba(255,181,17,255);
    }
    .drawer-toggle {
        display: flex;
        justify-self: end;
        flex-direction: column;
        justify-content: space-around;
        height: 50%;
        width: 35px;
        padding-right: 16px;
        cursor: pointer;
    }
    @media (max-width: 1250px) {
        header{
            padding: 0 16px;
        }
        header:nth-child{
            justify-self: end !important;
        }
        .app-links {
            display: none;
        }
    }
    @media (min-width: 1250px) {
        header{
            padding: 0 64px;
        }
        .app-links {
            display: block;
        }
        .drawer-toggle {
            display: none;
        }
    }
</style>