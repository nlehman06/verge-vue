<template>
    <div class="bg-blue-darker w-full h-screen gradient relative">
        <div class="w-full h-full flex flex-col items-center bg-curves bg-no-repeat bg-left-bottom">
            <div class="text-white font-bold text-3xl font-sans mt-32">Code and Design</div>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style>
.bg-curves {
  background-image: url("../assets/curves.png");
}

.gradient {
  background: #4d46c0; /* Old browsers */
  background: -moz-linear-gradient(
    top,
    #4d46c0 0%,
    #7456cf 49%,
    #9664db 100%
  ); /* FF3.6-15 */
  background: -webkit-linear-gradient(
    top,
    #4d46c0 0%,
    #7456cf 49%,
    #9664db 100%
  ); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to bottom, #4d46c0 0%, #7456cf 49%, #9664db 100%);
  /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#4d46c0', endColorstr='#9664db', GradientType=0);
  /* IE6-9 */
}
</style>
