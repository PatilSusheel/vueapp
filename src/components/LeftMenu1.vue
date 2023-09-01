<template>
  <div class="page-container">
    <div class="left-column">
      <!-- Big Block 1 -->
      <div class="big-block">
        <div class="centered-content">
          <p class="highlight-text"><strong>Today's Highlight</strong></p>
          <hr class="block-divider">
          <h2 class="block-heading">Heading</h2>
          <p class="highlight-text">Jul 19, 2022, Reps Name, ABC Company</p>
          <hr class="block-divider">
          <h2 class="block-heading">Heading</h2>
          <p class="highlight-text">Jul 19, 2022, Reps Name, ABC Company</p>
          <hr class="block-divider">
          <h2 class="block-heading">Heading</h2>
          <p class="highlight-text">Jul 19, 2022, Reps Name, ABC Company</p>
          <hr class="block-divider">
          <h2 class="block-heading">Heading</h2>
          <p class="highlight-text">Jul 19, 2022, Reps Name, ABC Company</p>
          <hr class="block-divider">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LeftMenu1',
};
</script>

<style scoped>
/* Add CSS styles for the page container and big blocks as needed */
.page-container {
  display: flex;
  justify-content: flex-start; /* Align to the left */
  padding: 20px;
}

.left-column {
  display: flex;
  flex-direction: row; /* Arrange blocks horizontally */
  align-items: flex-start; /* Align blocks to the left */
}

.big-block {
  width: 300px; /* Fixed width for each big block */
  height: 320px; /* Fixed height for each big block */
  padding: 10px;
  background-color: #ffffff;
  border: 1px solid #ccc;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-radius: 10px; /* Rounded corners */
  display: flex;
  flex-direction: column;
}

/* Style for the text content inside the big block */
.centered-content {
  text-align: left; /* Align text to the left */
}

.highlight-text {
  font-size: 14px;
  color: #333; /* Change the text color to #3f51b5 */
  margin-bottom: 5px; /* Add space below text */
}

.block-heading {
  font-size: 14px;
  color: #3f51b5; /* Change the heading color (e.g., #333) */
  margin-top: 10px; /* Add space above the heading */
}

.block-divider {
  width: 100%; /* Horizontal line width */
  border: 1px solid #ccc; /* Line color and style */
  margin: 10px 0; /* Add space above and below the line */
}
</style>
