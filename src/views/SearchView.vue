<script setup>
import CategorySelect from '../components/CategorySelect.vue';
</script>

<template>
	<div class="p-8">
		<button type="button" class="text-white text-2xl font-semibold hover:underline cursor-pointer">
			Podcasts to make to Smarter
		</button>

		<div class="py-1.5"></div>

		<div class="grid xl:grid-cols-5 lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 gap-6">
			<CategorySelect category="Podcasts" image="https://picsum.photos/id/40/300/300" />
			<CategorySelect category="Audiobooks" image="https://picsum.photos/id/1/300/300" />
			<CategorySelect category="Made for You" image="https://picsum.photos/id/2/300/300" />
			<CategorySelect category="New Release" image="https://picsum.photos/id/3/300/300" />
			<CategorySelect category="New Release" image="https://picsum.photos/id/4/300/300" />
			<CategorySelect category="Podcasts" image="https://picsum.photos/id/5/300/300" />
			<CategorySelect category="Audiobooks" image="https://picsum.photos/id/6/300/300" />
			<CategorySelect category="Made for You" image="https://picsum.photos/id/7/300/300" />
			<CategorySelect category="New Release" image="https://picsum.photos/id/8/300/300" />
			<CategorySelect category="New Release" image="https://picsum.photos/id/9/300/300" />
			<CategorySelect category="Podcasts" image="https://picsum.photos/id/10/300/300" />
			<CategorySelect category="Audiobooks" image="https://picsum.photos/id/11/300/300" />
			<CategorySelect category="Made for You" image="https://picsum.photos/id/12/300/300" />
			<CategorySelect category="New Release" image="https://picsum.photos/id/13/300/300" />
			<CategorySelect category="New Release" image="https://picsum.photos/id/14/300/300" />
		</div>
	</div>
</template>