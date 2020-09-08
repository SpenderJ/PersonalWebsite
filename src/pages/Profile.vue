<template>
  <div>
    <div class="page-header clear-filter" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image:url('img/rugby.jpg')"
      >
      </parallax>
      <div class="container">
        <div class="photo-container">
          <img src="img/julesprofile.jpg" alt="" />
        </div>
        <h3 class="title">Jules Spender</h3>
        <p class="category">Developer | Data Scientist</p>
        <div class="content">
          <div class="social-description">
            <h2>Rugby<br/>Tennis</h2>
            <p>Sports</p>
          </div>
          <div class="social-description">
            <h2>Data Scientist</h2>
            <p>Currently</p>
          </div>
          <div class="social-description">
            <h2>42</h2>
            <p>Tuition</p>
          </div>
        </div>
      </div>
    </div>
    <div class="section">
      <div class="container">
        <h3 class="title">About me</h3>
        <h5 class="description">
          My name is Jules Spender. I was born in 1998, in Paris. After a Scientific bac, I joined EPITECH. After having validated
          my first year there, I decided to attend 42 "Piscine" in July 2017. I got accepted and joined 42 on november 2017. On september
          2018 I joined WiserSkills to attend a 5 months internship. I then studied 4 months at 42 Silicon Valley exploring data science and advanced
          algorithmic project.<br/>I am now working as a Data Scientist at Engie E&C on a student contract completing my master degree.
          <br>
          I've practiced tennis in competition for 8 years before joining Renault's rugby team in FFSE. Sport addict, I've been sailing
          since my youngest age and since 4 years, during summer, I've been working as a monitor mostly in windsurf. I'm also a graduated
          tennis referee (A1).
        </h5>
      </div>
      <h3 class="title">Contact</h3>
      <h5 class="description">
        I'm mostly looking for a part-time, but I stay open to any offers.
        <br>
        Feel free to contact me
        <br>
        • juspende@student.42.fr
      </h5>
    </div>
  </div>
</template>
<script>
import { Tabs, TabPane } from '@/components';

export default {
  name: 'profile',
  bodyClass: 'profile-page',
  components: {
    Tabs,
    TabPane
  }
};
</script>
<style></style>
