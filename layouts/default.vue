<template>
  <div>
    <header class="navbar">
      <div class="container navbar-container">
        <a href="/" class="navbar-logo">SocialMediaClipper</a>
        <nav class="navbar-links">
          <a href="#features" class="navbar-link">Features</a>
          <a href="#pricing" class="navbar-link">Pricing</a>
          <a href="#comparison" class="navbar-link">Why Choose Us</a>
          <a href="#faq" class="navbar-link">FAQ</a>
        </nav>
      </div>
    </header>

    <main>
      <slot />
    </main>

    <footer class="footer">
      <div class="container">
        <div class="footer-content">
          <div class="footer-column">
            <h3>SocialMediaClipper</h3>
            <p>Making content creation easier, faster, and more efficient than ever before.</p>
          </div>
          <div class="footer-column">
            <h3>Resources</h3>
            <ul class="footer-links">
              <li class="footer-link"><a href="/docs">Documentation</a></li>
              <li class="footer-link"><a href="/tutorials">Tutorials</a></li>
              <li class="footer-link"><a href="/blog">Blog</a></li>
            </ul>
          </div>
          <div class="footer-column">
            <h3>Legal</h3>
            <ul class="footer-links">
              <li class="footer-link"><a href="/terms">Terms of Service</a></li>
              <li class="footer-link"><a href="/privacy">Privacy Policy</a></li>
              <li class="footer-link"><a href="/cookies">Cookie Policy</a></li>
            </ul>
          </div>
          <div class="footer-column">
            <h3>Connect</h3>
            <ul class="footer-links">
              <li class="footer-link"><a href="https://twitter.com">Twitter</a></li>
              <li class="footer-link"><a href="https://youtube.com">YouTube</a></li>
              <li class="footer-link"><a href="https://linkedin.com">LinkedIn</a></li>
            </ul>
          </div>
        </div>
        <div class="footer-bottom">
          <p>&copy; {{ new Date().getFullYear() }} SocialMediaClipper. All rights reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>
