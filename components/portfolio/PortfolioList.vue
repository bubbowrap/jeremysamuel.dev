<template>
  <div class="portfolio">
    <ul class="portfolio__list">
      <PortfolioBlock
        v-for="post in featuredPosts"
        :key="post.attributes.title"
        :post="post"
      />
    </ul>
    <div v-if="showMoreBtn" class="portfolio__button-container">
      <button class="btn btn--resume" @click="showMore">More Projects +</button>
    </div>
  </div>
</template>

<script>
import PortfolioBlock from '@/components/portfolio/PortfolioBlock.vue'

export default {
  components: {
    PortfolioBlock,
  },
  // eslint-disable-next-line
  props: ['posts'],
  data() {
    return {
      featuredPosts: [],
      postLimit: 6,
      showMoreBtn: null,
    }
  },
  created() {
    this.featuredPosts = this.posts
    // shows more button depending on number of posts
    this.showMoreBtn = this.postLimit < this.posts.length
  },
  mounted() {
    this.featuredPosts = this.posts.slice(0, this.postLimit)
  },
  methods: {
    showMore(e) {
      e.preventDefault()
      this.$nuxt.refresh()
      this.featuredPosts = this.posts
      this.showMoreBtn = false
    },
  },
}
</script>
