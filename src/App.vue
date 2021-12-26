<template>
	<side-bar/>
	<main>
  	<router-view/>
	</main>
</template>

<script>
import SideBar from '@/components/SideBar.vue';
export default {
	components: {SideBar}
}
</script>