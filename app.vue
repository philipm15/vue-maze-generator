<template>
  <div>
    <NuxtWelcome/>
  </div>
</template>
<script lang="ts">
import {MazeGenerator} from "~/maze-generator/maze-generator";

const mazeGenerator = new MazeGenerator(9, 20);
console.log(mazeGenerator.cells)
</script>
