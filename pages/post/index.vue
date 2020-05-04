<template>
  <div>
    <article>
      <h1>記事の見出し</h1>
      <!-- <div class="post-content" v-html="$md.render(post.fields.content)"></div> -->
    </article>
    <p>次の記事</p>
    <p>前の記事</p>
    <p>広告</p>
    <Banner />
    <Subscribe />
    <FeedCard />
  </div>
</template>

<script>
import Banner from "~/components/Banner.vue";
import Subscribe from "~/components/Subscribe.vue";
import FeedCard from "~/components/FeedCard.vue";

export default {
  components: {
    Banner,
    Subscribe,
    FeedCard
  }
};
</script>
