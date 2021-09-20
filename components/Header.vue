<template>
  <b-navbar toggleable="md" type="light" variant="light" class="w-100">
    <b-navbar-brand to="/">
    
      <span class="font-weight-bold">Owen Kempton</span>
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item v-for="(item, index) in menu" :key="index" :href="item.to">
          {{ item.label }}
        </b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {
  data() {
    return {
      menu: [
        { to: "#about", label: "About" },
        { to: "#3DPrintProjects", label: "3D Print Projects" },
        { to: "#contact", label: "Contact" }
      ]
    };
  }
};

</script>


