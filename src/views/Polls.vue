<template>
  <div>
    <section class="section">
      <h1 class="title">Community Polls</h1>
      <h2 class="subtitle">
        Your input will help improve the stream! Please vote on the following: 
      </h2>
    </section>
    <section class="section uneven-two-column">
      <div>
      <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfsB6OzCVOxgtWXlRIlGFttiFu0-_5ubb43SMWfTePgNdOm4g/viewform?embedded=true" width="320" height="451" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
      </div>
      <div class="chart">
        CHART HERE
      </div>
    </section>
  </div>
</template>
<style lang="scss">
  .uneven-two-column {
    display: flex;
    > .chart {
      flex: 1;
      background-color: pink;
    }
  }
</style>
