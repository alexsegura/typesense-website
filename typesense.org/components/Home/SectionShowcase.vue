<template>
  <div class="container">
    <h2 class="text-gradient-1">Showcase</h2>
    <div>
      Built with Typesense, InstantSearch UI components & hosted on Typesense
      Cloud.
    </div>
    <div class="row mt-4">
      <div class="col-sm-4">
        <HomeShowcaseBlock
          emoji="⚡ 🔍 🎵"
          link="https://songs-search.typesense.org"
        >
          <template #title>
            <small>Instantly Search</small><br />32 Million Songs
          </template>
        </HomeShowcaseBlock>
      </div>
      <div class="col-sm-4 mt-4 mt-sm-0">
        <HomeShowcaseBlock
          emoji="⚡ 🔍 📚"
          link="https://books-search.typesense.org"
        >
          <template #title>
            <small>Instantly Search</small><br />28 Million Books
          </template>
        </HomeShowcaseBlock>
      </div>
      <div class="col-sm-4 mt-4 mt-sm-0">
        <HomeShowcaseBlock
          emoji="⚡ 🔍 🥘"
          link="https://recipe-search.typesense.org"
        >
          <template #title>
            <small>Instantly Search</small><br />2 Million Recipes
          </template>
        </HomeShowcaseBlock>
      </div>
    </div>
  </div>
</template>
