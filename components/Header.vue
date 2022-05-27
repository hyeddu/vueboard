<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-navbar-brand to="/">DiaryLog</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item to="/">Opne Diary</b-nav-item>
          <b-nav-item to="/Login">Login</b-nav-item>
          <b-nav-item to="/gallery">Images</b-nav-item>
          <b-nav-item to="/boardlist">Practice</b-nav-item>
          <b-nav-item to="/calvue">Calendar</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  nama: "Header",
  data() {
    return {

    }
  }
};
</script>
