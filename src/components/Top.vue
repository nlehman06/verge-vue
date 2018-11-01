<template>
    <div class="bg-blue-darker w-full h-screen gradient relative">
        <div class="w-full h-full flex justify-between bg-curves bg-no-repeat bg-left-bottom">
            <div class="mt-32 ml-12 flex flex-col">
                <div>
                    <div class="text-purple-lightest font-bold text-5xl sm:text-6xl font-display uppercase">Code</div>
                    <div class="text-center text-purple-lightest font-semibold text-4xl sm:text-5xl font-display uppercase -mt-4">+</div>
                    <div class="text-purple-lightest font-bold text-5xl sm:text-6xl font-display uppercase -mt-4">Design</div>
                </div>
                <div class="text-white font-display font-medium mt-6 text-xl sm:text-2xl">When used together,<br>
                    you can build powerful solutions</div>
            </div>
            <div><!--Some image--></div>
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
  background: #526d63; /* Old browsers */
  background: -moz-linear-gradient(
    top,
    #526d63 0%,
    #4e7b70 30%,
    #98c8bc 100%
  ); /* FF3.6-15 */
  background: -webkit-linear-gradient(
    top,
    #526d63 0%,
    #4e7b70 30%,
    #98c8bc 100%
  ); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(
    to bottom,
    #526d63 0%,
    #4e7b70 30%,
    #98c8bc 100%
  ); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#526d63', endColorstr='#98c8bc',GradientType=0 ); /* IE6-9 */
}
</style>
