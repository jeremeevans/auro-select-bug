<script setup lang="ts">
</script>

<template>
  <main>
    <div class="control">
      <auro-select ref="countryControl">
        <span slot="label">Country</span>
        <auro-menu>
          <auro-menuoption value="United States">United States</auro-menuoption>
          <auro-menuoption value="Canada">Canada</auro-menuoption>
        </auro-menu>
      </auro-select>
    </div>
  </main>
</template>

<style scoped lang="scss">
@import "../node_modules/@alaskaairux/design-tokens/dist/tokens/SCSSVariables"; // Auro design tokens as Sass variables, required to import WCSS
@import "../node_modules/@alaskaairux/design-tokens/dist/tokens/SassCustomProperties"; // Auro design tokens as CSS Custom Properties, used by auro-* components
@import "../node_modules/@alaskaairux/webcorestylesheets/dist/breakpoints";
@import "../node_modules/@alaskaairux/webcorestylesheets/dist/fonts";
@import "../node_modules/@alaskaairux/webcorestylesheets/dist/normalize";
@import "../node_modules/@alaskaairux/webcorestylesheets/dist/essentials";
@import "../node_modules/@alaskaairux/webcorestylesheets/dist/headings";

div.control {
  padding-bottom: var(--auro-size-md);
}
</style>
