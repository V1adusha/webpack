<template>
	<section>
		<div class="container">
			<img src="/assets/img/logo.png" alt="message">
			<p>{{ message }}</p>
		</div>
	</section>
</template>

<script>
export default {
	data () {
		return {
			message: 'Example Vue component',
		}
	}
}
</script>


