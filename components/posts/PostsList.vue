<template>
  <section class='posts-list'>
    <PostPreview id='1' title='Title 1' text='This is preview text 1' thumbnail='http://www.kiplinger.com/slideshow/investing/T058-S001-10-tech-stocks-to-watch-like-a-hawk-this-spring/images/intro.jpg'/>
    <PostPreview id='2' title='Title 2' text='This is preview text 2' thumbnail='https://image.freepik.com/free-vector/modern-technology-background_1361-620.jpg'/>
    <PostPreview id='3' title='Title 3' text='This is preview text 3' thumbnail='https://previews.123rf.com/images/nexusplexus/nexusplexus1212/nexusplexus121200141/16620958-modern-wireless-technology-and-social-media-illustration.jpg'/>
  </section>
</template>

<script>
import PostPreview from '@/components/posts/PostPreview'
  export default {
    components: {
      PostPreview
    }
  }
</script>

<style scoped>
  .posts-list {
    display: flex;
    padding: 20px;
    box-sizing: border-box;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
}
</style>
