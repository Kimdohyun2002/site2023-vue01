<template>
  <div className="youtube__cont container">
    <ul>
      <li v-for="(youtube, index) in youtubes" :key="index">
        <a :href="`https://www.youtube.com/${youtube.id}`">
          <img :src="`${youtube.snippet.thumbnails.medium.url}`" alt="#" />
          <span>{{ youtube.snippet.title }}</span>
        </a>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  props: {
    youtubes: {
      type: Array,
      required: true,
    },
  },
};
</script>
<style lang="scss">
.youtube__cont {
  ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin-bottom: 100px;
    li {
      width: 24.3333%;
      margin-bottom: 4%;
      span {
        display: block;
        margin: 4px 0;
        white-space: nowrap;
        overflow: hidden;
        text-overflow: ellipsis;
        color: #f1e5d4;
      }
    }
  }
}
</style>
