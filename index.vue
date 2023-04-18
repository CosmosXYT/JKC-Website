<template>
  <main class="home-container">
    <section class="home-hero">
      <div class="home-menu">
        <div id="mobile-menu" class="home-mobile-navigation">
          <img
            alt="pastedImage"
            src="/playground_assets/pastedimage-no9b-1500h.png"
            class="home-logo"
          />
          <div class="home-links">
            <span class="Link">Solutions</span>
            <span class="Link">How it works</span>
            <span class="Link">Prices</span>
          </div>
          <div id="close-mobile-menu" class="home-close-mobile-menu">
            <svg viewBox="0 0 804.5714285714286 1024" class="home-icon">
              <path
                d="M741.714 755.429c0 14.286-5.714 28.571-16 38.857l-77.714 77.714c-10.286 10.286-24.571 16-38.857 16s-28.571-5.714-38.857-16l-168-168-168 168c-10.286 10.286-24.571 16-38.857 16s-28.571-5.714-38.857-16l-77.714-77.714c-10.286-10.286-16-24.571-16-38.857s5.714-28.571 16-38.857l168-168-168-168c-10.286-10.286-16-24.571-16-38.857s5.714-28.571 16-38.857l77.714-77.714c10.286-10.286 24.571-16 38.857-16s28.571 5.714 38.857 16l168 168 168-168c10.286-10.286 24.571-16 38.857-16s28.571 5.714 38.857 16l77.714 77.714c10.286 10.286 16 24.571 16 38.857s-5.714 28.571-16 38.857l-168 168 168 168c10.286 10.286 16 24.571 16 38.857z"
              ></path>
            </svg>
          </div>
        </div>
        <div class="home-desktop-navigation">
          <nav class="home-centered">
            <div class="home-left">
              <img
                alt="pastedImage"
                src="/playground_assets/1677788737087159-200h.png"
                class="home-logo1"
              />
              <div class="home-links1">
                <span class="Link">Why?</span>
                <span class="Link">Don&apos;t Click.</span>
                <span class="Link">We will Take Your Money.</span>
              </div>
            </div>
            <div class="home-right">
              <span class="home-sign-in Link">Sign in</span>
              <div class="home-get-started">
                <span class="home-text06">Get started</span>
              </div>
              <div id="open-mobile-menu" class="home-burger-menu">
                <img
                  alt="pastedImage"
                  src="/playground_assets/pastedimage-yxbd.svg"
                  class="home-mobile-menu-button"
                />
              </div>
            </div>
          </nav>
        </div>
        <div>
          <DangerousHTML
            html="<script>
  /*
  Mobile menu - Code Embed
  */
  
  // Mobile menu
  const mobileMenu = document.querySelector('#mobile-menu')
  
  // Buttons
  const closeButton = document.querySelector('#close-mobile-menu')
  const openButton = document.querySelector('#open-mobile-menu')
  
  // On openButton click, set the mobileMenu position left to -100vw
  openButton.addEventListener('click', function() {
      mobileMenu.style.transform = 'translateX(0%)'
  })
  
  // On closeButton click, set the mobileMenu position to 0vw
  closeButton.addEventListener('click', function() {
      mobileMenu.style.transform = 'translateX(100%)'
  })
  </script>"
          ></DangerousHTML>
        </div>
      </div>
      <header class="home-header">
        <h1 class="home-text07">JK Creations</h1>
        <div class="home-get-started1">
          <span class="home-text08">Don&apos;t Get Started!</span>
        </div>
      </header>
    </section>
    <section class="home-action-bar">
      <div>
        <DangerousHTML
          html="<!DOCTYPE html>
  <html>
  <head>
  	<title>Video Button</title>
  	<style>
  		.video-button {
  		  position: relative;
  		  display: inline-block;
  		  border-radius: 20px;
  		  overflow: hidden;
  		  width: 300px;
  		  height: 200px;
  		}
  
  		.video-cover {
  		  position: absolute;
  		  top: 0;
  		  left: 0;
  		  width: 100%;
  		  height: 100%;
  		  background-image: url('https://img.youtube.com/vi/1SNqRlxxQKA/hqdefault.jpg');
  		  background-size: cover;
  		  opacity: 0.8;
  		  transition: opacity 0.3s ease-in-out;
  		}
  
  		.watch-video-button {
  		  position: absolute;
  		  bottom: 20px;
  		  left: 50%;
  		  transform: translateX(-50%);
  		  padding: 16px 40px;
  		  font-size: 18px;
  		  font-weight: bold;
  		  font-family: Arial, sans-serif;
  		  text-transform: uppercase;
  		  color: #fff;
  		  background-color: #5d3aff;
  		  border: none;
  		  border-radius: 20px;
  		  box-shadow: 0 5px 15px rgba(93, 58, 255, 0.5);
  		  cursor: pointer;
  		  transition: transform 0.3s ease-in-out;
  		}
  
  		.video-button:hover .watch-video-button {
  		  transform: scale(1.1);
  		}
  
  		.video-button:hover .video-cover {
  		  opacity: 0;
  		}
  	</style>
  </head>
  <body>
  	<div class='video-button'>
  	  <div class='video-cover'></div>
  	  <a href='https://www.youtube.com/watch?v=1SNqRlxxQKA' target='_blank' class='watch-video-button'>Watch Video</a>
  	</div>
  
  	<script>
  		const videoCover = document.querySelector('.video-cover');
  		videoCover.style.backgroundImage = `url('https://img.youtube.com/vi/1SNqRlxxQKA/hqdefault.jpg')`;
  	</script>
  </body>
  </html>
  "
        ></DangerousHTML>
      </div>
      <div class="home-action">
        <div class="home-heading">
          <span class="home-text09 title">Check out our Podcasts!</span>
          <span class="home-text10">
            This button will lead you to our Podcasts section on our YouTube
            Channel
          </span>
          <div class="home-get-started2 template-button">
            <span class="home-text11">
              <span>Check it out</span>
              <br />
            </span>
          </div>
        </div>
        <div class="home-images">
          <img
            alt="image"
            src="/playground_assets/1677793443716774-1500w.png"
            class="home-image"
          />
        </div>
      </div>
      <div>
        <DangerousHTML
          html="<!DOCTYPE html>
  <html>
  <head>
  	<title>Video Button</title>
  	<style>
  		.video-button {
  		  position: relative;
  		  display: inline-block;
  		  border-radius: 20px;
  		  overflow: hidden;
  		  width: 300px;
  		  height: 200px;
  		}
  
  		.video-cover {
  		  position: absolute;
  		  top: 0;
  		  left: 0;
  		  width: 100%;
  		  height: 100%;
  		  background-image: url('https://img.youtube.com/vi/1SNqRlxxQKA/hqdefault.jpg');
  		  background-size: cover;
  		  opacity: 0.8;
  		  transition: opacity 0.3s ease-in-out;
  		}
  
  		.watch-video-button {
  		  position: absolute;
  		  bottom: 20px;
  		  left: 50%;
  		  transform: translateX(-50%);
  		  padding: 16px 40px;
  		  font-size: 18px;
  		  font-weight: bold;
  		  text-transform: uppercase;
  		  color: #fff;
  		  background-color: #ff4d4d;
  		  border: none;
  		  border-radius: 20px;
  		  box-shadow: 0 5px 15px rgba(255, 77, 77, 0.5);
  		  cursor: pointer;
  		  transition: transform 0.3s ease-in-out;
  		}
  
  		.video-button:hover .watch-video-button {
  		  transform: scale(1.1);
  		}
  
  		.video-button:hover .video-cover {
  		  opacity: 0;
  		}
  	</style>
  </head>
  <body>
  	<div class='video-button'>
  	  <div class='video-cover'></div>
  	  <a href='https://www.youtube.com/watch?v=1SNqRlxxQKA' target='_blank' class='watch-video-button'>Watch Video</a>
  	</div>
  
  	<script>
  		const videoCover = document.querySelector('.video-cover');
  		videoCover.style.backgroundImage = `url('https://img.youtube.com/vi/1SNqRlxxQKA/hqdefault.jpg')`;
  	</script>
  </body>
  </html>
  "
        ></DangerousHTML>
      </div>
    </section>
    <section class="home-quote-container">
      <div class="home-quote">
        <span class="home-message">
          “Scale your content, grew lorem ipsum dolor sit amet, consectetur
          adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
          magna aliqua.”
        </span>
        <div class="home-author">
          <span class="home-quote1">
            <span class="home-text14">
              — 
              <span v-html="raws3t9"></span>
            </span>
            <span class="home-text15">J</span>
            <span class="home-text16">
              ust
              <span v-html="rawz0tm"></span>
            </span>
            <span class="home-text17">K</span>
            <span class="home-text18">
              idding
              <span v-html="rawd98y"></span>
            </span>
            <span class="home-text19">C</span>
            <span class="home-text20">reations</span>
          </span>
        </div>
      </div>
    </section>
    <section class="home-banners"></section>
    <section class="home-integrations">
      <div class="home-centered-container">
        <div class="home-heading1">
          <span class="title">
            <span>Our socials:</span>
            <br />
            <span>(not functional yet)</span>
            <br />
          </span>
        </div>
        <div class="home-pills-container">
          <div class="home-pills">
            <div class="home-container1">
              <you-tube></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/group%201012-200h.png"
              ></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/layer1-200h.png"
              ></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/group-200h.png"
              ></you-tube>
            </div>
            <div class="home-container2">
              <you-tube
                pastedImage_src="/playground_assets/pinterest%20logo-200h.png"
              ></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/group%201014-200h.png"
              ></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/group%201015-200h.png"
              ></you-tube>
              <you-tube
                pastedImage_src="/playground_assets/group%201017-200h.png"
              ></you-tube>
            </div>
          </div>
        </div>
      </div>
    </section>
    <footer class="home-footer">
      <div class="home-top">
        <div class="home-left1">
          <span class="home-text26">Subscribe to our newsletter</span>
          <div class="home-subscription">
            <input
              type="email"
              placeholder="Enter your email"
              class="home-textinput input"
            />
            <div class="home-subscribe">
              <span class="home-text27">Subscribe</span>
            </div>
          </div>
          <span class="home-text28">
            We don&apos;t feel like setting up this part, so it doesn&apos;t
            actually work. But you can still give us your email if you&apos;d
            like!
          </span>
          <div class="home-contact">
            <span class="home-text29">Contact</span>
            <a href="mailto:use@active-app.com?subject=Support" class="home-link">
              You can&apos;t contact us.
            </a>
          </div>
        </div>
      </div>
      <div class="home-bottom">
        <img
          alt="pastedImage"
          src="/playground_assets/1677788737087159-200h.png"
          class="home-branding"
        />
        <span class="home-text30">Copyright © Active - 2022</span>
      </div>
    </footer>
  </main>
</template>

<script>
import DangerousHTML from 'dangerous-html/dist/vue/lib.mjs'

import YouTube from '../components/you-tube'

export default {
  name: 'Home',
  components: {
    DangerousHTML,
    YouTube,
  },
  data() {
    return {
      raws3t9: ' ',
      rawz0tm: ' ',
      rawd98y: ' ',
    }
  },
  head: {
    title: 'JKC Website',
    meta: [
      {
        property: 'og:title',
        content: 'JKC Website',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  overflow-x: hidden;
  flex-direction: column;
}
.home-hero {
  width: 100%;
  height: 527px;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-oneandhalfunits);
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: column;
  background-color: #5228F5;
}
.home-menu {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-mobile-navigation {
  top: 0px;
  flex: 0 0 auto;
  left: 0px;
  width: 100vw;
  height: 100vh;
  display: flex;
  z-index: 150;
  position: fixed;
  transform: translateX(100%);
  transition: transform 0.3s;
  align-items: flex-start;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  background-color: var(--dl-color-gray-white);
}
.home-logo {
  width: 64px;
}
.home-links {
  gap: var(--dl-space-space-twounits);
  display: flex;
  margin-top: var(--dl-space-space-twounits);
  align-items: flex-start;
  flex-direction: column;
}
.home-close-mobile-menu {
  top: var(--dl-space-space-oneandhalfunits);
  right: var(--dl-space-space-oneandhalfunits);
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-icon {
  width: 24px;
  height: 24px;
  display: flex;
}
.home-desktop-navigation {
  width: 100%;
  display: flex;
  margin-top: var(--dl-space-space-oneandhalfunits);
  align-items: center;
  flex-direction: column;
}
.home-centered {
  width: 100%;
  display: flex;
  max-width: 1200px;
  box-sizing: initial;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: 50px;
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: row;
  justify-content: space-between;
  background-color: #ffffff;
}
.home-left {
  height: 43px;
  display: flex;
  position: relative;
  align-items: center;
  padding-top: 38px;
  flex-direction: row;
  padding-bottom: 38px;
}
.home-logo1 {
  width: 105px;
  margin-left: var(--dl-space-space-halfunit);
}
.home-links1 {
  display: flex;
  align-items: center;
  margin-left: 33px;
  flex-direction: row;
}
.home-right {
  height: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-oneandhalfunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-sign-in {
  margin-right: 20px;
}
.home-get-started {
  cursor: pointer;
  display: flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: 56px;
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  background-color: #000000;
}
.home-get-started:hover {
  background-color: #5228F5;
}
.home-text06 {
  color: #ffffff;
  font-style: normal;
  font-weight: 600;
}
.home-burger-menu {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-mobile-menu-button {
  width: 40px;
  height: 40px;
  display: none;
}
.home-header {
  display: flex;
  margin-top: 140px;
  align-items: center;
  flex-direction: column;
}
.home-text07 {
  color: rgb(255, 255, 255);
  font-size: 72px;
  font-style: normal;
  text-align: center;
  font-weight: 700;
  line-height: 80px;
}
.home-get-started1 {
  color: white;
  cursor: pointer;
  display: flex;
  margin-top: 40px;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  border-radius: 56px;
  padding-right: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  background-color: #000000;
}
.home-get-started1:hover {
  color: black;
  background-color: #ffffff;
}
.home-text08 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
}
.home-action-bar {
  width: 100%;
  display: flex;
  padding: 120px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-action {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: flex-end;
  border-radius: 50px;
  flex-direction: row;
  justify-content: space-between;
  background-color: #5228F5;
}
.home-heading {
  width: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-sevenunits);
  padding-left: var(--dl-space-space-sevenunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sevenunits);
}
.home-text09 {
  color: var(--dl-color-gray-white);
  text-align: left;
}
.home-text10 {
  color: rgb(238, 233, 254);
  line-height: 24px;
  margin-bottom: var(--dl-space-space-threeunits);
}
.home-get-started2 {
  margin-bottom: 0px;
}
.home-text11 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
}
.home-images {
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-image {
  width: 521px;
  height: 597px;
  align-self: center;
  object-fit: cover;
  user-select: none;
}
.home-quote-container {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 160px;
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: column;
  padding-bottom: 160px;
  justify-content: center;
  background-color: #000000;
}
.home-quote {
  width: 100%;
  display: flex;
  max-width: 1200px;
  flex-direction: column;
  justify-content: center;
}
.home-message {
  color: rgb(255, 255, 255);
  font-size: 40px;
  max-width: 800px;
  line-height: 52px;
}
.home-author {
  width: 800px;
  display: flex;
  margin-top: var(--dl-space-space-oneandhalfunits);
  align-items: center;
  flex-direction: row;
}
.home-quote1 {
  color: rgb(151, 126, 249);
  width: 100%;
  max-width: 800px;
  font-weight: 600;
  margin-left: var(--dl-space-space-unit);
}
.home-text14 {
  font-style: normal;
}
.home-text15 {
  font-weight: 800;
}
.home-text16 {
  font-style: normal;
}
.home-text17 {
  font-weight: 800;
}
.home-text18 {
  font-style: normal;
}
.home-text19 {
  font-weight: 800;
}
.home-text20 {
  font-style: normal;
}
.home-banners {
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-integrations {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-sevenunits);
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: #EFF0F2;
}
.home-centered-container {
  width: 100%;
  display: flex;
  max-width: 1200px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-heading1 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-pills-container {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-pills {
  width: 100%;
  display: flex;
  grid-gap: var(--dl-space-space-twounits);
  position: relative;
  flex-wrap: wrap;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.home-container1 {
  gap: var(--dl-space-space-twounits);
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: center;
}
.home-container2 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 896px;
  display: flex;
  flex-wrap: wrap;
  align-self: center;
  margin-left: var(--dl-space-space-fiveunits);
  flex-direction: row;
  justify-content: center;
}
.home-footer {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-sevenunits);
  padding-left: var(--dl-space-space-sevenunits);
  padding-right: var(--dl-space-space-sevenunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sevenunits);
  background-color: #000000;
}
.home-top {
  width: 100%;
  display: flex;
  max-width: 1200px;
  border-color: #3B3B3B;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: space-between;
  border-bottom-width: 1px;
}
.home-left1 {
  width: 33%;
  display: flex;
  align-items: flex-start;
  margin-right: var(--dl-space-space-twounits);
  flex-direction: column;
}
.home-text26 {
  color: rgb(255, 255, 255);
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-subscription {
  width: 100%;
  height: 66px;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: 50px;
  margin-bottom: var(--dl-space-space-unit);
  padding-right: var(--dl-space-space-halfunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-halfunit);
  justify-content: space-between;
  background-color: #ffffff;
}
.home-textinput {
  width: 60%;
  outline: none;
  font-size: 14px;
  border-width: 0px;
}
.home-subscribe {
  cursor: pointer;
  display: flex;
  transition: 0.3s;
  align-items: center;
  padding-top: 16px;
  padding-left: 32px;
  border-radius: 56px;
  padding-right: 32px;
  flex-direction: row;
  padding-bottom: 16px;
  justify-content: flex-start;
  background-color: #5228F5;
}
.home-subscribe:hover {
  background-color: #000;
}
.home-text27 {
  color: #ffffff;
  font-size: 14px;
  font-style: normal;
  font-weight: 600;
}
.home-text28 {
  color: rgb(104, 104, 104);
  font-size: 14px;
}
.home-contact {
  display: flex;
  margin-top: 52px;
  align-items: flex-start;
  flex-direction: column;
}
.home-text29 {
  color: rgb(255, 255, 255);
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  margin-bottom: var(--dl-space-space-unit);
}
.home-link {
  color: rgb(196, 196, 196);
  font-size: 14px;
  text-decoration: underline;
}
.home-bottom {
  width: 100%;
  height: 128px;
  display: flex;
  max-width: 1200px;
  margin-top: var(--dl-space-space-threeunits);
  align-items: flex-start;
  user-select: none;
  flex-direction: column;
}
.home-branding {
  width: var(--dl-size-size-large);
  filter: invert(100%) sepia(0%) saturate(0%) hue-rotate(93deg) brightness(103%) contrast(103%);;
  margin-bottom: var(--dl-space-space-unit);
}
.home-text30 {
  color: rgb(104, 104, 104);
  font-size: 14px;
  line-height: 30px;
}
@media(max-width: 991px) {
  .home-hero {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-close-mobile-menu {
    align-items: center;
    justify-content: center;
  }
  .home-desktop-navigation {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-centered {
    height: 60px;
    padding-left: 10px;
    padding-right: 10px;
  }
  .home-left {
    margin-left: var(--dl-space-space-halfunit);
  }
  .home-logo1 {
    width: 64px;
  }
  .home-links1 {
    display: none;
  }
  .home-sign-in {
    display: none;
  }
  .home-get-started {
    display: none;
  }
  .home-mobile-menu-button {
    display: flex;
  }
  .home-header {
    width: 100%;
    max-width: 1200px;
  }
  .home-action {
    flex-direction: column;
  }
  .home-heading {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
    padding-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-text09 {
    font-size: 36px;
    line-height: 36px;
  }
  .home-quote-container {
    padding-top: var(--dl-space-space-sevenunits);
    padding-bottom: var(--dl-space-space-sevenunits);
  }
  .home-message {
    width: 100%;
    max-width: 800px;
  }
  .home-author {
    width: 100%;
    max-width: 800px;
  }
  .home-container2 {
    margin-left: 0px;
  }
  .home-footer {
    padding: var(--dl-space-space-sixunits);
  }
  .home-top {
    flex-direction: column;
  }
  .home-left1 {
    width: 100%;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-threeunits);
  }
  .home-text28 {
    color: rgb(104, 104, 104);
    font-size: 14px;
  }
  .home-text29 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-link {
    text-decoration: underline none;
  }
  .home-branding {
    width: var(--dl-size-size-medium);
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .home-text30 {
    font-size: 12px;
    line-height: 25px;
    margin-bottom: 0px;
  }
}
@media(max-width: 767px) {
  .home-hero {
    height: 620px;
    position: relative;
    padding-bottom: 180px;
    background-color: var(--dl-color-template-blue-bg);
  }
  .home-desktop-navigation {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-centered {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-left {
    margin-left: var(--dl-space-space-unit);
  }
  .home-right {
    margin-right: var(--dl-space-space-unit);
  }
  .home-sign-in {
    display: none;
  }
  .home-get-started {
    display: none;
  }
  .home-header {
    height: 100%;
    margin-top: var(--dl-space-space-fourunits);
    justify-content: center;
  }
  .home-text07 {
    color: rgb(255, 255, 255);
    font-size: 32px;
    font-style: normal;
    font-weight: 700;
    line-height: 36px;
  }
  .home-get-started1 {
    margin-top: var(--dl-space-space-twounits);
  }
  .home-action-bar {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-fourunits);
    padding-right: var(--dl-space-space-fourunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-action {
    align-items: center;
  }
  .home-heading {
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-text09 {
    font-size: 28px;
    text-align: left;
  }
  .home-text11 {
    color: var(--dl-color-gray-white);
    font-size: 18px;
    font-style: normal;
    font-weight: 600;
  }
  .home-images {
    justify-content: center;
  }
  .home-image {
    width: 100%;
  }
  .home-quote-container {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-message {
    font-size: 24px;
    line-height: 31px;
  }
  .home-author {
    width: 100%;
  }
  .home-quote1 {
    font-size: 14px;
    max-width: 800px;
  }
  .home-integrations {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-pills {
    margin-bottom: var(--dl-space-space-threeunits);
  }
  .home-footer {
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
}
@media(max-width: 479px) {
  .home-hero {
    padding-bottom: 160px;
  }
  .home-logo {
    margin-left: 0px;
  }
  .home-icon {
    align-items: center;
    justify-content: center;
  }
  .home-get-started1 {
    width: 100%;
  }
  .home-action-bar {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-footer {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-subscription {
    padding-top: var(--dl-space-space-halfunit);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-halfunit);
    padding-bottom: var(--dl-space-space-halfunit);
  }
}
</style>
