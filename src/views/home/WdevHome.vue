<template>
    <main id="wdev-home">
        <div class="text-top">
            Vídeos novos toda <b>quinta</b> às <b>20h</b>
        </div>

        <a href="https://youtube.com/wdevoficial" target="_blank">
            <img src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg" alt="Inscreva-se" id="subscribe">
        </a>

        <div class="text-bottom">youtube.com/wdevoficial</div>
    </main>
</template>

<script>
import Vue from "vue";
import Component from "vue-class-component";

@Component({
    name: 'WdevHome',
    components: {}
})
export default class WdevHome extends Vue {}
</script>

<style scoped>
    main{
        background-color: var(--color-background-home);
        justify-content: center;
        text-align: center;
    }

    .text-top{
        color: var(--color-text-light);
        font-size: 22px;
        margin-bottom: 20px;
    }

    .text-bottom{
        color: var(--color-text-light);
        font-size: 18px;
        margin-top: 20px;
    }

    #subscribe {
        width: 340px;
    }

    @media (min-width: 700px) {
        #subscribe {
            width: 370px;
        }
    }
</style>