<script lang="ts">
  import { navigate } from "svelte-native";
  import Page from "./Page";

  let message: string = "Blank Svelte Native App";
</script>

<page>
  <actionBar title="Home" />
  <stackLayout>
    <button
      on:tap={() => {
        navigate({ page: Page });
      }}
      text="Hello"
    />
    <span text=" {message}" />
  </stackLayout>
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
