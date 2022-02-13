<template>
  <article>
    <!-- <h1>{{ article.title }}</h1>
    <h3>{{ article.author }}</h3>
    <nuxt-content :document="article" /> -->
    <div class="container">
	<div class="row">
		<!-- Begin Post -->
		<div class="col-md-12 col-md-offset-2 col-xs-12">
			<div class="mainheading">

				<!-- Begin Top Meta -->
				<div class="row post-top-meta">
					<div class="col-md-10">
						<nuxt-link to="/blog"> Back to Blog List </nuxt-link>
					</div>
				</div>
				<!-- End Top Menta -->

				<h1 class="posttitle">{{  article.title  }}</h1>

			</div>

			<!-- Begin Featured Image -->
			<!-- <img class="featured-image img-fluid" src="assets/img/demopic/10.jpg" alt=""> -->
			<!-- End Featured Image -->

			<!-- Begin Post Content -->
			<div class="article-post">
				<nuxt-content :document="article" />
			</div>
			<!-- End Post Content -->

			<!-- Begin Tags -->
			<!-- <div class="after-post-tags">
				<ul class="tags">
					<li><a href="#">Design</a></li>
					<li><a href="#">Growth Mindset</a></li>
					<li><a href="#">Productivity</a></li>
					<li><a href="#">Personal Growth</a></li>
				</ul>
			</div> -->
			<!-- End Tags -->

		</div>
		<!-- End Post -->

	</div>
</div>
  </article>
</template>
<script>
export default {
  async asyncData ({ $content, params }) {
    const article = await $content('articles', params.slug).fetch()
  console.log(article)
    return { article }
  }
}
</script>
