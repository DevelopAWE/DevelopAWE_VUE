<template>
<div id="wrapper">
  <!-- Header -->
  <header id="header">
    <div class="logo">
    </div>
    <div class="content">
      <div class="inner">
        <h1>DevelopAWE</h1>
          <p>Web design, web development, android and IOS Apps and everything else web related.</p>
      </div>
    </div>
    <nav>
      <ul>
        <li><a href="#intro">Intro</a></li>
        <li><a href="#work">Work</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Main -->
  <div id="main">

    <!-- Intro -->
    <article id="intro">
      <h2 className="major">Intro</h2>
        <p>We are DevelopAWE. AWE stands for App, Web, and Everything. We aim to do everything web or app related for you. We will design and develop your website, host it for you, supply domains and keep your site up to date for you. We can also develop Android and IOS apps to suit your needs if you need an app built. “We will leave you in <strong><em>AWE</em></strong>”</p>
    </article>

    <!-- Work -->
    <article id="work">
      <h2 class="major">Work</h2>
      <p>Adipiscing magna sed dolor elit. Praesent eleifend dignissim arcu, at eleifend sapien imperdiet ac. Aliquam erat volutpat. Praesent urna nisi, fringila lorem et vehicula lacinia quam. Integer sollicitudin mauris nec lorem luctus ultrices.</p>
      <p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus pharetra. Pellentesque condimentum sem. In efficitur ligula tate urna. Maecenas laoreet massa vel lacinia pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus amet feugiat tempus.</p>
    </article>

    <!-- About -->
    <article id="about">
      <h2 class="major">About</h2>
      <p>Lorem ipsum dolor sit amet, consectetur et adipiscing elit. Praesent eleifend dignissim arcu, at eleifend sapien imperdiet ac. Aliquam erat volutpat. Praesent urna nisi, fringila lorem et vehicula lacinia quam. Integer sollicitudin mauris nec lorem luctus ultrices. Aliquam libero et malesuada fames ac ante ipsum primis in faucibus. Cras viverra ligula sit amet ex mollis mattis lorem ipsum dolor sit amet.</p>
    </article>

    <!-- Contact -->
    <article id="contact">
      <h2 class="major">Contact</h2>
      <form method="post" action="#">
        <div class="field half first">
          <label for="name">Name</label>
          <input type="text" name="name" id="name" />
        </div>
        <div class="field half">
          <label for="email">Email</label>
          <input type="text" name="email" id="email" />
        </div>
        <div class="field">
          <label for="message">Message</label>
          <textarea name="message" id="message" rows="4"></textarea>
        </div>
        <ul class="actions">
          <li><input type="submit" value="Send Message" class="special" /></li>
          <li><input type="reset" value="Reset" /></li>
        </ul>
      </form>
      <ul class="icons">
        <li>
          <a href="#" class="icon fa-twitter">
            <span class="label">Twitter</span>
          </a>
        </li>
        <li>
          <a href="#" class="icon fa-facebook">
            <span class="label">Facebook</span>
          </a>
        </li>
        <li>
          <a href="#" class="icon fa-instagram">
            <span class="label">Instagram</span>
            </a>
        </li>
        <li>
          <a href="#" class="icon fa-github">
            <span class="label">GitHub</span>
          </a>
        </li>
      </ul>
    </article>
  </div>
  <!-- Footer -->
  <footer id="footer">
    <p class="copyright">&copy; Untitled. Design: <a href="https://html5up.net">HTML5 UP</a>.</p>
  </footer>
</div>
</template>

<script>
export default {
  name: 'Index'
}
</script>

<style>

</style>
