# Wall-Magazine2
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Digital Culture – Wall Magazine</title>
  <style>
    /* General body styles */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #4a90e2, #9013fe);
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      margin-bottom: 2rem;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
    }
    header p {
      margin: 0.5rem 0 0;
      font-size: 1.2rem;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      padding: 0 1rem 2rem;
    }

    section {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
      display: flex;
      flex-direction: column;
    }

    section h2 {
      background-color: #eee;
      margin: 0;
      padding: 1rem;
      font-size: 1.5rem;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    section p {
      padding: 0 1rem 1rem;
      flex-grow: 1;
    }

    section img {
      width: 100%;
      display: block;
      object-fit: cover;
    }

    .video-container {
      position: relative;
      overflow: hidden;
      padding-top: 56.25%;
    }

    .video-container iframe {
      position: absolute;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      border: 0;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #333;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <h1>Digital Culture</h1>
    <p>Exploring how technology shapes our society, creativity, and future</p>
  </header>

  <div class="container">
    <section>
      <h2>🌐 What is Digital Culture?</h2>
      <p>
        Digital culture is the way our lives are influenced by the internet, social media, smartphones,
        and digital innovations. It changes how we communicate, learn, work, and express ourselves.
      </p>
      <img src="https://images.unsplash.com/photo-1518770660439-4636190af475" alt="Digital world" />
    </section>

    <section>
      <h2>📱 Impact on Society</h2>
      <p>
        The rise of social media, online education, and digital art has transformed society. While we gain
        global connectivity and new opportunities, challenges like misinformation, screen addiction, and privacy
        concerns also grow.
      </p>
      <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085" alt="Technology impact" />
    </section>

    <section>
      <h2>🎨 Digital Creativity</h2>
      <p>
        From memes to AI-generated art, creativity has found new forms in the digital era. Platforms like YouTube,
        TikTok, and Instagram have given everyone a stage to share their voices and ideas.
      </p>
      <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d" alt="Digital creativity" />
    </section>

    <section>
      <h2>🚀 The Future</h2>
      <p>
        With AI, virtual reality, blockchain, and the metaverse, digital culture is constantly evolving.
        The future promises more immersive experiences, smarter technologies, and deeper integration of the
        digital into everyday life.
      </p>
      <img src="https://images.unsplash.com/photo-1518770660439-4636190af475" alt="Future tech" />
    </section>

    <section>
      <h2>🤖 Artificial Intelligence</h2>
      <p>
        Dive into the world of AI—its power, influence, and how it’s shaping creativity and innovation.
      </p>
      <div class="video-container">
        <iframe
          src="https://www.youtube.com/embed/Fucnd9D35dg"
          title="AI Video"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen>
        </iframe>
      </div>
    </section>
  </div>

  <footer>
    <p>Made with ❤️ for the Wall Magazine Competition (BCA 1st sem) | Digital Culture</p>
  </footer>
</body>
</html>
