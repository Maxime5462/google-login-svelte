<script>
  import GoogleSignInButton from "./GoogleSignInButton.svelte";
  import Logout from "./Logout.svelte";
  let name = "world";

</script>

<style>
  h1 {
    color: blue;
  }
</style>

<GoogleSignInButton />

<Logout />
