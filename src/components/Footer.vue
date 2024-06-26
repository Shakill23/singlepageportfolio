<template>
    <footer class="container-fluid">
        <div class="row">
            <p class="lead">Shakeel's portfolio &copy; <span class="shadow">{{ currentYear }}</span></p>
        </div>
    </footer>
</template>

<script>
    export default {
        name: 'FooterComp',
        data(){
            return{
                currentYear: new Date().getUTCFullYear()
            }
        }
    }
</script>