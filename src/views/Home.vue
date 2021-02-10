<template>
  <div class="view">
    <section class="section">
      <h1 class="title">Hi! Welcome to the CatsAMillion site!</h1>
      <h2 class="subtitle">
         Here you will find polls for the
        community and stream information. More to come soon!
      </h2>
    </section>
    <section>
      <div class="two-column">
      <div>
        <a
          href="https://www.instagram.com/therealcatsamillion/"
          target="_blank"
          rel="noopener noreferrer nofollow"
        >
          <span class="icon-text icon-container">
            <img
              class="icon is-large"
              :src="instagramIcon"
              alternate="instagram icon"
            />
            <span>Check me out on Instagram!</span>
          </span>
        </a>
        <a
          href="https://www.twitch.tv/catsamillion"
          target="_blank"
          rel="noopener noreferrer nofollow"
        >
        </a>
        <a
          href="https://www.twitch.tv/catsamillion"
          target="_blank"
          rel="noopener noreferrer nofollow"
        >
          <span class="icon-text icon-container">
            <img
              class="icon is-large"
              :src="twitchIcon"
              alternate="twitch icon"
            />
            <span>I stream on Twitch sometimes.</span>
          </span>
        </a>
      </div>
      <div>
        <a
          href="https://www.youtube.com/channel/UCWU6dL29JFW5MHAjSBPczZA"
          target="_blank"
          rel="noopener noreferrer nofollow"
        >
          <span class="icon-text icon-container">
            <img
              class="icon is-large"
              :src="youtubeIcon"
              alternate="youtube icon"
            />
            <span>There's nothing on my YouTube...</span>
          </span>
        </a>
        <a
          href="https://twitter.com/ImCatsAMillion"
          target="_blank"
          rel="noopener noreferrer nofollow"
        >
          <span class="icon-text icon-container">
            <img
              class="icon is-large"
              :src="twitterIcon"
              alternate="twitter icon"
            />
            <span>Follow me!</span>
          </span>
        </a>
      </div>
      </div>
      <div class="vertical-center vertical-spacing"> 
        <div class="icon-attributes">
          <span class="icon-attributes-text">Icons made by <a href="http s://www.flaticon.com/authors/pixel-perfect" title="Pixel perfect">Pixel perfect</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></span>
          <span class="icon-attributes-text">Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></span>
        </div>
        <div class="vertical-spacing vertical-center">
                  <a
          href="https://github.com/CatsAMillion"
          target="_blank"
          rel="noopener noreferrer nofollow"
        >
          <span class="icon-text icon-container">
            <img
              class="icon is-large"
              :src="githubIcon"
              alternate="github icon"
            />
            <span>Fresh account for this channel!</span>
          </span>
        </a>
          <a href="https://www.codewars.com/users/CatsAMillion" target="_blank" rel="noopener noreferrer nofollow" ><img src="https://www.codewars.com/users/CatsAMillion/badges/large" alt="codewars badge" /></a>
        </div>
      </div>
    </section>
    </div>
</template>

<script>
import instagramIcon from '@/assets/instagram.svg';
import twitchIcon from '@/assets/twitch.svg';
import youtubeIcon from '@/assets/youtube.svg';
import twitterIcon from '@/assets/twitter.svg';
import githubIcon from '@/assets/github.svg';

export default {
  name: 'Home',
  data: function() {
    return {
      instagramIcon,
      twitchIcon,
      youtubeIcon,
      twitterIcon,
      githubIcon,
    };
  },
};
</script>
<style lang="scss">
.vertical-spacing {
  margin: 5% 0;
}
.icon-attributes-text {
  font-size: 8pt;
  font-style: italic;
  margin: 0 2%;
}
.icon-attributes {
  display: flex;
  justify-content: space-around;
  width: 100%;
}
.icon-container {
  display: flex;
  margin: 5% 0;
  align-items: center;
  > span {
    margin-left: 5%;
  }
}
.view {
  height: 90%;
  display: flex;
  flex-direction: column;
  align-content: space-around;
  justify-content: space-around;
}
.vertical-center {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-content: center;
  align-items: center;
}
.two-column {
  display: flex;
  width: 100%;
  justify-content: space-around;
}
.center-p {
  text-align: center;
}
</style>
