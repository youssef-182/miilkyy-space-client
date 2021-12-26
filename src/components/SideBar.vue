<template>
	<aside class="bg-epic-purple min-h-screen h-full w-1/5 flex flex-col">
		<div class="flex justify-center my-4">
			<img class="rounded-2xl border border-black h-auto w-12" src="../assets/logo.png" alt="">
		</div>
		<div class="bg-gray rounded-md w-full p-3 text-white">
			<i>icon</i>
			<router-link class="font-bold mx-2" to="#">Home</router-link>
		</div>
		<div class="bg-gray rounded-md p-3 text-white">
			<i>icon</i>
			<router-link class="font-bold mx-2" to="#">Search</router-link>
		</div>
		<div class="bg-gray rounded-md p-3 text-white">
			<i>icon</i>
			<router-link class="font-bold mx-2" to="#">My Library</router-link>
		</div>
		<hr class="text-white mx-4 mb-1">
		<div class="bg-gray rounded-md p-3 text-white">
			<i>icon</i>
			<router-link class="font-bold mx-2" to="#">My Favirotes</router-link>
		</div>
		<hr class="text-white mx-4 mt-1">
		<div class="p-3 text-white flex">
			<i>icon</i>
			<h4 class="font-bold mx-2">My Playlists</h4>
		</div>
		<div class="bottom-0 absolute">
			<router-link class="text-white font-bold" to="#">Logout</router-link>
		</div>
	</aside>
</template>

<style scoped>
.text-white {
	color:  white;
}

.bg-gray {
	/*background-color: gray;*/
	transition: background-color .5s;
	margin-bottom: .2rem;
}

.bg-gray:hover {
	background-color: #9e0059;
	cursor: pointer;
}
</style>