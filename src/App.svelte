<script>
	export let name;
</script>


<div class="container">
  <h1>Hello {name}!</h1>
  <p class="text-primary">
    Bacon ipsum dolor amet frankfurter tri-tip ham, doner ground round biltong salami spare ribs ball tip strip steak filet mignon meatloaf pork chop buffalo corned beef. Cow beef shank doner picanha tail. Ham short ribs shankle, salami shoulder ground round filet mignon chuck swine strip steak prosciutto t-bone bresaola. Swine ham turducken tri-tip chislic ham hock picanha rump t-bone capicola ground round short ribs filet mignon.
  </p>
</div>

<style lang="scss">
  $primary: purple;

  @import "../node_modules/bootstrap/scss/bootstrap.scss";
    h1 {
      color: $primary;
    }
</style>
