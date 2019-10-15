<template>
	<div class="todo-item">
		<p>Todo Item</p>
	</div>
</template>

<script type="text/javascript">
	export default {
		name: "TodoItem",
		props: ["todo"]
	}
</script>

<style type="text/css">
	.todo-item {
		background: #f4f4f4;
		padding: 10px;
		border-bottom: 1px #ccc dotted;
	}
	.is-complete {
		text-decoration: line-through;
	}
	.del {
		background: #ff0000;
		color: #fff;
		border: none;
		padding: 5px 9px;
		border-radius: 50%;
		cursor: pointer;
		float: right;
	}
</style>