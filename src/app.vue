<template>
	<div id="app">
		<div id="cover"></div>
		<div class="container">
			<Header></Header>
			<Todo></Todo>
			<Footer></Footer>
		</div>
	</div>
</template>

<script>
import Header from './view/todo/header.vue'
import Footer from './view/todo/footer.vue'
import Todo from './view/todo/todo.vue'

export default {
	components: {
		Header,
		Footer,
		Todo
	}
}
</script>

<style lang="css" scoped>
#app {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
}

.container{
	margin-top: 10%;
}

#cover {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  background-color: #555;
  opacity: 0.5;
  z-index: -1;
}
</style>

