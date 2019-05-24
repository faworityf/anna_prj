<template>
  <div class="wrap__all">
    <!--Header-->
    <header class="header container">
      <div class="logo">
        <img src="img/logo.svg" alt="logo">
      </div>
      <div class="burger">
        <div class="burger__line"></div>
        <div class="menu__overlay"></div>
      </div>
      <div class="header__menu">
        <Navigation></Navigation>
        <div class="user">
          <div class="user__img">
            <img src="img/user-superstar-2x.jpg" alt="">
          </div>
          <div class="user__info">
            <div class="user__info__name">Superstar</div>
            <a href="mailto:superstar@gmail.com" rel="nofollow">Superstar@gmail.com</a>
          </div>
          <a href="#signout" rel="nofollow" class="user__info__out">
            <picture>
              <source srcset="img/icons/sign-out.svg" media="(min-width: 1024px)">
              <img class="svg" srcset="" alt="">
            </picture>
          </a>
        </div>
      </div>
    </header>
    <!--end Header-->
    <!--All Container-->
    <!-- 1 Section-->
    <section class="top__screen">
      <div class="container">
        <div class="top__screen__content">
          <h1>Test assignment for Frontend Developer position</h1>
          <p>We kindly remind you that your test assignment should be submitted as a link to github/bitbucket
            repository. Please be patient, we consider and respond to every application that meets minimum
            requirements. We look forward to your submission. Good luck!</p>
          <a class="button button__full" href="#signup" rel="nofollow">Sign Up</a>
        </div>
      </div>
    </section>
    <!-- end 1 Section-->
    <!-- 2 Section-->
    <section id="about" class="about container">
      <h2>Let's get acquainted</h2>
      <div class="about__content">
        <div><img src="img/man-mobile.svg" alt=""></div>
        <div>
          <h3>I am cool frontend developer</h3>
          <p>When real users have a slow experience on mobile, they're much less likely to find what they are
            looking
            for
            or purchase from you in the future. For many sites this equates to a huge missed opportunity,
            especially
            when more than half of visits are abandoned if a mobile page takes over 3 seconds to load.</p>

          <p>Last week, Google Search and Ads teams announced two new speed initiatives to help improve
            user-experience on
            the web.</p>
          <a href="#signup" rel="nofollow" class="button__link">Sign Up</a>
        </div>
      </div>
    </section>
    <!-- end 2 Section-->
    <!-- 3 Section-->
    <section id="relationships" class="relationship container">
      <h2>About my relationships with web-development</h2>
        <AboutComponent></AboutComponent>
    </section>
    <!-- end 3 Section-->
    <!-- 4 Section-->
    <section id="requirements" class="requirements">
      <div class="container">
        <h2>General requirements for the test task</h2>
        <div class="requirements__content">
          <picture>
            <source srcset="img/man-laptop-v1.svg" media="(min-width: 1024px)">
            <source srcset="img/man-laptop-v2.svg" media="(min-width: 768px)">
            <img srcset="img/man-laptop-v1.svg" alt="">
          </picture>
          <div>
            <p>Users want to find answers to their questions quickly and data shows that people really care
              about
              how
              quickly their pages load. The Search team announced speed would be a ranking signal for desktop
              searches in
              2010 and as of this month (July 2018), page speed will be a ranking factor for mobile searches
              too.</p>

            <p>If you're a developer working on a site, now is a good time to evaluate your performance using
              our
              speed
              tools. Think about how performance affects the user experience of your pages and consider
              measuring
              a
              variety of real-world user-centric performance metrics.</p>

            <p>Are you shipping too much JavaScript? Too many images? Images and JavaScript are the most
              significant
              contributors to the page weight that affect page load time based on data from HTTP Archive and
              the
              Chrome
              User Experience Report - our public dataset for key UX metrics as experienced by Chrome users
              under
              real-world conditions.</p>
          </div>
        </div>
      </div>
    </section>
    <!-- end 4 Section-->
    <!-- 5 Section-->
    <section id="users" class="users container">
      <h2>Our cheerful users</h2>
      <h5>Attention! Sorting users by registration date</h5>
      <UsersComponent></UsersComponent>
      <div class="button">Show more</div>
    </section>
    <!-- end 5 Section-->
    <!-- 6 Section-->
    <section id="signup" class="signup container">
      <h2>Register to get a work</h2>
      <h5>Attention! After successful registration and alert, update the list of users
        in the block from the top</h5>
      <form class="form">
        <div class="column__three">
          <fieldset>
            <legend>Name</legend>
            <input type="text" name="name" placeholder="Your name">
          </fieldset>
          <fieldset>
            <legend>Email</legend>
            <input type="email" name="email" placeholder="Your email">
          </fieldset>
          <fieldset>
            <legend>Phone</legend>
            <input type="tel" name="phone" placeholder="+38(___) ___ __ __">
          </fieldset>
        </div>
        <div class="column__two">
          <select name="position">
            <option value="" disabled selected hidden>Select your position</option>
            <option value="first">First</option>
            <option value="second">Second</option>
          </select>
          <div>
            <label class='input__file'>
              <span data-default='upload'>Upload your photo</span>
              <input type="file" class="upload">
            </label>
            <p>File format jpg up to 5 MB, the minimum size of 70x70px</p>
          </div>
        </div>
        <button type="submit" class="button button__full button__disable">Sign Up</button>
      </form>
    </section>
    <!-- end 6 Section-->
    <!--end All Container-->
    <!--Footer-->
    <footer class="footer">
      <div class="footer__top container">
        <div class="logo">
          <img src="img/logo.svg" alt="logo" class="svg">
        </div>
        <div class="footer__menu">
          <Navigation></Navigation>

        </div>
      </div>
      <div class="footer__middle container">
        <div class="footer__middle__contacts">
          <div class="footer__middle__contacts__icon">
            <picture>
              <source srcset="img/icons/mail.svg" media="(min-width: 1024px)">
              <img srcset="" alt="">
            </picture>
            <a href="mailto:work.of.future@gmail.com" rel="nofollow">work.of.future@gmail.com</a>
          </div>
          <div class="footer__middle__contacts__icon">
            <picture>
              <source srcset="img/icons/phone.svg" media="(min-width: 1024px)">
              <img srcset="" alt="">
            </picture>
            <a>+38 (050) 789 24 98</a>
          </div>
          <div class="footer__middle__contacts__icon">
            <picture>
              <source srcset="img/icons/cellphone.svg" media="(min-width: 1024px)">
              <img srcset="" alt="">
            </picture>
            <a>+38 (095) 556 08 45</a>
          </div>
        </div>
        <div class="footer__middle__tags">
          <div>
            <a>News</a>
            <a>Blog</a>
            <a>Partners</a>
            <a>Shop</a>
          </div>
          <div>
            <a>Overview</a>
            <a>Design</a>
            <a>Code</a>
            <a>Collaborate</a>
          </div>
          <div>
            <a>Tutorials</a>
            <a>Resources</a>
            <a>Guides</a>
            <a>Examples</a>
          </div>
          <div>
            <a>FAQ</a>
            <a>Terms</a>
            <a>Conditions</a>
            <a>help</a>
          </div>
        </div>

      </div>
      <div class="footer__bottom container">
        <div class="social">
          <a><img src="img/icons/facebook.svg" alt="" class="svg"></a>
          <a><img src="img/icons/linkedin.svg" alt="" class="svg"></a>
          <a><img src="img/icons/instagram.svg" alt="" class="svg"></a>
          <a><img src="img/icons/twitter.svg" alt="" class="svg"></a>
          <a><img src="img/icons/pinterest.svg" alt="" class="svg"></a>
        </div>
        <div>© abz.agency specially for the test task</div>
      </div>
    </footer>
    <!--end Footer-->
  </div>

</template>

<script>
import Navigation from '@/components/Navigation'
import AboutComponent from '@/components/About'
import UsersComponent from '@/components/Users'

export default {
  name: 'app',
  components: {
      Navigation,
      AboutComponent,
      UsersComponent
  }
}
</script>

<style>
</style>
