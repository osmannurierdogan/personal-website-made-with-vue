<template>
	<div class="social-media-icons-container">
		<i class="fab fa-facebook-f facebook social-media-icon "></i>
		<i class="fab fa-instagram instagram social-media-icon "></i>
		<i class="fab fa-twitter twitter social-media-icon "></i>
		<i class="fab fa-youtube youtube social-media-icon "></i>
		<i class="fab fa-linkedin-in linkedin social-media-icon "></i>
		<i class="fab fa-whatsapp whatsapp social-media-icon "></i>
	</div>
</template>
<script>
	export default {
		data() {
			return {};
		},
	};
</script>
<style scoped>
	/* 
  ! SOCIAL MEDIA SECTION STYLING START 
  */
	.social-media-icons-container {
		margin: 1rem;
	}
	.social-media-icon {
		margin: 1rem;
		margin-top: 2rem;
		font-size: 1.75rem;
		cursor: pointer;
	}
  .social-media-icon:hover{
    cursor: pointer;
  }
	.facebook:hover {
		color: var(--facebook-color);
	}
	.twitter:hover {
		color: var(--twitter-color);
	}
	.instagram:hover {
		color: var(--instagram-color);
	}
	.linkedin:hover {
		color: var(--linkedin-color);
	}
	.youtube:hover {
		color: var(--youtube-color);
	}
	.whatsapp:hover {
		color: var(--whatsapp-color);
	}
	/* 
  ! SOCIAL MEDIA SECTION STYLING END 
  */
</style>
