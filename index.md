## Portfolio

<div>
  <table>
    <tr>
      <td align="left">
        <a href="https://github.com/Faizanshah007">GitHub</a> |
        <a href="https://www.linkedin.com/in/faizanshah-ansari-gamedev/">LinkedIn</a>
      </td>
    </tr>
  </table>
</div>

Game programmer focused on designing extensible systems that integrate well with the wider codebase, improving developer workflows and tracking down the bugs that emerge between systems.

<div class="project-tabs" role="tablist" aria-label="Project categories">
  <button type="button" class="project-tab active" role="tab" aria-selected="true" aria-controls="professional-projects" data-project-tab="professional-projects">Professional Projects</button>
  <button type="button" class="project-tab" role="tab" aria-selected="false" aria-controls="university-projects" data-project-tab="university-projects">University Projects</button>
</div>

<div id="professional-projects" class="project-panel" role="tabpanel">
<div>
  <table>
    <tr>
      <td valign="top"><h3>
        <li><a href="https://www.exodusgame.com/en-US">Exodus</a></li>
        <p><code>Unreal Engine 5</code> <code>C++</code> <code>Blueprints</code></p>
        <p>Gameplay systems, editor tooling and targeted engine improvements.</p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/OcED8x2LsXE?si=VSKeAejo9BflwyDF&mute=1" title="Exodus video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
        <iframe width="560" height="315" src="https://www.youtube.com/embed/gx8T80bnTCk?mute=1" title="Spitoon team project video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      </h3></td>
    </tr>
    <tr>
      <td valign="top"><h3>
        <li><a href="https://github.com/Faizanshah007/Advanced-Graphics-for-Games">Tropical Island</a></li>
        <p><code>Custom Engine</code> <code>C++</code></p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/HFE6a5WwDNY?mute=1" title="Tropical Island video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      </h3></td>
      <td valign="top"><h3>
        <li><a href="https://github.com/Faizanshah007/Advanced-Game-Technologies">Game Engine (Physics)</a></li>
        <p><code>Custom Engine</code> <code>C++</code></p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/g7kDU1J3jcs?mute=1" title="Game Engine C++ physics video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      </h3></td>
    </tr>
  </table>
</div>
</div>

<style>
  .project-tabs {
    display: flex;
    gap: 0.25rem;
    margin: 1.5rem 0 1rem;
    border-bottom: 1px solid #d0d7de;
  }

  .project-tab {
    appearance: none;
    background: transparent;
    border: 0;
    border-bottom: 2px solid transparent;
    padding: 0.65rem 1rem;
    color: inherit;
    font: inherit;
    font-weight: 600;
    cursor: pointer;
  }

  .project-tab:hover {
    border-bottom-color: #8c959f;
  }

  .project-tab.active {
    border-bottom-color: #0969da;
    color: #0969da;
  }

  .project-tab:focus-visible {
    outline: 2px solid #0969da;
    outline-offset: 2px;
  }

  .project-panel[hidden] {
    display: none;
  }
</style>

<script>
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
