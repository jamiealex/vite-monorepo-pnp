<script>
import getArray from 'package-b';

export default {
  setup () {
    console.log( getArray());

    return {
      array: getArray(),
    };
  }
}
</script>

<template>
  <h1>Look at this array... {{ array }}</h1>
</template>
