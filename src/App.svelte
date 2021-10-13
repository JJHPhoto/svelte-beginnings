<script>
  import {onMount} from "svelte";
  import ArtistList from "./ArtistList.svelte";
  import ArtistSearch from "./ArtistSearch.svelte";
  let searchTerm = "Artists";
  let artists = [];

  onMount(
    async() => {
      const res = await fetch(`data.json`);

      artists = await res.json();
    }
  )
</script>


<div class="container">
  <ArtistSearch searchTerm={searchTerm}/>
  <ArtistList {artists}/>
</div>

<style global lang="scss">
  $primary: purple;

  @import "../node_modules/bootstrap/scss/bootstrap.scss";
</style>
