<template>
  <div>
    <h1>Chart.js</h1>
    <!-- 바 차트 컴포넌트 -->
    <bar-chart></bar-chart>
    <!-- 라인 차트 컴포넌트 -->
    <line-chart></line-chart>
  </div>
</template>

<script>
import BarChart from './components/BarChart.vue';
import LineChart from './components/LineChart.vue';

export default {
  components: {
    BarChart,
    LineChart,
  },
}
</script>

<style>

</style>