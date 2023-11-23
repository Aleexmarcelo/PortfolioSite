$(function() {
  
    const introHeight = document.querySelector('.intro').offsetHeight;
    const topButton = document.getElementById('top-button');
    const $topButton = $('#top-button');
  
    window.addEventListener('scroll', function() {
      if (window.scrollY > introHeight) {
        $topButton.fadeIn();
      } else {
        $topButton.fadeOut();
      }
    }, false);
  
    topButton.addEventListener('click', function() {
      $('html, body').animate({scrollTop: 0}, 500);
    });
  
    //const hand = document.querySelector('.emoji.wave-hand');
  
    // function waveOnLoad() {
    //   hand.classList.add('wave');
    //   
    // }
  
    window.sr = ScrollReveal({
    reset: false,
    duration: 600,
    easing: 'cubic-bezier(.694,0,.335,1)',
    scale: 1,
    viewFactor: 0.3
    });

    sr.reveal('.background');
    sr.reveal('.skills');
    sr.reveal('.featured-projects', {viewFactor: 0.1});
    sr.reveal('.jam-projects', {viewFactor: 0.05});
    sr.reveal('.assets', {viewFactor: 0.05});
  });

  