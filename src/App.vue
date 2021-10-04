<template>
	<link
		rel="stylesheet"
		href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css"
		integrity="sha512-YWzhKL2whUzgiheMoBFwW8CKV4qpHQAEuvilg9FAn5VJUDwKZZxkJNuGM4XkWuk94WCrrwslk8yWNGmY1EduTA=="
		crossorigin="anonymous"
		referrerpolicy="no-referrer"
	/>
	<div class="whole-page">
		<Header />
		<SocialMediaIcons />
	</div>
</template>

<script>
	import Header from '@/components/Header';
	import SocialMediaIcons from '@/components/SocialMediaIcons';
	export default {
		components: {
			Header,
			SocialMediaIcons,
		},
    data(){
      return{
        socialMediaLinks: [],
      };
    },
		provideData() {
			return {
				socialMediaLinks: [
					{ platform: 'facebook', href: 'https://www.facebook.com/osmerd04' },
					{ platform: 'instagram', href: 'https://www.instagram.com/osmnerd' },
					{ platform: 'youtube', href: 'https://www.facebook.com/osmerd04' },
					{ platform: 'twitter', href: 'https://www.facebook.com/osmerd04' },
					{ platform: 'github', href: 'https://www.facebook.com/osmerd04' },
					{ platform: 'whatsapp', href: 'tel:+905306619958' },
				],
			};
		},
	};
</script>

<style></style>
