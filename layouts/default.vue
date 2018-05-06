<template lang="pug">
div
	header
		row(center)
			column(small="1", medium="2:3")
				h3.logo calculator
	main.bg-white
		<nuxt></nuxt>
	svd-footer
</template>
<style>

</style>
<script>
import svdFooter from "svd-footer/src/components/svd-footer.vue";

export default {
  components: { svdFooter }
};
</script>
