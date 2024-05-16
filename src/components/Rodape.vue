<template>
    <footer class="rodape paragrafo">
        <p>Desenvolvido por André Luis Quiosi | 2024 - Projeto ficticio de aprendizado.</p>
    </footer>

</template>
<script lang="ts">
export default {

}
</script>
<style scoped>
.rodape {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 1.5rem 7.5rem;
    background: var(--verde-escuro, #263A29);
}

@media only screen and (max-width: 1300px) {
    .rodape {
        padding: 1.5rem 3.75rem;
    }
}

@media only screen and (max-width: 767px) {
    .rodape {
        padding: 1.5rem;
    }
}
</style>