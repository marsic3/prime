<template>
    <footer class="footer has-cards">
        <div class="container">
            <!-- <hr> -->
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        <a href="https://www.linkedin.com/in/milos-arsic-292b49142/" target="_blank" rel="noopener" class="text-custom">Developed by Marsic</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style lang="scss" scoped>

</style>
