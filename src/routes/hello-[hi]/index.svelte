<script context="module">
  let hi;
  export async function load(ctx) {
    hi = ctx.page.params.hi;

    return { props: { hi } };
  }
</script>

<main>
    <deus>
        <h1>
            {hi}
        </h1>
    </deus>
</main>
