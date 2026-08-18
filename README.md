<div align="center">

# Robo Cat vs Objects on Table

A simulated robo-cat that learns to clear a table.

**Marcel Padilla**, ETH Zürich

<img src="assets/thumbnail.png" alt="The robo-cat walking up to an object on the table and pushing it over the edge" width="100%">

<sub>Robo cat doesn't like objects.</sub>

<a href="https://marcelpadilla.com/Projects/robo_cat/index.html"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/button-project-page-dark.png">
  <img src="assets/button-project-page-light.png" alt="Project Page" width="137" height="44">
</picture></a>

</div>

Open [`index.html`](index.html) in a browser. It is one self-contained file: the
physics engine, the scene, the networks and the sounds are all inside it, so it needs
no server and no network, and it fills the window it is opened in.

## License

MIT, except the physics engine: the page embeds the MuJoCo WebAssembly build,
Apache 2.0, whose notice ships beside it in [`NOTICE.txt`](NOTICE.txt).
