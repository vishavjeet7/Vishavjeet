#<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1.0" />
  <title>Visionary Storytelling in Every Frame.</title>
  
  <link href="https://fonts.googleapis.com/css2?family=Metal+Mania&display=swap" rel="stylesheet">
  <style>
    @font-face {
      font-family: 'Brunson Rough';
      src: url('Brunson Rough.ttf') format('truetype');
      font-weight: normal;
      font-style: normal;
    }

    @font-face {
      font-family: 'PLANK';
      src: url('PLANK___.TTF') format('truetype');
      font-weight: normal;
      font-style: normal;
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      color: #eee;
      background-color: #0b0b0b;
      cursor: url('https://cdn-icons-png.flaticon.com/512/545/545682.png') 16 16, auto;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    header {
      display: flex;
      align-items: center;
      justify-content: center;
      height: 80vh;
      background: #000;
      color: #fff;
      text-align: center;
      width: 100%;
    }
    header h1 {
      font-size: 3rem;
    }
    section {
      padding: 3rem 1rem;
      max-width: 1000px;
      width: 100%;
      box-sizing: border-box;
    }
    h2, h3, p, li, a {
      color: #eee;
    }
    a {
  color: #910736;
  font-weight: 600;
  background: linear-gradient(90deg, #ff6a00, #ff0000);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-shadow: 0 0 5px #ff4500;
}
    .work {
      margin: 2rem 0;
    }
    .video-grid {
      display: flex;
      flex-direction: column;
      gap: 3rem;
      align-items: center;
    }
    .work-item {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 2rem;
      width: 100%;
    }
    .work-item.reverse {
      flex-direction: row-reverse;
    }
    .video-wrapper {
      position: relative;
      overflow: hidden;
      border-radius: 16px;
      opacity: 0;
      transform: translateY(80px);
      transition: all 0.8s ease;
      box-shadow: 0 0 20px rgba(145, 7, 54, 0.2);
      background: linear-gradient(90deg, #910736 0%, transparent 100%);
      background-size: 200% auto;
      background-position: 0% center;
      flex: 1 1 45%;
      animation: flicker 3s infinite linear;
    }
    .video-wrapper.visible {
      opacity: 1;
      transform: translateY(0);
      transition-delay: 0.3s;
      background-position: 100% center;
    }
    .video-wrapper::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      border: 2px solid #910736;
      border-radius: 16px;
      box-shadow: 0 0 20px #910736, 0 0 60px #910736;
      pointer-events: none;
      z-index: 1;
    }
    @keyframes flicker {
      0% {
        box-shadow: 0 0 10px rgba(145, 7, 54, 0.1);
      }
      50% {
        box-shadow: 0 0 40px rgba(145, 7, 54, 0.6);
      }
      100% {
        box-shadow: 0 0 10px rgba(145, 7, 54, 0.1);
      }
    }
    video {
      width: 100%;
      border-radius: 12px;
      position: relative;
      z-index: 0;
    }
    .video-text {
      flex: 1 1 45%;
    }
    .video-text h3 {
      font-family: 'Brunson Rough', sans-serif;
      font-size: 2.8rem;
      font-weight: 900;
      text-align: center;
    }
    .work-item p {
      margin-top: 0;
      font-size: 1rem;
      color: #ccc;
      text-align: center;
    }
    .cta {
      text-align: center;
      margin: 2rem 0;
    }
    footer {
      background: #111;
      padding: 2rem;
      font-size: 0.9rem;
      color: #aaa;
      width: 100%;
      text-align: center;
    }
  </style>
</head>
<body>
<header>
  <div>
    <h2 style="font-family: 'Metal Mania', cursive; font-size: 3rem; margin-bottom: 1rem;">Vishavjeet</h2>
    <h1>Visionary Storytelling in Every Frame.</h1>
    <p>Helping online business owners dominate their niche through cinematic video editing.</p>
    <a href="#contact">Let’s Talk</a>
  </div>
</header>

<section class="work">
  <h2 style="text-align: center;">Examples of My Work</h2>
  <div class="video-grid">
    <div class="work-item">
      <div class="video-wrapper">
        <div style="padding:56.25% 0 0 0;position:relative;">
  <iframe src="https://player.vimeo.com/video/1099050534?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media; web-share" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="jon-vimeo"></iframe>
</div>
<script src="https://player.vimeo.com/api/player.js"></script>
      </div>
      <div class="video-text">
        <h3>JON</h3>
        <p>Iman Gadhzi style video make your video professional touch</p>
      </div>
    </div>
    <div class="work-item reverse">
      <div class="video-wrapper">
        <div style="padding:56.25% 0 0 0;position:relative;">
          <iframe src="https://player.vimeo.com/video/1099050502?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media; web-share" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="ali-abdaal-demo"></iframe>
        </div>
        <script src="https://player.vimeo.com/api/player.js"></script>
      </div>
      <div class="video-text">
        <h3>Ali Abdaal</h3>
        <p>Simple and minimal give nice look to your content</p>
      </div>
    </div>
    <div class="work-item">
      <div class="video-wrapper">
        <div style="padding:56.25% 0 0 0;position:relative;">
          <iframe src="https://player.vimeo.com/video/1099050584?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media; web-share" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="vlogs-vimeo"></iframe>
        </div>
        <script src="https://player.vimeo.com/api/player.js"></script>
      </div>
      <div class="video-text">
        <h3>Vlogs</h3>
        <p>Cinematic Vlogs and lifestlye</p>
      </div>
    </div>
    <div class="work-item reverse">
      <div class="video-wrapper">
        <div style="padding:56.25% 0 0 0;position:relative;">
          <iframe src="https://player.vimeo.com/video/1099050519?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media; web-share" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="colorgrading-vimeo"></iframe>
        </div>
        <script src="https://player.vimeo.com/api/player.js"></script>
      </div>
      <div class="video-text">
        <h3>Colorgrading</h3>
        <p>Rec 709 to cinematics</p>
      </div>
    </div>
  </div>
</section>

<section class="cta" id="contact">
  <h2>Want to work with me?</h2>
  <p>DM me on Instagram or email me at <a href="mailto:vishavjeetoffcial@gmail.com">vishavjeetoffcial@gmail.com</a>.</p>
  <a href="https://instagram.com/yourhandle">Let’s Talk</a>
</section>

<footer>
  &copy; 2025 Vishavjeet — Video Editor & Cinematic Storyteller
</footer>
<script>
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, {
    threshold: 0.1
  });

  document.querySelectorAll('.video-wrapper').forEach(el => {
    observer.observe(el);
  });
</script>
</body>
</html>
