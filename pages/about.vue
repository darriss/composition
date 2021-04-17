<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="Traditional Marriage"
      subtitle="Example About Page"
      image="/uploads/IMG-4126.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
          <h3>Samantha Darris</h3>
          <p>
            Samantha Darris is from New York City and attends ALlegheny College.
            While she has always enjoyed computer science, throughout college she
            grew a passion for cultural anthropology, social justice, and transnational
            feminism. Her passion developed when she studied abroad in Morocco from
            August to December of 2019. This experience changed how she viewed international
            affairs, feminism, and marriage. She left Morocco with many questions,
            and looked for answers in this research project.
          </p>

          <quote-card />
            <strong>Alias aut facere harum ipsam</strong>
          </p>
        </div>

        </div>
      </template>
    </main-section>
  </div>
</template>
<script>
import QuoteCard from '~/components/cards/QuoteCard'
export default {
  head() {
    return {
      title: `About | ${this.$siteConfig.siteName}`
    }
  },
  components: { QuoteCard }
}
</script>
