<template>
  <div id="app">

    <nestedone message="This is message one..." :number="20"></nestedone>

    <nestedone message="This is another message..."></nestedone>

  </div>
</template>

<script>
import nestedone from './components/NestedOne';

export default {
  name: 'app',
  components:
  {
    nestedone
  }
}
</script>

<style>

  body
  {
    padding: 25px;
    font-family: "helvetica";
    box-sizing: border-box;
  }

  #app > section
  {
    margin: 25px;
  }

  h1
  {
    font-size:20px;
    font-weight: normal;
    color: #333;
  }

  #app > h1
  {
    margin: 0;
    font-size: 25px;
  }

  section
  {
    margin: 25px 0 0 0;
    padding: 25px;
    border-radius: 5px;
    background: rgba(200,200,200,0.4);
  }

  section h1
  {
    padding: 0;
    margin: 0;
  }
</style>
