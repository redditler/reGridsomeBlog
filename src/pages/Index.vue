<template>
  <Layout>
    <img class="greet-image" src="../../uploads/hello.svg" />

    <h2 class="mb-4">Gridsome starter bootstrap</h2>

    <h3 class="mt-5 mb-4">Features</h3>
    <ul>
      <li>
        <b>Gridsome - </b> Vue.js & GraphQL powered framework genrating static files.
      </li>
      <li>
        <b>Bootstrap & Bootstrap Vue - </b> Powerful styling and layout with styled Vue components.
      </li>
      <li>
        <b>Sass - </b> Professional grade CSS extension with many features.
      </li>
      <li>
        <b>Forestry.io - </b> CMS that uses the Github repo for storage.
      </li>
      <li>
        <b>Markdown - </b> Easy and widely used format for writing content.
      </li>
      <li>
        <b>Netlify forms - </b> Netlify forms ready to be used after deployment.
      </li>
      <li>
        <b>Google Analytics - </b> Just add your tracking ID in the config.
      </li>
      <li>
        <b>Sitemap generator - </b> Automatically generates a sitemap.xml file.
      </li>
    </ul>

    <h3 class="mt-5 mb-4">Getting started</h3>
    <p>The easiest way to get started quick is to use the Forestry button below, which will create a Github repository for you,
      clone this starter repo and import all data to the CMS. After that is complete, you can just go to <a href="https://www.netlify.com/">Netlify</a>
      and connect your newly created project that will set it up for automatic deployment when you commit to the Github repo.
    </p>

    <a href="https://app.forestry.io/quick-start?repo=LokeCarlsson/gridsome-starter-bootstrap&amp;provider=github&amp;engine=vuepress" target="_blank" rel="nofollow">
      <img class="mt-3 mb-3" src="https://camo.githubusercontent.com/2455e97e4e989374a355fb0bea7ad364f2561c92/68747470733a2f2f6173736574732e666f7265737472792e696f2f696d706f72742d746f2d666f7265737472794b2e737667" alt="Import this project into Forestry" data-canonical-src="https://assets.forestry.io/import-to-forestryK.svg" style="max-width:100%;" />
    </a>

    <h3 class="mt-4 mb-4">Netlify config</h3>
    <p>
      Use the following build config for Netlify
    </p>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Gridsome starter bootstrap'
  }
}
</script>

<style>
.greet-image {
  display: block;
  margin: auto;
  width: 90%;
  max-width: 500px;
  padding-bottom: 50px;
}
</style>
