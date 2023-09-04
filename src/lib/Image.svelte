<script>
  export let src = "image url"
  export let alt = "alternative message for image"
</script>

<figure class="content section">
  <img {src} {alt} />
</figure>

<style>
  img {
    width: 1200px;
  }
</style>
