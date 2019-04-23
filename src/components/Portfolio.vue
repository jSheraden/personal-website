<template>
  <div class="portfolio">
    <div class="content">
      <h1>My Portfolio</h1>
      <p>Here are some projects I have been working on lately:</p>
      <div class="project-container">
        <div class="project"></div>
        <div class="project"></div>
        <div class="project"></div>
      </div>
    </div>
  </div>
</template>

<style>
.portfolio {
  background-color: #daf7dc;
  background: url('../assets/mustard_field.jpg') no-repeat fixed center;
}

.portfolio h1,
.portfolio p {
  color: #ffffff;
}

.project-container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

.project {
  margin: 20px;
  width: 350px;
  min-height: 350px;
  background-color: #ffffff;
}

@media screen and (max-width: 750px) {
  .project-container {
    flex-direction: column;
  }
}
</style>
