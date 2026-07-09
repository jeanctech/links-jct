<script>
  let link_one = "https://jeanctech.netlify.app/";
  let link_two = "https://github.com/jeanctech/portfolio";
</script>

<main>
  <div id="app">
    <header>
      <h1>⚡ Links·Jct</h1>
    </header>

    <div class="info">
      <p><strong>✦ Mis proyectos, entradas y experimentos</strong></p>
      <p class="text-muted">
        Una galería visual con los trabajos que he creado. <br
          class="hide-on-mobile"
        /> Cada tarjeta contiene el enlace a la web y al repositorio.
      </p>
    </div>

    <h2 class="gallery-title">💻 Proyectos</h2>
    <div class="gallery-grid">

      <article class="project-card">
        <h3>👨‍💻 Portfolio <span>v2</span></h3>
        <span class="tech">✦ Astro · Tailwind · Vite</span>
        <p class="desc">
          <cite
            >✨ Un portfolio limpio, con enfoque en rendimiento y diseño.</cite
          >
        </p>
        <div class="btn-group">
          <button
            ><a
              href={link_one}
              target="_blank"
              rel="noopener noreferrer">🌐 Ver Web</a
            ></button
          >
          <button
            ><a
              href={link_two}
              target="_blank"
              rel="noopener noreferrer">👀 Código</a
            ></button
          >
        </div>
      </article>

      <article class="project-card">
        <h3>🎨 UI Lab <span>experimental</span></h3>
        <span class="tech">✦ Svelte · CSS · Bun</span>
        <p class="desc">
          <cite>Componentes interactivos y micro-interacciones con Svelte.</cite
          >
        </p>
        <div class="btn-group">
          <button
            ><a
              href="https://jeanctech.netlify.app/"
              target="_blank"
              rel="noopener noreferrer">🌐 Ver Web</a
            ></button
          >
          <button
            ><a
              href="https://github.com/jeanctech/portfolio"
              target="_blank"
              rel="noopener noreferrer">👀 Código</a
            ></button
          >
        </div>
      </article>

      <article class="project-card">
        <h3>📝 Blog·dev <span>personal</span></h3>
        <span class="tech">✦ Astro · MDX · Netlify</span>
        <p class="desc">
          <cite>Artículos sobre desarrollo, diseño y herramientas.</cite>
        </p>
        <div class="btn-group">
          <button
            ><a
              href="https://jeanctech.netlify.app/"
              target="_blank"
              rel="noopener noreferrer">🌐 Ver Web</a
            ></button
          >
          <button
            ><a
              href="https://github.com/jeanctech/portfolio"
              target="_blank"
              rel="noopener noreferrer">👀 Código</a
            ></button
          >
        </div>
      </article>

      <article class="project-card">
        <h3>🧩 Components <span>library</span></h3>
        <span class="tech">✦ Svelte · Storybook · Vite</span>
        <p class="desc">
          <cite>Colección de componentes reutilizables y documentados.</cite>
        </p>
        <div class="btn-group">
          <button
            ><a
              href="https://jeanctech.netlify.app/"
              target="_blank"
              rel="noopener noreferrer">🌐 Ver Web</a
            ></button
          >
          <button
            ><a
              href="https://github.com/jeanctech/portfolio"
              target="_blank"
              rel="noopener noreferrer">👀 Código</a
            ></button
          >
        </div>
      </article>

      <article class="project-card">
        <h3>⚡ Dash·kit <span>analytics</span></h3>
        <span class="tech">✦ Vue · Chart.js · Tailwind</span>
        <p class="desc">
          <cite
            >Dashboard ligero para visualización de datos en tiempo real.</cite
          >
        </p>
        <div class="btn-group">
          <button
            ><a
              href="https://jeanctech.netlify.app/"
              target="_blank"
              rel="noopener noreferrer">🌐 Ver Web</a
            ></button
          >
          <button
            ><a
              href="https://github.com/jeanctech/portfolio"
              target="_blank"
              rel="noopener noreferrer">👀 Código</a
            ></button
          >
        </div>
      </article>

      <article class="project-card">
        <h3>🖌️ Palette·pro <span>design</span></h3>
        <span class="tech">✦ React · Framer · CSS vars</span>
        <p class="desc">
          <cite>Generador de paletas y temas con vista previa en vivo.</cite>
        </p>
        <div class="btn-group">
          <button
            ><a
              href="https://jeanctech.netlify.app/"
              target="_blank"
              rel="noopener noreferrer">🌐 Ver Web</a
            ></button
          >
          <button
            ><a
              href="https://github.com/jeanctech/portfolio"
              target="_blank"
              rel="noopener noreferrer">👀 Código</a
            ></button
          >
        </div>
      </article>
    </div>

    <footer>
      <fieldset>
        <p>
          <strong
            >✦ Creado con Svelte + Vite + Bun · Rose Pine Theme · Netlify</strong
          >
        </p>
        <br>
        <p><code>Creado por @jeanctech · 2025</code></p>
      </fieldset>
    </footer>
  </div>
</main>

<style>
</style>
