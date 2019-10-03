<template lang="pug">

.w3-container
	img(alt='Vue logo', src='../assets/logo.png')
	helloworld(msg='Addio Mondo Crudele')
</template>


<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
	name: 'home',
	components: {
		HelloWorld
	}
}
</script>
