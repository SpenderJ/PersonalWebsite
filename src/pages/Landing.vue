<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/bg6.jpg')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Jules Spender</h1>
          <div class="text-center">
            <h3>42 Paris Student</h3>
          </div>
          <div class="text-center">
            <a href="https://github.com/SpenderJ" class="btn btn-primary btn-icon btn-round">
              <i class="fab fa-github"></i>
            </a>
            <a href="https://www.linkedin.com/in/jules-spender-927a69135/" class="btn btn-primary btn-icon btn-round">
            <i class="fab fa-linkedin"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 class="title">My projects</h2>
            <h5 class="description">
              Currently I am spending most of my time working on advanced algorithmic project at 42 Paris.
              I'm also working as a Data Scientist at Engie E&C completing my master degree on student work contract.
              I'm interested in any languages and can adapt and learn really fast.
              Some of the last project I made:<br/>
              <br/>- Creation of a mathematical set from scratch without any library to handle parsing or matrix.
              <br/>- Creation of a server and a client to work with the voice recognition library Sphinx in C.
              <br/>- Creation of personal linear regression, logistic regression, and neural networks algorithms in Python.
            </h5>
          </div>
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 class="title">My objectives</h2>
            <h5 class="description">
              In november 2018, I had the chance to join WiserSkills for a 5 months Internship.
              I loved this experience. Having the chance to join this project was a life changer experience for me.<br/>
              After spending 4 months in the Silicon Valley, working with on a wide range of subjects about Computer Science and Data Science.
              I'm now back in Paris completing my master degree on a student contract as a Data Scientist at Engie E&C.
            </h5>
          </div>
        </div>
      </div>
    </div>
    <div class="section section-team text-center">
      <div class="container">
        <h2 class="title">Precedent Reviews</h2>
        <div class="team">
          <div class="row">
              <div class="col-md-4">
              </div>
            <div class="col-md-4">
              <div class="team-player">
                <img
                  src="img/wsk.jpg"
                  alt="Thumbnail Image"
                  class="rounded-circle img-fluid img-raised"
                />
                <h4 class="title">WiserSkills</h4>
                <p class="category text-primary">Intern Fullstack Developer</p>
                <p class="description">
                  Jules was very quickly fully part of the team and took part succesfuly in all tasks he was assigned.
                  He communicates his skills and passion for development very efficiently, and will rapidly fix methodology issues.
                  The whole WiserSkills team thank him for his contribution and wish him
                  all the success in his future professional experiences.
                </p>
                <a href="https://twitter.com/wiserskills?lang=fr" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-twitter"></i
                ></a>
                <a href="https://www.linkedin.com/company/wiserskills1/?originalSubdomain=fr" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-linkedin"></i
                ></a>
                  <a href="https://www.wiserskills.com/" class="btn btn-primary btn-icon btn-round"
                  ><i class="fab fa-google"></i
                  ></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Button, FormGroupInput } from '@/components';
export default {
  name: 'landing',
  bodyClass: 'landing-page',
  components: {
    [Button.name]: Button,
    [FormGroupInput.name]: FormGroupInput
  },
  data() {
    return {
      form: {
        firstName: '',
        email: '',
        message: ''
      }
    };
  }
};
</script>
<style></style>
