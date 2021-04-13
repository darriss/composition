<template>
  <article
    :class="
      `subscribe-form-wrapper message is-dark subtle-box-shadow ${
        active ? 'active' : ''
      }`
    "
  >
    <div class="message-header">
      <font-awesome-icon
        :icon="active ? 'times' : 'envelope'"
        :aria-label="active ? 'close' : 'open'"
        class="close"
        @click="toggle()"
      />
      <p>{{ header }}</p>
    </div>
    <div class="message-body">
      <news-letter-form />
    </div>
  </article>
</template>
