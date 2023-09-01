<template>
  <div class="page-container">
    <div class="left-column">
      <!-- Small Block 1 -->
      <div class="small-block">
        <!-- Your content for Small Block 1 goes here -->
        <div class="centered-content">
          <h2>Total Deals</h2>
          <h1>NaN</h1>
        </div>
      </div>

      <div class="block-separator"></div>

      <!-- Small Block 2 -->
      <div class="small-block">
        <!-- Your content for Small Block 2 goes here -->
        <div class="centered-content">
          <h2>Closed Deals</h2>
        </div>
      </div>

      <div class="block-separator"></div>

      <!-- Small Block 3 -->
      <div class="small-block">
        <!-- Your content for Small Block 3 goes here -->
        <div class="centered-content">
          <h2>Active Deals</h2>
        </div>
      </div>
    </div>
  </div>
  
</template>

<script>
export default {
  name: 'LeftMenu',
};
</script>

<style scoped>
/* Add CSS styles for the page container and small blocks as needed */
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

.small-block {
  width: 100px; /* Fixed width for each small block */
  height: 100px; /* Fixed height for each small block */
  padding: 10px;
  background-color: #ffffff;
  border: 1px solid #ccc;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-radius: 10px; /* Rounded corners */
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

/* Style for the content inside the small blocks */
.centered-content {
  text-align: center; /* Center text horizontally */
}

.small-block h2 {
  font-size: 16px;
  margin-bottom: 5px; /* Add some space below the headings */
}

.block-separator {
  width: 10px; /* Adjust the width to control the spacing */
}

.small-block p {
  font-size: 12px;
}
</style>
