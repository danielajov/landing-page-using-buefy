<template>
  <div id="contactForm">
    <div class="columns is-centered">
      <div class="column is-6">
        <div class="box">
          <div class="container">
            <h2 class="title">{{ title }}</h2>
            <section>
              <b-field label="Name">
                <b-input placeholder="Plese enter your name."></b-input>
              </b-field>

              <b-field label="E-mail">
                <b-input
                  type="email"
                  placeholder="Plese enter your e-mail."
                ></b-input>
              </b-field>

              <b-field label="Subject">
                <b-input placeholder="Plese enter a subject."></b-input>
              </b-field>
              <div class="field">
                <label class="" for="content">Message</label>
                <div class="control">
                  <textarea
                    class="input"
                    placeholder="Please enter your message"
                  >
                  </textarea>
                </div>
              </div>
              <b-button type="is-dark" focu>Submit</b-button>
            </section>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contact',
  props: {
    title: String,
  },
};
</script>

<style scoped lang="scss">
#contactForm {
  margin-top: 30px;
  min-height: 100vh;
}
</style>
