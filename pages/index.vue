<template>
  <div class="gpg-container h-screen flex flex-col justify-between"">
      <video
          class="w-full fixed gpg-video"
          playsinline
          autoplay
          loop
          muted>
          <source
              src="~/assets/video/gpg-gaming.mp4"
              type="video/mp4">
      </video>

      <header id="header" class="site-header site-header--landing">
          <!-- Main Navigation Left -->
          <nav class="main-nav">
              <ul class="main-nav__list">
                  <li class=""><a href="#">Home</a></li>
                  <li class="">
                      <a href="#">Teams</a>
                      <ul class="main-nav__sub">
                          <li class="">
                              <a href="#">Team</a>
                              <ul class="main-nav__sub">
                                  <li class=""><a href="team-selection-1.html">Team Selection v1</a></li>
                                  <li class=""><a href="team-selection-2.html">Team Selection v2</a></li>
                                  <li class=""><a href="team-selection-3.html">Team Selection v3</a></li>
                                  <li class=""><a href="team-selection-4.html">Team Selection v4</a></li>
                              </ul>
                          </li>
                          <li class="">
                              <a href="team-overview.html">Team Overview</a>
                              <ul class="main-nav__sub">
                                  <li class=""><a href="team-overview.html">Team Overview v1</a></li>
                                  <li class=""><a href="team-overview-2.html">Team Overview v2</a></li>
                              </ul>
                          </li>
                          <li class=""><a href="team-player-1.html">Player Page</a></li>
                      </ul>
                  </li>
                  <li class=""><a href="#">Matches</a>
                      <ul class="main-nav__sub">
                          <li class=""><a href="matches-scores.html">Match Scores</a></li>
                          <li class=""><a href="matches-upcoming.html">Upcoming Matches</a></li>
                          <li class=""><a href="matches-standings.html">Standings</a></li>
                          <li class=""><a href="#">Match Stats</a>
                              <ul class="main-nav__sub">
                                  <li class=""><a href="matches-stats-1.html">Match Stats v1</a></li>
                                  <li class=""><a href="matches-stats-2.html">Match Stats v2</a></li>
                                  <li class=""><a href="matches-stats-3.html">Match Stats v3</a></li>
                              </ul>
                          </li>
                          <li class="">
                              <a href="#">Match Lineups</a>
                              <ul class="main-nav__sub">
                                  <li class=""><a href="matches-lineups-1.html">Match Lineups v1</a></li>
                                  <li class=""><a href="matches-lineups-2.html">Match Lineups v2</a></li>
                                  <li class=""><a href="matches-lineups-3.html">Match Lineups v3</a></li>
                              </ul>
                          </li>
                          <li class=""><a href="#">Match Overviews</a>
                              <ul class="main-nav__sub">
                                  <li class=""><a href="matches-overview-1.html">Match Overview v1</a></li>
                                  <li class=""><a href="matches-overview-2.html">Match Overview v2</a></li>
                              </ul>
                          </li>
                          <li class=""><a href="matches-replay.html">Match Replay</a></li>
                      </ul>
                  </li>
              </ul>
          </nav>
          <!-- Main Navigation Left / End -->

          <!-- Logo - Image Based -->
          <div class="header-logo header-logo--img">
              <a href="index.html"><img src="~assets/img/logo.png" srcset="assets/img/logo@2x.png 2x" alt="Necromancers"></a>
          </div>
          <!-- Logo - Image Based / End -->
            
          <!-- Main Navigation Right -->
          <nav class="main-nav">
              <ul class="main-nav__list">
                  <li class=""><a href="#">News</a>
                      <ul class="main-nav__sub">
                          <li class=""><a href="blog-1.html">News v1</a></li>
                          <li class=""><a href="blog-2.html">News v2</a></li>
                          <li class=""><a href="blog-3.html">News v3</a></li>
                          <li class=""><a href="blog-4.html">News v4</a></li>
                          <li class=""><a href="blog-classic.html">News Classic <span class="badge badge-danger">New</span></a></li>
                          <li class=""><a href="blog-post.html">Post Page</a></li>
                      </ul>
                  </li>
                  <li class=" has-child"><a href="#">Features</a>
                      <div class="main-nav__megamenu">
                          <div class="row">
                              <div class="col-md-4">
                                  <h6 class="main-nav__title">Main Pages</h6>
                                  <div class="row">
                                      <ul class="col-md-4">
                                          <li class="active"><a href="index.html">Landing Image</a></li>
                                          <li class=""><a href="index-2.html">Landing Video</a></li>
                                          <li class=""><a href="blog-post.html">Post Page</a></li>
                                          <li class=""><a href="blog-1.html">News v1</a></li>
                                          <li class=""><a href="blog-2.html">News v2</a></li>
                                          <li class=""><a href="blog-3.html">News v3</a></li>
                                          <li class=""><a href="blog-4.html">News v4</a></li>
                                          <li class=""><a href="blog-classic.html">News Classic <span class="badge badge-danger">New</span></a></li>
                                      </ul>
                                      <ul class="col-md-4">
                                          <li class=""><a href="shop-account-settings.html">Account Settings</a></li>
                                          <li class=""><a href="shop-account-orders.html">Account Orders</a></li>
                                          <li class=""><a href="login-register.html">Login & Register</a></li>
                                          <li class=""><a href="features-about-us.html">About Us</a></li>
                                          <li class=""><a href="features-contact-us.html">Contact Us</a></li>
                                          <li class=""><a href="features-faqs.html">FAQs</a></li>
                                      </ul>
                                      <ul class="col-md-4">
                                          <li class=""><a href="management-and-staff.html">MGMT & Staff</a></li>
                                          <li class=""><a href="streams-archive.html">Streams Page</a></li>
                                          <li class=""><a href="partners.html">Our Partners</a></li>
                                          <li class=""><a href="features-shortcodes.html">Shortcodes</a></li>
                                          <li class=""><a href="features-typography.html">Typography</a></li>
                                          <li class=""><a href="features-icons.html">Icons <span class="badge badge-danger">New</span></a></li>
                                          <li class=""><a href="features-bg-1.html">Backgrounds</a></li>
                                      </ul>
                                  </div>
                              </div>
                              <div class="col-md-4">
                                  <div class="row">
                                      <h6 class="col-md-8 main-nav__title">Team Pages</h6>
                                      <h6 class="col-md-4 main-nav__title">Player Pages</h6>
                                  </div>
                                  <div class="row">
                                      <ul class="col-md-4">
                                          <li class=""><a href="team-selection-1.html">Team Selection v1</a></li>
                                          <li class=""><a href="team-selection-2.html">Team Selection v2</a></li>
                                          <li class=""><a href="team-selection-3.html">Team Selection v3</a></li>
                                          <li class=""><a href="team-selection-4.html">Team Selection v4</a></li>
                                          <li><a href="team-overview.html">Team Overview v1</a></li>
                                          <li><a href="team-overview-2.html">Team Overview v2</a></li>
                                      </ul>
                                      <ul class="col-md-4">
                                          <li><a href="team-overview.html?slide=1">Team Statistics</a></li>
                                          <li><a href="team-overview.html?slide=2">Team Achv</a></li>
                                          <li><a href="team-overview.html?slide=3">Team Matches</a></li>
                                      </ul>
                                      <ul class="col-md-4">
                                          <li><a href="team-player-1.html">Player Overview</a></li>
                                          <li><a href="team-player-1.html?slide=1">Player Statistics</a></li>
                                          <li><a href="team-player-1.html?slide=2">Player Achv</a></li>
                                          <li><a href="team-player-1.html?slide=3">Player Hardware</a></li>
                                          <li><a href="team-player-1.html?slide=4">Player Stream</a></li>
                                      </ul>
                                  </div>
                              </div>
                              <div class="col-md-4">
                                  <div class="row">
                                      <h6 class="col-md-8 main-nav__title">Match Pages</h6>
                                      <h6 class="col-md-4 main-nav__title">Shop Pages</h6>
                                  </div>
                                  <div class="row">
                                      <ul class="col-md-4">
                                          <li class=""><a href="matches-scores.html">Match Scores</a></li>
                                          <li class=""><a href="matches-upcoming.html">Upcoming Matches</a></li>
                                          <li class=""><a href="matches-standings.html">Standings</a></li>
                                          <li class=""><a href="matches-overview-1.html">Overview v1</a></li>
                                          <li class=""><a href="matches-overview-2.html">Overview v2</a></li>
                                          <li class=""><a href="matches-stats-1.html">Match Stats v1</a></li>
                                      </ul>
                                      <ul class="col-md-4">
                                          <li class=""><a href="matches-stats-2.html">Match Stats v2</a></li>
                                          <li class=""><a href="matches-stats-3.html">Match Stats v3</a></li>
                                          <li class=""><a href="matches-lineups-1.html">Match Lineups v1</a></li>
                                          <li class=""><a href="matches-lineups-2.html">Match Lineups v2</a></li>
                                          <li class=""><a href="matches-lineups-3.html">Match Lineups v3</a></li>
                                          <li class=""><a href="matches-replay.html">Match Replay</a></li>
                                      </ul>
                                      <ul class="col-md-4">
                                          <li class=""><a href="shop.html">Shop Page v1</a></li>
                                          <li class=""><a href="shop-2.html">Shop Page v2</a></li>
                                          <li class=""><a href="shop-product.html">Product Page</a></li>
                                          <li class=""><a href="shop-checkout.html">Checkout Page</a></li>
                                      </ul>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </li>
                  <li class="">
                      <a href="#">Shop</a>
                      <ul class="main-nav__sub">
                          <li class=""><a href="shop.html">Shop Page v1</a></li>
                          <li class=""><a href="shop-2.html">Shop Page v2</a></li>
                          <li class=""><a href="shop-product.html">Product Page</a></li>
                          <li class=""><a href="shop-checkout.html">Checkout Page</a></li>
                      </ul>
                  </li>
              </ul>
          </nav>
          <!-- Main Navigation Right / End -->
      </header>
      <!-- Header / End -->
      <main class="site-content text-center" id="wrapper">
			
			<div class="site-content__center">
				<h1 class="text-white landing-title"><span class="subtitle landing-subtitle">Esports and Streaming</span>Germany Playsgroup</h1>
				<a href="home.html" class="btn btn-primary btn-lg btn--landing"><span>Start Browsing!</span></a>
			</div>
			
		</main>
    

<!--      <main class="mb-auto">-->

<!--      </main>-->

    <footer class="p-2 text-center relative gpg-footer border-t-2 border-red">
          <h3 class="text-white">Footer</h3>
      </footer>
    </div>
</template>

<script>
export default {
}
</script>

<style>
.gpg-video{
    position:fixed;
    margin-top: -20px;
    z-index: -1;
    width: 100%;
    height:auto;
   
   
}
li{
    border: none;
}

.gpg-footer{
    background-color: black;
}
@media(min-aspect-ratio: 16/9)
{
    .gpg-video{
        width:100%;
        height:auto;
    }
}
@media(max-aspect-ratio: 16/9)
{
    .gpg-video{
        width:auto;
        height:100%;
    }
}


</style>
