<script setup>
import SingleComponent from '../components/myComponents/SingleComponent.vue';
import RawHtmlData from '../components/myComponents/RawHtmlData.vue';
import DirectiveVShow from '../components/myComponents/directives/DirectiveVShow.vue';
import DirectiveVIf from '../components/myComponents/directives/DirectiveVIf.vue';
import DirectiveVModel from '../components/myComponents/directives/DirectiveVModel.vue';
import DirectiveVFor from '../components/myComponents/directives/DirectiveVFor.vue';
import ComputedProps from '../components/myComponents/computed-properties/ComputedProps.vue';
import ParentComponent from '../components/myComponents/props/ParentComponent.vue';

</script>

<template>
  <div>
    <h1>Hello Vue</h1>
    <!-- <h3>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quo unde accusamus omnis, inventore autem animi quibusdam ut consequatur vitae, itaque quidem odit a magnam labore minima alias dignissimos eum illum.</h3> -->
    -----------------------------
    <RawHtmlData />
    -----------------------------
    <SingleComponent />
    -----------------------------
    <DirectiveVShow />
    -----------------------------
    <DirectiveVIf />
    -----------------------------
    <DirectiveVModel />
    -----------------------------
    <DirectiveVFor />
    -----------------------------
    <ComputedProps />
    -----------------------------
    <ParentComponent />
  </div>
</template>

<style lang="css" scoped>
h1{
  color: red;
}
</style>