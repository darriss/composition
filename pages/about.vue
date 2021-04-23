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
            Samantha Darris is from New York City and attends Allegheny College.
            While she has always enjoyed computer science, throughout college she
            grew a passion for cultural anthropology, social justice, and transnational
            feminism. Her passion developed when she studied abroad in Morocco from
            August to December of 2019. This experience changed how she viewed international
            affairs, feminism, and marriage. She left Morocco with many questions,
            and looked for answers in this research project.
          </center></p>

          <quote-card />
        </div>

                <div class="tile is-ancestor">
                  <div class="tile is-parent">
                    <article class="tile is-child box">
                      <p class="title">
                        Cool Stuff We Do
                      </p>
                      <p class="subtitle">
                        Sooo Cool
                      </p>
                      <figure class="image is-1by1">
                        <opti-image width="500" height="500" />
                      </figure>
                    </article>
                  </div>
                  <div class="tile is-parent">
                    <article class="tile is-child box">
                      <p class="title">
                        Other Cool Things
                      </p>
                      <p class="subtitle">
                        Just as cool
                      </p>
                      <figure class="image is-1by1">
                        <opti-image width="500" height="500" />
                      </figure>
                    </article>
                  </div>
                  <div class="tile is-parent">
                    <article class="tile is-child box">
                      <p class="title">
                        All the cool
                      </p>
                      <p class="subtitle">
                        that is all
                      </p>
                      <figure class="image is-1by1">
                        <opti-image width="500" height="500" />
                      </figure>
                    </article>
                  </div>
                </div>
              </template>

              <template v-slot:sidebar>
                <h3 class="subtitle is-4">
                  Latest Posts
                </h3>
                <posts-grid :per-row="1" :number="2" />
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
