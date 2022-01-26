<script context="module">
  export function load({ error }) {
    return {
      props: { error },
    };
  }
</script>

<script>
  export let message;
</script>

<div class="error">
  <h2>Oops</h2>
  <p>{message}</p>
  <a href="/guides">View all guides</a>
</div>

<style>
  .error {
    text-align: center;
    margin-bottom: 60px;
  }
</style>
