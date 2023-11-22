<!-- Markdown -->

# Hello World

<div class="letter-animation">
  <span>H</span>
  <span>e</span>
  <span>l</span>
  <span>l</span>
  <span>o</span>
  <span> </span>
  <span>W</span>
  <span>o</span>
  <span>r</span>
  <span>l</span>
  <span>d</span>
</div>

<!-- CSS -->

<style>
  .letter-animation span {
    display: inline-block;
    opacity: 0;
    transform: translateY(-20px);
    transition: opacity 0.3s, transform 0.3s;
  }

  .letter-animation span.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* Delay each letter's appearance */
  .letter-animation span:nth-child(1) { transition-delay: 0.1s; }
  .letter-animation span:nth-child(2) { transition-delay: 0.2s; }
  .letter-animation span:nth-child(3) { transition-delay: 0.3s; }
  .letter-animation span:nth-child(4) { transition-delay: 0.4s; }
  .letter-animation span:nth-child(5) { transition-delay: 0.5s; }
  .letter-animation span:nth-child(6) { transition-delay: 0.6s; }
  .letter-animation span:nth-child(7) { transition-delay: 0.7s; }
  .letter-animation span:nth-child(8) { transition-delay: 0.8s; }
  .letter-animation span:nth-child(9) { transition-delay: 0.9s; }
  .letter-animation span:nth-child(10) { transition-delay: 1s; }
  .letter-animation span:nth-child(11) { transition-delay: 1.1s; }

  /* Add more styles as needed */
</style>
