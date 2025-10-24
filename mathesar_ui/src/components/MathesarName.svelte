<script lang="ts">
  import IconPath from '@mathesar/component-library/icon/IconPath.svelte';
  import { staticText } from '@mathesar/i18n/staticText';
  import { iconMathesarName } from '@mathesar/icons';

  const [viewBoxWidth, viewBoxHeight, , , paths] = iconMathesarName.data.icon;
  const path = (Array.isArray(paths) ? paths : [paths]).at(0);
</script>

<div>
  Solutions
</div>

<style>
  .mathesar-name {
    fill: currentcolor;
  }
</style>
