<template>
  <div class="menu">
    <div class="home-search">
      <label class="home-label"><img alt="home img" src="../assets/home.png" class="icon-img">Home</label>
      <label class="search-label"><img alt="search img" src="../assets/search.png" class="icon-img">Search</label>
    </div>
    <div class="library">
      <label class="library-label"><img alt="library img" src="../assets/library.png" class="icon-img">Your Library</label>
      <div class="playlist">
        <h3>
          Create your first playlist
        </h3>
        <h5>
          It's easy, we'll help you
        </h5>
        <button>Create playlist</button>
      </div>
      <div class="podcast">
        <h3>
          Let's find some podcasts to follow
        </h3>
      </div>
      <div class="info">
        <u>Legal</u>
        <u>Privacy Center</u>
        <u>Privacy Policy</u>
        <u>Cookie Settings</u>
        <u>About Ads</u>
        <u>Accessibility</u>
        <u>Cookies</u>
      </div>
      <button class="lingua">
        <img alt="globe" src="../assets/globe.png" class="icon-img">
        <select>
          <option value="english">English</option>
          <option value="italiano">Italiano</option>
        </select>
      </button>
    </div>
  </div>
  <div class="main">
    <div class="up-rigth">
      <div class="arrow">
        <button>
          <img alt="arrow left" src="../assets/indietro.png" class="indietro">
        </button>
        <button>
          <img alt="arrow rigth" src="../assets/avanti.png" class="indietro">
        </button>
      </div>
      <div class="signup-login">
        <button class="signup">
          SIGNUP
        </button>
        <button class="login">
          LOGIN
        </button>
      </div>
    </div>
    <div class="focus">
        <h2>
          Focus
        </h2>
        <div class="canzoni">
          <div class="card-brano">
            <img alt="img brano" src="../assets/peaceful-piano.png">
            <h3>
              Peaceful Piano
            </h3>
            <p>
              peaceful paino to help you slow down, breath...
            </p>
          </div>
          <div class="card-brano">
            <img alt="img brano" src="../assets/deep-focus.png">
            <h3>
              Deep Focus
            </h3>
            <p>
              Keep calm and focus with ambient and post...
            </p>
          </div>
          <div class="card-brano">
            <img alt="img brano" src="../assets/instrumental-study.png">
            <h3>
              Instrumental Study
            </h3>
            <p>
              Focus with soft study music in the...
            </p>
          </div>
          <div class="card-brano">
            <img alt="img brano" src="../assets/focus-flow.png">
            <h3>
              Focus Flow
            </h3>
            <p>
              Uptempo instrumental hip hop beats.
            </p>
          </div>
          <div class="card-brano">
            <img alt="img brano" src="../assets/beats-to-think-to.png">
            <h3>
              Beats to think to
            </h3>
            <p>
              Focus with deep techno and tech house.
            </p>
          </div>
          <div class="card-brano">
            <img alt="img brano" src="../assets/tth.png">
            <h3>
              Today's Top Hits
            </h3>
            <p>
              Travis Scott is on top of the hootest 50!
            </p>
          </div>
          <div class="card-brano">
            <img alt="img brano" src="../assets/rapcaviar.png">
            <h3>
              RapCaviar
            </h3>
            <p>
              New music from Lil Tjay, Quavo and JT of...
            </p>
          </div>
          <div class="card-brano">
            <img alt="img brano" src="../assets/all2010.png">
            <h3>
              All Out 2010s
            </h3>
            <p>
              The biggest songs of 2010s.
            </p>
          </div>
          <div class="card-brano">
            <img alt="img brano" src="../assets/allrock.png">
            <h3>
              Rock Classics
            </h3>
            <p>
              Rock legends & epic songs that continue t...
            </p>
          </div>
          <div class="card-brano">
            <img alt="img brano" src="../assets/chill.png">
            <h3>
              Chill Hits
            </h3>
            <p>
              Kick back to the best new and recent chill...
            </p>
          </div>
          <div class="card-brano">
            <img alt="img brano" src="../assets/rapcaviar.png">
            <h3>
              RapCaviar
            </h3>
            <p>
              New music from Lil Tjay, Quavo and JT of...
            </p>
          </div>
        </div>
      </div>
  </div>
  <div class="bottom-bar">
    <p class="first">
      PREVIEW OF SPOTIFY
    </p>
    <p class="second">
      Sign up to get unlimited songs and podcasts with occasional ads. No credit card needed
    </p>
  </div>
  <botton class="for-free">SIGNUP FOR FREE</botton>
</template>

<script>
import '../assets/styles/components/homepage.scss'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>