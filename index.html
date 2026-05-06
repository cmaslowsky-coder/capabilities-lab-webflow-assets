const planes = document.querySelectorAll('.plane');
  const sky = document.querySelector('.sky');
  let ticking = false;

  function update() {
    const scroll = window.scrollY;
    planes.forEach(plane => {
      const rate = parseFloat(plane.dataset.rate);
      plane.style.transform = `translate3d(0, ${-scroll * rate}px, 0)`;
    });
    sky.style.backgroundPosition = `0 ${-scroll}px`;
    ticking = false;
  }

  window.addEventListener('scroll', () => {
    if (!ticking) {
      requestAnimationFrame(update);
      ticking = true;
    }
  }, { passive: true });
  window.addEventListener('resize', update);
  update();

  // Subtle text fade-in
  const cards = document.querySelectorAll('.card');
  cards.forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(24px)';
    el.style.transition = 'opacity 1.1s ease-out, transform 1.1s ease-out';
  });
  const observer = new IntersectionObserver(entries => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        e.target.style.opacity = '1';
        e.target.style.transform = 'translateY(0)';
      }
    });
  }, { threshold: 0.15 });
  cards.forEach(el => observer.observe(el));
