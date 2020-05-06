<template>
  <div>
    <article>
       <v-breadcrumbs :items="items"></v-breadcrumbs>
      <h1 class="headline">記事の見出し</h1>
      <h1>普通のh1</h1>
      <h1 class="test">CSSで上書きできるか試す</h1>
      <p class="body-1">記事の内容記事の内容記事の内容記事の内容記事の内容記事の内容記事の内容記事の内容記事の内容記事の内容記事の内容記事の内容記事の内容</p>
      <!-- <div class="post-content" v-html="$md.render(post.fields.content)"></div> -->
      <h2 class="title">記事の章</h2>
      <h2>普通のh2</h2>
      <h2 class="title">記事の章</h2>
      <h2 class="title">記事の章</h2>
    </article>
    <p>次の記事</p>
    <p>前の記事</p>
    <p>広告</p>
    <Banner />
    <Subscribe />
  </div>
</template>

<script>
import Banner from "~/components/Banner.vue";
import Subscribe from "~/components/Subscribe.vue";

export default {
   data: () => ({
      items: [
        {
          text: 'Dashboard',
          disabled: false,
          href: 'breadcrumbs_dashboard',
        },
        {
          text: 'Link 1',
          disabled: false,
          href: 'breadcrumbs_link_1',
        },
        {
          text: 'Link 2',
          disabled: true,
          href: 'breadcrumbs_link_2',
        },
      ],
    }),
  components: {
    Banner,
    Subscribe
  }
};
</script>

<style scoped>
* {
  background-color: #f6f6f6;
  color: #433422;
  /* これは効くけど左右上下にマージンある */
}
html {
  background-color: gold;
  /* これは効かない  */
}
article {
  background-color: bisque;
  /* これは効く */
}

.test {
  color: red;
  /* 普通に効く */
}
</style>