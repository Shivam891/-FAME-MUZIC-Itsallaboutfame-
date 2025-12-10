<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Famemuzic — YOUR_NAME</title>
  <link rel="stylesheet" href="styles.css" />
  <meta name="description" content="Official music of YOUR_NAME — singles, beats and bookings." />
</head>
<body>
  <header class="site-header">
    <div class="wrap">
      <h1 class="brand">FameMuzic</h1>
      <nav class="nav">
        <a href="#music">Music</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="wrap">
        <h2>YOUR_NAME</h2>
        <p class="tagline">Singer • Producer • Performer — New single out now</p>
        <a class="cta" href="#music">Listen Now</a>
      </div>
    </section>

    <section id="music" class="wrap music-section">
      <h3>Latest Tracks</h3>
      <!-- Replace with SoundCloud / Spotify / YouTube embed -->
      <div class="player">
        <!-- Example SoundCloud embed -->
        <iframe width="100%" height="166" scrolling="no" frameborder="no"
          src="https://w.soundcloud.com/player/?url=YOUR_SOUNDCLOUD_TRACK_URL&color=%23000000&auto_play=false"></iframe>
      </div>

      <div class="player">
        <!-- Example YouTube embed -->
        <iframe width="100%" height="200" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
      </div>
    </section>

    <section id="about" class="wrap about">
      <h3>About</h3>
      <p>Short bio — aaj tak ka kaam, achievements, link to press kit (PDF).</p>
    </section>

    <section id="contact" class="wrap contact">
      <h3>Contact / Booking</h3>
      <p>Email: <a href="mailto:your@email.com">your@email.com</a></p>
      <p>Booking form: <a href="https://forms.gle/YOUR_GOOGLE_FORM" target="_blank">Booking Request</a></p>
      <p>Follow: <a href="#">Instagram</a> • <a href="#">Spotify</a> • <a href="#">SoundCloud</a></p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="wrap">
      <small>© <span id="year"></span> FameMuzic</small>
    </div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
style.css
:root{--maxw:980px;--accent:#111}
*{box-sizing:border-box}
body{font-family:system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;margin:0;color:#111;line-height:1.5}
.wrap{max-width:var(--maxw);margin:0 auto;padding:20px}
.site-header{background:#fff;border-bottom:1px solid #eee}
.brand{margin:0;display:inline-block;padding:14px 0;font-weight:700}
.nav{float:right}
.nav a{margin-left:18px;text-decoration:none;color:inherit}
.hero{background:linear-gradient(180deg, #f8f8f8, #fff);padding:56px 0;text-align:center}
.hero h2{margin:0;font-size:32px}
.tagline{color:#555;margin:8px 0 18px}
.cta{display:inline-block;padding:10px 18px;border-radius:6px;text-decoration:none;border:1px solid #111}
.music-section h3, .about h3, .contact h3{margin-top:0}
.player{margin-bottom:18px}
.site-footer{border-top:1px solid #eee;padding:18px 0;text-align:center;color:#666}
@media(max-width:700px){.nav{float:none;text-align:center;margin-top:10px}.wrap{padding:12px}}