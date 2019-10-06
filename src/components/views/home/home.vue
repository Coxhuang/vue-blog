<template>
	<div class="home">
		<homehead></homehead>
		<hometitle></hometitle>
		<homemain></homemain>
	</div>
</template>

<script>
    import homehead from '@/components/views/home/home_head/homehead'
	import hometitle from '@/components/views/home/home_title/hometitle'
	import homemain from '@/components/views/home/home_main/homemain'

	export default {
	name: 'Home',
		data () {
			return {
				msg: 'Welcome to Your Vue.js App'
			}
		},
		components: {
			homehead,
			hometitle,
			homemain
        },
	}
</script>

<style lang="scss" scoped>
	
</style>
