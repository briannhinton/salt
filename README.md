<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This is an opinionated, and simple starter CSS file to use an alternative to a large framework.

<p align="center">(<a href="#top">back to top</a>)</p>

### Built With

* [Code](https://code.visualstudio.com)

<p align="center">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get started follow these simple example steps.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/mrbrianhinton/css-starter
   ```
3. Update any CSS variables (color for instance)
   ```css
   :root {
   /* Before */
   --color-white: #fff;
   /* Updated */
   --color-white: #fafafa;
   }
   ```
4. The import the stylesheet into your project
   ```html
   <link rel="stylesheet" src="styles.css">
   ```

<p align="center">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

To use the starter reference the variables when shaping the CSS for your layouts.

```css
:root {
   /* Spacing */
  --space-eighth: 0.2rem;

  /* Font Weights */
  --weight-regular: 400;
}

.header {
  padding: var(--space-eighth);
  font-weight: var(--weight-regular);
}
```

The advantage of a simple starter is that it's all about mixing in your own styles, and you can take advantage of modern CSS without it having to be baked into the framework you are using.

```css
@container sidebar (min-width: 400px){
  .card {
    display: grid;
    grid-template-columns: 2fr 1fr;
    padding: var(--space-quad);
  }
}
```

Then you can keep adding, and growing when you see patterns emerge.

<p align="center">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] Clean up default fonts, and set a new opinionated default font
- [ ] Add more helpers for Flex and Grid

See the [open issues](https://github.com/mrbrianhinton/css-starter/issues) for a full list of proposed features (and known issues).

<p align="center">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'feat: add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="center">(<a href="#top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="center">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Brian Hinton - [@RealTinyPenguin](https://twitter.com/RealTinyPenguin)

<p align="center">(<a href="#top">back to top</a>)</p>
