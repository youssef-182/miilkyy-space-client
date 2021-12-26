<template>
	<div class="flex">
		<side-bar/>
		<main class="container">
	  	<router-view/>
		</main>
	</div>
</template>

<script>
import SideBar from '@/components/SideBar.vue';
export default {
	components: {SideBar}
}
</script>