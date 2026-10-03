<p align="right">
  <a href="README.md"><img src="https://img.shields.io/badge/English-30363D?style=flat-square" alt="Read in English"></a>
  <img src="https://img.shields.io/badge/Espa%C3%B1ol-0A84FF?style=flat-square" alt="Español (actual)">
</p>

<div align="center">
  <img src="banner.svg" alt="Facundo Guarnier (Guarnold) - Software Engineer, full-stack e IA aplicada. Mendoza, Argentina." width="100%">
</div>

<p align="center">
  <br>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
</p>

<p align="center">
  Ingeniero en Informática que construye productos full-stack con IA en cada capa: como herramienta de desarrollo,
  como funcionalidad dentro de las apps que entrego y como pipeline generativo local.
</p>

<h2 align="center">🤖 Construyo con IA</h2>

<table>
  <tr>
    <td width="25%" valign="top" align="center">
      <b>Ingeniería asistida<br>por IA</b><br><br>
      <sub>Agentes de código con límites que hacen cumplir las herramientas y reglas escritas. Detalles más abajo.</sub><br><br>
      <img src="https://img.shields.io/badge/-Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code"> <img src="https://img.shields.io/badge/-Antigravity-4285F4?style=flat-square" alt="Antigravity"> <img src="https://img.shields.io/badge/-MCP-0A84FF?style=flat-square" alt="MCP"> <img src="https://img.shields.io/badge/-Agents-0A84FF?style=flat-square" alt="Agents"> <img src="https://img.shields.io/badge/-Prompt_engineering-0A84FF?style=flat-square" alt="Prompt engineering">
    </td>
    <td width="25%" valign="top" align="center">
      <b>Productos con<br>LLMs</b><br><br>
      <sub>De fotos a registros estructurados, asistentes dentro de la app con la API key del propio usuario (BYOK), recuperación de información y agentes.</sub><br><br>
      <img src="https://img.shields.io/badge/-Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API"> <img src="https://img.shields.io/badge/-OpenAI_API-412991?style=flat-square" alt="OpenAI API"> <img src="https://img.shields.io/badge/-OpenRouter-6467F2?style=flat-square&logo=openrouter&logoColor=white" alt="OpenRouter"> <img src="https://img.shields.io/badge/-RAG-0A84FF?style=flat-square" alt="RAG">
    </td>
    <td width="25%" valign="top" align="center">
      <b>IA generativa<br>local</b><br><br>
      <sub>Pipelines de imágenes en mi propia GPU, ajustados a un presupuesto de 16 GB de VRAM, con personajes consistentes.</sub><br><br>
      <img src="https://img.shields.io/badge/-ComfyUI-0A84FF?style=flat-square" alt="ComfyUI"> <img src="https://img.shields.io/badge/-FLUX.1-0A84FF?style=flat-square" alt="FLUX.1"> <img src="https://img.shields.io/badge/-PuLID-0A84FF?style=flat-square" alt="PuLID"> <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
    </td>
    <td width="25%" valign="top" align="center">
      <b>ML y visión<br>por computadora</b><br><br>
      <sub>Clasificación y reconocimiento en tiempo real. Tesis sobre control de semáforos con IA: hasta un 58% menos de tiempo de espera en simulaciones.</sub><br><br>
      <img src="https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"> <img src="https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
    </td>
  </tr>
</table>

<h2 align="center">Cómo trabajo con agentes de código</h2>

<p align="center">
  Programo con Claude Code y Antigravity. Lo que mantiene eso bajo control, separado entre
  lo que hacen cumplir las herramientas y lo que es una regla escrita.
</p>

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <b>Lo hacen cumplir las herramientas</b>
      <ul>
        <li><code>main</code> está protegida en casi todos mis repos de apps: los cambios entran solo por pull request.</li>
        <li>Cada repo tiene una lista de comandos permitidos para el agente. Lo que queda afuera necesita mi aprobación.</li>
        <li>Hooks de Claude Code revisan las migraciones de base de datos mientras el agente las escribe.</li>
        <li>El pre-commit corre escaneo de secretos (gitleaks), lint y chequeo de tipos en cada commit.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <b>Reglas escritas que sigue el agente</b> <sub>(<code>AGENTS.md</code>)</sub>
      <ul>
        <li>Los agentes commitean y nunca pushean. El merge a <code>main</code> lo hago yo.</li>
        <li>Plan primero para todo lo que toca la base de datos, los permisos o varios archivos.</li>
        <li>Una tarea está lista solo si se corrieron build, lint y tests, y si algo falla se informa la salida real.</li>
        <li>Si falta información, el agente pregunta en lugar de inventarla.</li>
      </ul>
    </td>
  </tr>
</table>

<h2 align="center">⚡ Tecnologías</h2>

<p align="center">
  <img src="https://img.shields.io/badge/USO_DIARIO-0A84FF?style=for-the-badge" alt="Uso diario">
</p>

<table width="100%">
  <tr>
    <td width="170"><b>Lenguajes</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=py,ts,dart,postgres" alt="py, ts, dart, postgres"><br><sub>Python · TypeScript · Dart · SQL (PostgreSQL)</sub></td>
  </tr>
  <tr>
    <td width="170"><b>Frontend y mobile</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=react,flutter,tailwind,vite" alt="react, flutter, tailwind, vite"><br><sub>React · Flutter · Tailwind CSS · Vite</sub></td>
  </tr>
  <tr>
    <td width="170"><b>Backend y datos</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=fastapi,supabase" alt="fastapi, supabase"> <img src="https://img.shields.io/badge/-Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white" alt="Shopify"><br><sub>FastAPI · Supabase · Shopify (Storefront)</sub></td>
  </tr>
  <tr>
    <td width="170"><b>Cloud y DevOps</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=docker,git,azure,netlify" alt="docker, git, azure, netlify"><br><sub>Docker · Git · Azure · Netlify</sub></td>
  </tr>
  <tr>
    <td width="170"><b>Herramientas y flujo</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=bash,vscode" alt="bash, vscode"><br><sub>Bash · VS Code · Scrum · Git Flow</sub></td>
  </tr>
</table>

<p align="center">
  <img src="https://img.shields.io/badge/EXPERIENCIA_PREVIA-5C7DB8?style=for-the-badge" alt="Experiencia previa"><br>
  <sub>Proyectos académicos y anteriores. Me defiendo, pero estoy oxidado.</sub>
</p>

<table width="100%">
  <tr>
    <td width="170"><b>Ecosistema Java</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=java,spring&theme=light" alt="java, spring"> <img src="https://img.shields.io/badge/-JHipster-5C3EE8?style=flat-square" alt="JHipster"><br><sub>Java · Spring Boot · JHipster</sub></td>
  </tr>
  <tr>
    <td width="170"><b>Web</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=angular,bootstrap&theme=light" alt="angular, bootstrap"><br><sub>Angular · Bootstrap</sub></td>
  </tr>
  <tr>
    <td width="170"><b>Datos y Python</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=flask,mongodb,mysql,elasticsearch&theme=light" alt="flask, mongodb, mysql, elasticsearch"><br><sub>Flask · MongoDB · MySQL · Elasticsearch</sub></td>
  </tr>
  <tr>
    <td width="170"><b>Testing y CI</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=cypress,selenium,jenkins&theme=light" alt="cypress, selenium, jenkins"><br><sub>Cypress · Selenium · Jenkins</sub></td>
  </tr>
  <tr>
    <td width="170"><b>ML e infraestructura</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=pytorch,kubernetes&theme=light" alt="pytorch, kubernetes"><br><sub>PyTorch · Kubernetes</sub></td>
  </tr>
</table>

<h2 align="center">🎓 Aprendiendo ahora</h2>

<p align="center">
  <img src="https://img.shields.io/badge/-Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud"> <img src="https://img.shields.io/badge/-Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks">
</p>

<h2 align="center">💻 Hardware</h2>

<p align="center">
  <img src="https://img.shields.io/badge/Escritorio-Ryzen_5_9600X-ED1C24?style=flat-square&logo=amd&logoColor=white" alt="Escritorio: Ryzen 5 9600X">
  <img src="https://img.shields.io/badge/GPU-RTX_4060_Ti_16_GB-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="GPU: RTX 4060 Ti 16 GB">
  <img src="https://img.shields.io/badge/Notebook-Core_i5_1035G1-0071C5?style=flat-square&logo=intel&logoColor=white" alt="Notebook: Core i5-1035G1">
  <img src="https://img.shields.io/badge/Servidor_casero-Ryzen_5_5600G_%2B_48_GB_RAM-ED1C24?style=flat-square&logo=amd&logoColor=white" alt="Servidor casero: Ryzen 5 5600G, 48 GB RAM"><br>
  <sub>Fuera del código: domótica, electrónica, hardware, videojuegos y economía · Español (nativo), Inglés (B2)</sub>
</p>

<p align="center">
  <a href="https://guarnold.com.ar/"><img src="https://img.shields.io/badge/PORTFOLIO-guarnold.com.ar-0A84FF?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/facundo-guarnier/"><img src="https://img.shields.io/badge/LINKEDIN-facundo--guarnier-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
</p>
