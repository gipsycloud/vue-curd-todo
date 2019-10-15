<template>
	<div>
		<form @submit="addTodo">
			<input type="text" v-model="title" name="title" placeholder="Add Todo ....">
			<input type="submit" value="Submit" class="btn" name="">
		</form>
	</div>
</template>

<script type="text/javascript">
	export default {
		name: "AddTodo",
		data() {
			return {
				title: ''
			}
		}
	}
</script>

<style scoped>
	form {
		display: flex;
	}
	input[type="text"] {
		flex: 10;
		padding: 5px;
	}
	input[type="submit"] {
		flex: 2;
	}
</style>