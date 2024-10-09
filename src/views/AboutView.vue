<template>
  <header style=" background-color: white;">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#"><img src="@/assets/w5mrk.svg" alt="" class="me-2" /></a>
        <button class="btn btn-light ms-5"><img src="@/assets/w5search.svg" alt="" /></button>
        <button class="btn btn-light me-3"><img src="@/assets/w5oooo.svg" alt="" /></button>
      
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
          <div class="d-flex ms-auto align-items-center">
            <button class="btn btn-light me-2">
              <img src="@/assets/w5moon.svg" alt="Dark Mode" />
            </button>
            <button class="btn btn-light me-2">
              <img src="@/assets/w5nat.svg" alt="Notifications" />
            </button>
            <button class="btn btn-light me-2">
              <img src="@/assets/w5uk.svg" alt="Language" />
            </button>
            <div class="dropdown">
              <button
                class="btn btn-light dropdown-toggle"
                type="button"
                id="userDropdown"
                data-bs-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >
                <img src="@/assets/w5Mathew.svg" alt="User" class="rounded-circle" width="30" />
              </button>
              <ul class="dropdown-menu" aria-labelledby="userDropdown">
                <li><a class="dropdown-item" href="#">Profile</a></li>
                <li><a class="dropdown-item" href="#">Settings</a></li>
                <li><a class="dropdown-item" href="#">Logout</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </header>

  <!-- Sidebar -->
  <nav id="sidebar" class="col-md-3 col-lg-2 d-md-block bg-light sidebar" style="background-color: white;">
    <div class="position-sticky">
      <ul class="nav flex-column">
          <li class="nav-item">
  <a class="nav-link bg-primary text-light" href="#" style="font-size: 15px; text-align: left; border-radius: 18px;">
    <img src="@/assets/w5dash.svg" class="me-2" /> Dashboard</a>
</li>

<li class="nav-item">
  <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
    <img src="@/assets/w5order.svg" alt="Orders" class="me-2" /> Orders</a>
</li>


            <li class="nav-item">
          <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
            <img src="@/assets/w5pas.svg" alt="Passengers" class="me-2" /> Passengers</a></li>

            <li class="nav-item">
          <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
            <img src="@/assets/w5cap.svg" alt="Captains" class="me-2" /> Captains</a></li>

            <li class="nav-item">
          <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
            <img src="@/assets/w5cat.svg" alt="Categories" class="me-2" /> Categories</a></li>
<hr>
            <li class="nav-item">
          <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
            <img src="@/assets/w5set.svg" alt="Settlement" class="me-2" /> Settlement</a></li>
<hr>
            <li class="nav-item">
          <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
            <img src="@/assets/w5con.svg" alt="Contact" class="me-2" /> Contact</a></li>

            <li class="nav-item">
          <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
            <img src="@/assets/w5rev.svg" alt="Reviews" class="me-2" /> Reviews</a></li>
<hr>
            <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle text-black"  href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" 
      style="text-align: left;"><img src="@/assets/w5per.svg" alt="Permissions" class="me-2" />Permissions</a></li>

            <li class="nav-item">
          <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
            <img src="@/assets/w5tra.svg" alt="Translation" class="me-2" /> Translation</a></li>

            <li class="nav-item">
          <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
            <img src="@/assets/w5edu.svg" alt="Education Video" class="me-2" /> Education Video</a></li>

            <li class="nav-item">
          <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
            <img src="@/assets/w5settings.svg" alt="Settings" class="me-2" /> Settings</a></li>

            <li class="nav-item">
          <a class="nav-link text-dark" href="#" style="font-size: 15px; text-align: left;">
            <img src="@/assets/w5cont.svg" alt="Content" class="me-2" /> Content</a></li>

      </ul>
    </div>
  </nav>
   













   
</template>

<script>
export default {
  name: "NavbarComponent",
};

</script>

<style scoped>
body {
  background-color: white; /* Background for the entire body */
}

.navbar {
  padding: 1rem;
}

.navbar-brand {
  font-size: 1.5rem;
}

.sidebar {
  list-style-type: none;
  padding: 0;
}

.sidebar .nav-item {
  margin-bottom: 10px;
}

.dropdown-menu {
  right: 0;
  left: auto;
}

.left-section,
.right-section {
  display: flex;
  align-items:start;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.row {
  background-color: white; /* White background for the content row */
}
</style>
