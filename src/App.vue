<template>
	<v-app>
		<app-menu />
		<app-toolbar />
		<v-content>
			<app-carrosel/>	
		</v-content>	
		<app-footer />
	</v-app>
</template>

<script>
import Footer from '@/Footer.vue'
import Carrosel from '@/Carousel.vue'
import ToolBar from '@/Toolbar'
import Menu from '@/Menu'

export default {

	components: {"app-footer": Footer,
				"app-carrosel": Carrosel,
				"app-toolbar": ToolBar,
				"app-menu": Menu}
	

}
</script>
