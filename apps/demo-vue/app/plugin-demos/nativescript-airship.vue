<template>
  <Page>
    <ActionBar>
      <Label text="nativescript-airship"/>
    </ActionBar>

    <GridLayout>
      <Button class="info" :text="message"/>
    </GridLayout>
  </Page>
</template>

<script lang="ts">
  import Vue from "nativescript-vue";
  import { DemoSharedNativescriptAirship } from '@demo/shared';
  import { } from '@nstudio/nativescript-airship';

  export default Vue.extend({
    computed: {
      message() {
        return "Test nativescript-airship";
      }
    }
  });
</script>

<style scoped lang="scss">

  .info {
    font-size: 20;
    horizontal-align: center;
    vertical-align: center;
  }
</style>
