<template>
	<section
		class="hover:bg-primary rounded-22 flex flex-col items-center p-5 mx-5 text-center"
	>
		<div class="w-55 rounded-25 p-2 deg1">
			<img
				:src="item.userimg"
				class="rounded-22 border-2 border-back border-solid"
			/>
		</div>
		<h4 class="text-blanco mt-5">{{ item.nombre }}</h4>
	</section>
</template>

<script>
export default {
	props: ['item'],
};
</script>
