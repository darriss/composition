<template>
  <div id="contact-page" class="page-wrapper contact-page content-page">
    <site-hero
      title="Resources"
      subtitle="Example Contact Page"
      image="/uploads/bookMar.jpeg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                Hello!
              </p>
              <p class="subtitle">
                What can I do for you?
              </p>
              <figure class="image is-1by1 ">
                <opti-image
                  :src="require('~/assets/uploads/contact-person.jpg').src"
                  :srcset="
                    require('~/assets/uploads/contact-person.jpg').srcSet
                  "
                />
              </figure>
              <br />
              <div class="content">
                <p>
                  <strong>
                    Edit this page in<code>/pages/contact.vue</code>to fit your
                    needs.
                  </strong>
                </p>
                <p>
                  This form doesn't actually work but would be easy enough to
                  slap an action on to have it post wherever you'd like. Or put
                  the netlify attribute on it and have netlify handle all your
                  form submissions...
                </p>
              </div>
            </article>
          </div>
          <div class="tile is-parent is-8">
            <article class="tile is-child box">
              <h3><center>Resources</center></h3>
              <p>
                Batabyal, Amitrajeet A. "On the likelihood of finding the right partner in an arranged marriage."
                  The Journal of Socio-Economics 30.3 (2001): 273-280.
              </p>
              <p>
                Bedmar, Vicente Llorent, and Verónica Cobano-Delgado Palma. “The Influence of the Socioeducational
                  Environment on Marriage Formation in Morocco.” Journal of Comparative Family Studies, vol. 42, no. 6, 2011, pp. 771–785. JSTOR, www.jstor.org/stable/41604489.
              </p>
              <p>
                Hanafi, Leila. The Legal System of Morocco - Konrad Adenauer Foundation.
                  www.kas.de/documents/265308/265357/Legal+System+of+Morocco.pdf/23060d5a-26e0-64a0-7b8f-8b3640d68865?version=1.0&amp;t=1596788324505.
              </p>
              <p>
                Hoffman, Katherine E. “Berber Law by French Means: Customary Courts in the Moroccan Hinterlands, 1930-1956.” Comparative Studies in
                  Society and History, vol. 52, no. 4, 2010, pp. 851–880. JSTOR, www.jstor.org/stable/40864899.
              </p>
              <p>
                Landinfo. Translated by Office of the Commissioner General for Refugees and Stateless Persons, Norwegian Country of Origin Information
                  Centre, Oslo, Norway, 2017, pp. 1–40, Morocco: Marriage and Divorce – Legal and Cultural Aspects.
              </p>
              <p>
                Sabbe, A., Oulami, H., Zekraoui, W. et al. Determinants of child and forced marriage in Morocco: stakeholder perspectives on health,
                  policies and human rights. BMC Int Health Hum Rights 13, 43 (2013). https://doi.org/10.1186/1472-698X-13-43
              </p>
              <p>
                Sylvia I. Bergh and Daniele Rossi-Doria (2015) Plus ça Change? Observing the Dynamics of Morocco's ‘Arab Spring’ in the High Atlas,
                  Mediterranean Politics, 20:2, 198-216, DOI: 10.1080/13629395.2015.1033900 University of Central ARKANSAS: UCA. (n.d.). Retrieved
                  April 13, 2021, from https://uca.edu/politicalscience/dadm-project/middle-eastnorth-africapersian-gulf-region/francemorocco-1930-1956/
              </p>
              <p>
                Zoglin, Katie. “Morocco's Family Code: Improving Equality for Women.” Human Rights
                  Quarterly, vol. 31, no. 4, 2009, pp. 964–984. JSTOR, www.jstor.org/stable/40389983.
              </p>
            </article>
          </div>
        </div>
      </template>
    </main-section>
  </div>
</template>
