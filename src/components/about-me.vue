<template>
  <div>
    <div class="container-fluid bg-light py-5">
      <div class="jumbotron jumbotron-fluid">
        <div class="container p-5">
          <span class="ls bg-orange">About Me</span>
          <div class="row py-5">
            <div class="col-6">
              <span class="display-4"
                >I'm the kind of person who isn't afraid of challenges.</span
              >
              <br />
              <blockquote class="blockquote py-5">
                “I'm an experienced software engineer who constantly seeks out
                innovative solutions to everyday problems. In my 2+ years in
                this industry, I've honed my analytical thinking and
                collaboration skills, and I love working with a team.
              </blockquote>
              <div class="row">
                <button class="ls btn-custom">DOWNLOAD CV</button>
              </div>
            </div>

            <div class="col-6">
              <div class="p-4 ml-0">
                <img src="../assets/me.webp" width="400" alt="me" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>
