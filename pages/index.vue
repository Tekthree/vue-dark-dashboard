<template>
  <div class="app">
    <div class="app-header-logo">
      <div class="logo">
        <span class="logo-icon">
          <img src="https://assets.codepen.io/285131/almeria-logo.svg" alt="" />
        </span>
        <h1 class="logo-title">
          <span>Almeria</span>
          <span>NeoBank</span>
        </h1>
      </div>
    </div>
    <div class="app-header-navigation">
      <div class="tabs">
        <a href="#">Overview</a>
        <a href="#">Payments</a>
        <a href="#">Cards</a>
        <a href="#">Account</a>
        <a href="#">System</a>
        <a href="#">Business</a>
      </div>
    </div>

    <div class="app-header-actions">
      <button class="user-profile">
        <span>Matheo Paterson</span>
        <span
          ><img
            src="https://assets.codepen.io/285131/almeria-avatar.jpeg"
            alt=""
        /></span>
      </button>
      <div class="app-header-actions-buttons">
        <button class="icon-button large">
          <ph-magnifying-glass/>
        </button>
        <button class="icon-button large">
					<ph-bell/>
				</button>
        
      </div>
    </div>




  </div>
</template>

<script>
import { PhMagnifyingGlass, PhBell } from "phosphor-vue";
export default {
    name: "App",
    components: {
      PhMagnifyingGlass,
      PhBell,
    }
  };
</script>

<style>
@import "../reset.css";
@import "../variables.css";

body {
  line-height: 1.5;
  min-height: 100vh;
  font-family: purista-web, sans-serif;
  font-weight: 400;
  font-style: normal;
  background-color: var(--c-gray-900);
  color: var(--c-text-primary);
  display: flex;
  padding-top: 3vw;
  padding-bottom: 3vw;
  justify-content: center;
}

.responsive-wrapper {
	width: 90%;
	max-width: 1600px;
	margin-left: auto;
	margin-right: auto;
}

.app {
	min-height: 80vh;
	width: 95%;
	max-width: 1600px;
	background-color: var(--c-gray-800);
	padding: 2vw 4vw 6vw;
	display: flex;
	flex-direction: column;
}





h3 {
  font-family: purista-web, sans-serif;
  font-weight: 400;
  font-style: normal;
}
</style>
