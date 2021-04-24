<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="About the Creator"
      image="/uploads/IMG-4126.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
          <h3><center>Samantha Darris</center></h3>

          <p><center>
            Samantha Darris is from New York City in the Class of 2021 at Allegheny College.
            While she has always enjoyed computer science, throughout college she
            grew a passion for cultural anthropology, social justice, and transnational
            feminism. Her passion developed when she studied abroad in Morocco from
            August to December of 2019. This experience changed how she viewed international
            affairs, feminism, and marriage. She left Morocco with many questions,
            and looked for answers in this research project.
          </center></p>
          <img src= "assets/uploads/IMG-4923.JPG"/>
          <img src= "assets/uploads/IMG-5749 (1).JPG"/>
          <img src= "assets/uploads/IMG-6599"/>
          <quote-card />
        </div>

                <div class="tile is-ancestor">
                </div>
              </template>

              <template v-slot:sidebar>
                <h3 class="subtitle is-4">
                  Latest Posts
                  <image src="/uploads/IMG-4126.jpg">
                </h3>
                <posts-grid src="/uploads/IMG-4126.jpg" :per-row="1" :number="2" />
              </template>
            </main-section>
          </div>
        </template>
        </div>
      </template>
    </main-section>

</template>
<!--<script>
import QuoteCard from '~/components/cards/QuoteCard'
export default {
  head() {
    return {
      title: `About | ${this.$siteConfig.siteName}`
    }
  },
  components: { QuoteCard }
}
</script> -->
