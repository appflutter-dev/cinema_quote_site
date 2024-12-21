<script>
  import "./styles/global.css";
  import Header from "./components/Header.svelte";
  import Downloads from "./components/Downloads.svelte";
  import Legal from "./components/Legal.svelte";
  import PrivacyPolicy from "./components/PrivacyPolicy.svelte";
  import GdprNotice from "./components/GdprNotice.svelte";
</script>

<Header />
<main>
  <section class="about">
    <h2>Cinema Quote</h2>
    <div class="short-description">
      <h3>Dive into the world of movies with our engaging cinema quiz app.</h3>
    </div>
    <div class="detailed-description">
      <p>
        Step into the captivating universe of Cinema Quote! This engaging mobile
        application challenges you to guess the movie title based on iconic
        quotes. Designed with movie buffs in mind, it offers an interactive,
        fun, and rewarding experience for all cinema lovers.
      </p>
      <p>
        To make things even more exciting, hints are available in the form of
        emojis. These creative and entertaining clues help guide you to the
        correct movie title when you’re stuck, adding a unique twist to the
        game.
      </p>
      <p>
        Relive your favorite cinematic moments, expand your knowledge of movie
        history, and share the fun with friends. Whether you’re a casual fan or
        a hardcore movie lover, Cinema Quote is the perfect app for relaxing
        entertainment or friendly competition.
      </p>
    </div>
    <div class="features">
      <h3>Features</h3>
      <ul>
        <li>Guess movie titles from a diverse collection of iconic quotes.</li>
        <li>Use creative emoji hints to uncover the answers.</li>
        <li>Easy-to-use interface with stunning visuals.</li>
        <li>Hundreds of quotes to challenge your cinema knowledge.</li>
        <li>Engaging gameplay suitable for all ages and interests.</li>
      </ul>
    </div>
  </section>
  <Downloads />
  <PrivacyPolicy />
  <GdprNotice />
  <Legal />
</main>

<style>
  .about {
    max-width: 800px;
    margin: 2rem auto;
    padding: 2rem;
    background: #f9f9f9;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  .about h2 {
    text-align: center;
    color: #4caf50;
    margin-bottom: 1rem;
  }

  .short-description {
    text-align: center;
    margin-bottom: 2rem;
  }

  .short-description h3 {
    color: #333;
    font-size: 1.25rem;
  }

  .detailed-description {
    margin-bottom: 2rem;
  }

  .detailed-description p {
    line-height: 1.6;
    margin-bottom: 1rem;
  }

  .features {
    margin-top: 2rem;
  }

  .features h3 {
    color: #4caf50;
    margin-bottom: 1rem;
  }

  .features ul {
    list-style-type: disc;
    padding-left: 1.5rem;
  }

  .features li {
    margin-bottom: 0.5rem;
    line-height: 1.6;
  }
</style>
