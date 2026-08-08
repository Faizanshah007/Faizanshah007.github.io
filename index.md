## Portfolio

<div class="portfolio-links">
  <a href="https://github.com/Faizanshah007">GitHub</a>
  <span aria-hidden="true">|</span>
  <a href="https://www.linkedin.com/in/faizanshah-ansari-gamedev/">LinkedIn</a>
</div>

Game programmer focused on designing extensible systems that integrate well with the wider codebase, improving developer workflows and tracking down the bugs that emerge between systems.

<div class="projects-container">
  <div class="project-tabs-container">
    <div class="project-tabs" role="tablist" aria-label="Project categories">
      <button type="button" class="project-tab active" role="tab" aria-selected="true" aria-controls="professional-projects" data-project-tab="professional-projects">Professional Projects</button>
      <button type="button" class="project-tab" role="tab" aria-selected="false" aria-controls="university-projects" data-project-tab="university-projects">University Projects</button>
    </div>
  </div>

  <div class="project-content">
<div id="professional-projects" class="project-panel" role="tabpanel">
<div>
  <table>
    <tr>
      <td valign="top"><h3>
        <li><a href="https://www.exodusgame.com/en-US">Exodus</a></li>
        <p><code>Unreal Engine 5</code> <code>C++</code> <code>Blueprints</code></p>
        <p>Gameplay systems, editor tooling and targeted engine improvements.</p>
        <button class="video-thumbnail" type="button" data-video-id="OcED8x2LsXE" data-video-title="Exodus gameplay video" aria-label="Play Exodus gameplay video">
          <img src="ExodusGameplayThumbnail.png" alt="Exodus Extended Gameplay Reveal thumbnail">
        </button>
        <br><br>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/_c80LMt_Uxs?si=I7aiEYL2_mvS5Kx5&mute=1" title="Exodus additional video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
      </h3></td>
      <td valign="top"><h3>
        <li><a href="https://www.futurlab.co.uk/games/powerwash-simulator-2">PowerWash Simulator 2</a></li>
        <p><code>Unity 6</code> <code>C#</code></p>
        <p>Game stability, release support, cross-platform multiplayer and split-screen work.</p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/gP7i0rnNRkE?si=RGg_OystvMY10bKu&mute=1" title="PowerWash Simulator 2 video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <br><br>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/-rLMus-sx1I?si=FZQqSA25SrkkI6O4&mute=1" title="PowerWash Simulator 2 additional video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
      </h3></td>
    </tr>
  </table>
</div>
</div>

<div id="university-projects" class="project-panel" role="tabpanel" hidden>
<div>
  <table>
    <tr>
      <td colspan="2" align="center" valign="top"><h3>
        <li><a href="https://github.com/Faizanshah007/Spitoon-TeamProject">Spitoon - Team Project</a></li>
        <p><code>Custom Engine</code> <code>C++</code></p>
        <button class="video-thumbnail" type="button" data-video-id="gx8T80bnTCk" data-video-title="Spitoon team project video" aria-label="Play Spitoon team project video">
          <img src="TeamProjectThumbnail.png" alt="Spitoon team project gameplay thumbnail">
        </button>
      </h3></td>
    </tr>
    <tr>
      <td valign="top"><h3>
        <li><a href="https://github.com/Faizanshah007/Advanced-Graphics-for-Games">Tropical Island</a></li>
        <p><code>Custom Engine</code> <code>C++</code></p>
        <button class="video-thumbnail" type="button" data-video-id="HFE6a5WwDNY" data-video-title="Tropical Island video" aria-label="Play Tropical Island video">
          <img src="GraphicsThumbnail.png" alt="Tropical Island graphics project thumbnail">
        </button>
      </h3></td>
      <td valign="top"><h3>
        <li><a href="https://github.com/Faizanshah007/Advanced-Game-Technologies">Game Engine (Physics)</a></li>
        <p><code>Custom Engine</code> <code>C++</code></p>
        <button class="video-thumbnail" type="button" data-video-id="g7kDU1J3jcs" data-video-title="Game Engine C++ physics video" aria-label="Play Game Engine physics video">
          <img src="PhysicsGameEngineThumbnail.png" alt="Game Engine physics project thumbnail">
        </button>
      </h3></td>
    </tr>
  </table>
</div>
  </div>
</div>
</div>

<style>
  .portfolio-links {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    margin: 0 0 1.5rem;
    padding: 0;
    text-align: left;
  }

  .projects-container {
    width: 100%;
    margin: 1.75rem 0 0;
    border: 1px solid #8c959f;
    border-radius: 8px;
    box-sizing: border-box;
    overflow: hidden;
    background: rgba(127, 127, 127, 0.02);
  }

  /* One natural tab bar inside the outer project container. */
  .project-tabs-container {
    width: 100%;
    margin: 0;
    padding: 0;
    border-bottom: 1px solid #8c959f;
    box-sizing: border-box;
  }

  .project-tabs {
    display: grid;
    grid-template-columns: 1fr 1fr;
    width: 100%;
    margin: 0;
    padding: 0;
  }

  .project-tab {
    appearance: none;
    width: 100%;
    min-width: 0;
    margin: 0;
    padding: 1rem 1.25rem;
    border: 0;
    border-radius: 0;
    background: transparent;
    color: inherit;
    font: inherit;
    font-weight: 600;
    text-align: center;
    cursor: pointer;
    transition: background-color 120ms ease, color 120ms ease;
  }

  /* The only internal tab border: one divider between left and right. */
  .project-tab + .project-tab {
    border-left: 1px solid #8c959f;
  }

  .project-tab:hover {
    background: rgba(127, 127, 127, 0.08);
  }

  .project-tab.active {
    background: rgba(9, 105, 218, 0.12);
    color: #0969da;
  }

  .project-tab:focus-visible {
    outline: 2px solid #0969da;
    outline-offset: -2px;
  }

  .project-content {
    width: 100%;
    margin: 0;
    padding: 1rem;
    box-sizing: border-box;
  }

  .project-panel,
  .project-panel > div,
  .project-panel table {
    width: 100%;
    max-width: 100%;
    box-sizing: border-box;
  }

  .project-panel table {
    margin: 0;
    table-layout: fixed;
    border-collapse: collapse;
  }

  .project-panel td {
    width: 50%;
    min-width: 0;
    box-sizing: border-box;
    padding: 0.5rem 0.75rem;
    vertical-align: top;
    overflow-wrap: anywhere;
  }

  .project-panel td:first-child {
    padding-left: 0;
  }

  .project-panel td:last-child {
    padding-right: 0;
  }

  .project-panel td[colspan="2"] {
    width: 100%;
    padding-left: 0;
    padding-right: 0;
  }

  /* Make every project video fill its column instead of staying at 560px. */
  .project-panel iframe {
    display: block;
    width: 100%;
    max-width: 100%;
    height: auto;
    aspect-ratio: 16 / 9;
    box-sizing: border-box;
  }

  /* Custom video previews: sharp 16:9 images that become YouTube players on click. */
  .video-thumbnail {
    display: block;
    width: 100%;
    max-width: 100%;
    aspect-ratio: 16 / 9;
    margin: 0;
    padding: 0;
    border: 0;
    background: #000;
    cursor: pointer;
    overflow: hidden;
    box-sizing: border-box;
  }

  .video-thumbnail img {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .video-thumbnail:focus-visible {
    outline: 2px solid #0969da;
    outline-offset: 2px;
  }

  .project-panel[hidden] {
    display: none;
  }

  @media (max-width: 760px) {
    .project-content {
      padding: 0.75rem;
    }

    .project-panel table,
    .project-panel tbody,
    .project-panel tr,
    .project-panel td {
      display: block;
      width: 100%;
    }

    .project-panel td {
      padding: 0.5rem 0 1rem;
    }
  }
</style>

<script>
  document.querySelectorAll('.video-thumbnail').forEach((thumbnail) => {
    thumbnail.addEventListener('click', () => {
      const iframe = document.createElement('iframe');
      iframe.src = `https://www.youtube.com/embed/${thumbnail.dataset.videoId}?autoplay=1&mute=1`;
      iframe.title = thumbnail.dataset.videoTitle;
      iframe.frameBorder = '0';
      iframe.allow = 'accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share';
      iframe.referrerPolicy = 'strict-origin-when-cross-origin';
      iframe.allowFullscreen = true;
      thumbnail.replaceWith(iframe);
    });
  });

  document.querySelectorAll('[data-project-tab]').forEach((tab) => {
    tab.addEventListener('click', () => {
      const targetId = tab.dataset.projectTab;

      document.querySelectorAll('[data-project-tab]').forEach((item) => {
        const isActive = item === tab;
        item.classList.toggle('active', isActive);
        item.setAttribute('aria-selected', isActive ? 'true' : 'false');
      });

      document.querySelectorAll('.project-panel').forEach((panel) => {
        panel.hidden = panel.id !== targetId;
      });
    });
  });
</script>
