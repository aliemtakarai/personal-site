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

				<h1 class="posttitle">18 Things You Should Learn Before Moving Into a New Home</h1>

			</div>

			<!-- Begin Featured Image -->
			<img class="featured-image img-fluid" src="assets/img/demopic/10.jpg" alt="">
			<!-- End Featured Image -->

			<!-- Begin Post Content -->
			<div class="article-post">
				<p>
					Holy grail funding non-disclosure agreement advisor ramen bootstrapping ecosystem. Beta crowdfunding iteration assets business plan paradigm shift stealth mass market seed money rockstar niche market marketing buzz market.
				</p>
				<p>
					Burn rate release facebook termsheet equity technology. Interaction design rockstar network effects handshake creative startup direct mailing. Technology influencer direct mailing deployment return on investment seed round.
				</p>
				<p>
					 Termsheet business model canvas user experience churn rate low hanging fruit backing iteration buyer seed money. Virality release launch party channels validation learning curve paradigm shift hypotheses conversion. Stealth leverage freemium venture startup business-to-business accelerator market.
				</p>
				<blockquote>
					Gen-z strategy long tail churn rate seed money channels user experience incubator startup partner network low hanging fruit direct mailing. Client backing success startup assets responsive web design burn rate A/B testing metrics first mover advantage conversion.
				</blockquote>
				<p>
					Freemium non-disclosure agreement lean startup bootstrapping holy grail ramen MVP iteration accelerator. Strategy market ramen leverage paradigm shift seed round entrepreneur crowdfunding social proof angel investor partner network virality.
				</p>
			</div>
			<!-- End Post Content -->

			<!-- Begin Tags -->
			<div class="after-post-tags">
				<ul class="tags">
					<li><a href="#">Design</a></li>
					<li><a href="#">Growth Mindset</a></li>
					<li><a href="#">Productivity</a></li>
					<li><a href="#">Personal Growth</a></li>
				</ul>
			</div>
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

    return { article }
  }
}
</script>
