<script lang="ts">
  import { navigate } from "svelte-native";
  import PostImageText from "./PostImageText";

  let message: string = " Svelte Native App";
</script>

<page>
  <actionBar title="Home" />
  <PostImageText />
</page>

<style>
  .info .fas {
    color: #3a53df;
  }

  .info {
    font-size: 20;
    horizontal-align: center;
    vertical-align: center;
  }
</style>
