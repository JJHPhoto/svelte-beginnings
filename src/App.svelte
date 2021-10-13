<script>
  import ArtistList from "./ArtistList.svelte";
  import ArtistSearch from "./ArtistSearch.svelte";
  let searchTerm = "Tibetan Monk";
</script>


<div class="container">
  <ArtistSearch searchTerm={searchTerm}/>
  <ArtistList />
</div>

<style global lang="scss">
  $primary: purple;

  @import "../node_modules/bootstrap/scss/bootstrap.scss";
</style>
