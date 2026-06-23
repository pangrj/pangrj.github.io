---
title: Pangrj
---

<style>
  :root {
    --ink: #141414;
    --muted: #5f6673;
    --line: #d8dce3;
    --link: #164f9f;
    --surface: #ffffff;
    --soft: #f5f7fb;
    --accent: #0f766e;
    --shadow: 0 12px 30px rgba(31, 41, 55, 0.08);
  }

  body {
    color: var(--ink);
    font-family: Georgia, "Times New Roman", Times, serif;
    font-size: 20px;
    line-height: 1.45;
  }

  a {
    color: var(--link);
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .page {
    max-width: 1160px;
    margin: 0 auto;
    padding: 28px 22px 56px;
  }

  .profile {
    display: grid;
    grid-template-columns: minmax(0, 1fr) 250px;
    gap: 44px;
    align-items: start;
    margin-bottom: 58px;
  }

  .profile h1 {
    margin: 0 0 30px;
    font-size: 42px;
    line-height: 1.12;
    letter-spacing: 0;
  }

  .role {
    margin: 0 0 12px;
    font-size: 28px;
    font-weight: 700;
  }

  .affiliation,
  .email,
  .links {
    margin: 0 0 24px;
  }

  .portrait {
    width: 250px;
    aspect-ratio: 1;
    object-fit: cover;
    border: 1px solid var(--line);
    background: var(--soft);
  }

  .section {
    margin-top: 42px;
  }

  .section h2 {
    margin: 0 0 14px;
    padding-bottom: 4px;
    border-bottom: 1px solid #aeb4bd;
    font-size: 31px;
    line-height: 1.2;
  }

  .bio p {
    margin: 0 0 24px;
  }

  .publications {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 18px;
    margin-top: 22px;
  }

  .pub-card {
    display: grid;
    grid-template-columns: 112px minmax(0, 1fr);
    gap: 16px;
    padding: 14px;
    border: 1px solid var(--line);
    border-radius: 8px;
    background: var(--surface);
    box-shadow: var(--shadow);
  }

  .pub-cover {
    width: 112px;
    aspect-ratio: 0.78;
    border: 1px solid #cfd5df;
    border-radius: 6px;
    object-fit: cover;
    background: var(--soft);
  }

  .pub-title {
    margin: 0 0 8px;
    font-size: 20px;
    line-height: 1.24;
    font-weight: 700;
  }

  .pub-authors,
  .pub-venue {
    margin: 0 0 8px;
    color: var(--muted);
    font-size: 16px;
    line-height: 1.35;
  }

  .pub-venue {
    color: #263241;
    font-style: italic;
  }

  .pub-links {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 12px;
  }

  .pub-links a {
    display: inline-flex;
    align-items: center;
    min-height: 28px;
    padding: 3px 10px;
    border: 1px solid #b8c4d6;
    border-radius: 999px;
    color: #123f7d;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 13px;
    line-height: 1;
  }

  .pub-links a:hover {
    border-color: var(--link);
    text-decoration: none;
  }

  @media (max-width: 760px) {
    body {
      font-size: 18px;
    }

    .profile {
      grid-template-columns: 1fr;
      gap: 22px;
    }

    .portrait {
      width: min(220px, 70vw);
      grid-row: 1;
    }

    .profile h1 {
      font-size: 34px;
    }

    .role {
      font-size: 24px;
    }

    .pub-card {
      grid-template-columns: 92px minmax(0, 1fr);
      gap: 12px;
    }

    .pub-cover {
      width: 92px;
    }
  }
</style>

<main class="page">
  <section class="profile">
    <div>
      <h1>Pangrj</h1>
      <p class="role">Researcher</p>
      <p class="affiliation">Beihang University</p>
      <p class="email">
        Email:<br>
        <a href="mailto:pangrj@buaa.edu.cn">pangrj@buaa.edu.cn</a>
      </p>
      <p class="links">
        [<a href="#" aria-label="Google Scholar">Google Scholar</a>]
        [<a href="#" aria-label="ORCID">ORCID</a>]
        [<a href="https://github.com/pangrj" aria-label="GitHub">GitHub</a>]
      </p>
    </div>
    <img class="portrait" src="assets/profile-placeholder.svg" alt="Portrait placeholder">
  </section>

  <section class="section bio">
    <h2>Short Bio</h2>
    <p>
      Pangrj is a researcher at <a href="https://www.buaa.edu.cn/">Beihang University</a>.
      His research interests include artificial intelligence, data-driven modeling,
      and intelligent systems. He is interested in building practical AI methods
      that connect computational models with real-world scientific and engineering problems.
    </p>
    <p>
      This homepage collects selected publications and research outputs. More details
      will be added as the publication list is updated.
    </p>
  </section>

  <section class="section">
    <h2>Publications</h2>
    <div class="publications">
      <article class="pub-card">
        <img class="pub-cover" src="assets/covers/publication-1.svg" alt="Publication cover">
        <div>
          <h3 class="pub-title">From Embodied AI to Cobodied AI</h3>
          <p class="pub-authors"><strong>Pangrj</strong> et al.</p>
          <p class="pub-venue">ScienceDirect article, 2026</p>
          <div class="pub-links">
            <a href="https://www.sciencedirect.com/science/article/pii/S2096579626000161">Paper</a>
            <a href="#">Code</a>
            <a href="#">Project</a>
          </div>
        </div>
      </article>

      <article class="pub-card">
        <img class="pub-cover" src="assets/covers/publication-2.svg" alt="Publication cover">
        <div>
          <h3 class="pub-title">Selected Publication Title</h3>
          <p class="pub-authors"><strong>Pangrj</strong>, Coauthor A, Coauthor B</p>
          <p class="pub-venue">Conference or Journal, Year</p>
          <div class="pub-links">
            <a href="#">Paper</a>
            <a href="#">Code</a>
          </div>
        </div>
      </article>

      <article class="pub-card">
        <img class="pub-cover" src="assets/covers/publication-3.svg" alt="Publication cover">
        <div>
          <h3 class="pub-title">Selected Publication Title</h3>
          <p class="pub-authors"><strong>Pangrj</strong>, Coauthor A, Coauthor B</p>
          <p class="pub-venue">Conference or Journal, Year</p>
          <div class="pub-links">
            <a href="#">Paper</a>
            <a href="#">Project</a>
          </div>
        </div>
      </article>
    </div>
  </section>
</main>
