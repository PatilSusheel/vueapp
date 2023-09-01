<template>
  <div class="page-container">
    <div class="centered-column">
      <!-- Big Block 1 -->
      <div class="big-block">
        <div class="centered-content">
          <p class="highlight-text"><strong>Recent Calls</strong></p>
          <hr class="block-divider">
          <h6 class="heading">Today</h6>
          <div class="block-with-text">
            <div class="image-with-text">
              <img src="../assets/contacts.png" alt="Contacts Logo" class="contacts">
              <div class="text">
                <p class="highlight-text"><strong>ABC Company</strong></p> <!-- Add this line -->
                <p class="highlight-text">Date</p> <!-- Add this line -->
                <p class="highlight-text">Deal Closing date</p>
              </div>
            </div>
          </div>
          <hr class="block-divider">
          <h6 class="heading">Yesterday</h6>
          <div class="block-with-text">
            <div class="image-with-text">
              <img src="../assets/contacts.png" alt="Contacts Logo" class="contacts">
              <div class="text">
                <p class="highlight-text"><strong>ABC Company</strong></p> <!-- Add this line -->
                <p class="highlight-text">Date</p> <!-- Add this line -->
                <p class="highlight-text">Deal Closing date</p>
              </div>
            </div>
          </div>
          <hr class="block-divider">
          <h6 class="heading">Tuesday</h6>
          <div class="block-with-text">
            <div class="image-with-text">
              <img src="../assets/contacts.png" alt="Contacts Logo" class="contacts">
              <div class="text">
                <p class="highlight-text"><strong>ABC Company</strong></p> <!-- Add this line -->
                <p class="highlight-text">Date</p> <!-- Add this line -->
                <p class="highlight-text">Deal Closing date</p>
              </div>
            </div>
          </div>
          <hr class="block-divider">
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Add CSS styles for positioning the block at the top middle */
.page-container {
  display: flex;
  justify-content: center; /* Center horizontally */
  align-items: flex-start; /* Align to the top vertically */
  padding: 20px;
  height: 100vh; /* Ensure the container covers the full viewport height */
}
.contacts{
  height: 50px;
  width: 50px;
}

.centered-column {
  display: flex;
  flex-direction: column; /* Arrange blocks vertically */
  align-items: center; /* Center horizontally within the column */
}

.big-block {
  width: 250px; /* Fixed width for each big block */
  height: 700px; /* Fixed height for each big block */
  padding: 10px;
  background-color: #ffffff;
  border: 1px solid #ccc;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-radius: 10px; /* Rounded corners */
  display: flex;
  flex-direction: column;
}

/* Rest of your existing styles */
</style>
