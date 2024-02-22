- 👋 Hi, I’m @WebdDveloper1
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
- <!--- HTML-FILE --->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;700&display=swap"
      rel="stylesheet"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="assets/images/favicon-32x32.png"
    />
    <link rel="stylesheet" href="style.css" />
    <title>Frontend Mentor | Single-page developer portfolio</title>
  </head>
  <body>
    <header class="header">
      <h2 class="visually-hidden">Header</h2>
      <div class="wrapper">
        <nav class="header__nav">
          <h2 class="visually-hidden">Navigation</h2>
          <a href="index.html" class="header__home">
            Ravshan
            <span class="visually-hidden">(to home page)</span>
          </a>
          <a href="https://github.com/abdurahmon999" class="header__social">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="25"
              height="24"
              aria-labelledby="socialGitHub"
              role="img"
            >
              <title id="socialGitHub">GitHub</title>
              <path
                fill="#FFF"
                fill-rule="evenodd"
                d="M12.304 0C5.506 0 0 5.506 0 12.304c0 5.444 3.522 10.042 8.413 11.672.615.108.845-.261.845-.584 0-.292-.015-1.261-.015-2.291-3.091.569-3.891-.754-4.137-1.446-.138-.354-.738-1.446-1.261-1.738-.43-.23-1.046-.8-.016-.815.97-.015 1.661.892 1.892 1.261 1.107 1.86 2.876 1.338 3.584 1.015.107-.8.43-1.338.784-1.646-2.738-.307-5.598-1.368-5.598-6.074 0-1.338.477-2.446 1.26-3.307-.122-.308-.553-1.569.124-3.26 0 0 1.03-.323 3.383 1.26.985-.276 2.03-.415 3.076-.415 1.046 0 2.092.139 3.076.416 2.353-1.6 3.384-1.261 3.384-1.261.676 1.691.246 2.952.123 3.26.784.861 1.26 1.953 1.26 3.307 0 4.721-2.875 5.767-5.613 6.074.446.385.83 1.123.83 2.277 0 1.645-.015 2.968-.015 3.383 0 .323.231.708.846.584a12.324 12.324 0 0 0 8.382-11.672C24.607 5.506 19.101 0 12.304 0Z"
              />
            </svg>
          </a>
          <a href="https://www.instagram.com/x_abdurahmon309/" class="header__social">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="25"
              height="24"
              aria-labelledby="socialLinkedIn"
              role="img"
            >
              <title id="socialLinkedIn">Instagram</title>
              <path
                fill="#FFF"
                fill-rule="evenodd"
                d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"
              />
            </svg>
          </a>
          <a href="https://twitter.com/Abdurahmon_X" class="header__social">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="20"
              aria-labelledby="socialTwitter"
              role="img"
            >
              <title id="socialTwitter">Twitter</title>
              <path
                fill="#FFF"
                d="M23.492 2.705a9.563 9.563 0 0 1-2.742.751 4.788 4.788 0 0 0 2.1-2.643 9.536 9.536 0 0 1-3.033 1.159 4.778 4.778 0 0 0-8.14 4.357 13.564 13.564 0 0 1-9.844-4.99 4.774 4.774 0 0 0-.646 2.4 4.778 4.778 0 0 0 2.124 3.977 4.765 4.765 0 0 1-2.163-.598v.061a4.778 4.778 0 0 0 3.832 4.684 4.812 4.812 0 0 1-2.158.082 4.78 4.78 0 0 0 4.462 3.316 9.584 9.584 0 0 1-5.932 2.045c-.38 0-.762-.022-1.14-.067a13.508 13.508 0 0 0 7.32 2.146c8.787 0 13.59-7.277 13.59-13.589 0-.205-.004-.412-.013-.617a9.71 9.71 0 0 0 2.381-2.471l.002-.003Z"
              />
            </svg>
          </a>
        </nav>
      </div>
    </header>

    <main id="main">
      <section class="hero">
        <div class="wrapper hero__wrapper bottom-border">
          <div class="hero__content">
            <picture>
              <source
                media="(min-width: 62.5em)"
                srcset=""
              />
              <source
                media="(min-width: 37.5em)"
                srcset=""
              />
              <img
                class="hero__image"
                src="index.html"
                alt=""
                width-="174"
                height="383"
              />
            </picture>
            <img
              class="hero__rings"
              src="assets/images/pattern-rings.svg"
              alt=""
              width="530"
              height="129"
            />
            <img
              class="hero__circle"
              src="assets/images/pattern-circle.svg"
              alt=""
              width="129"
              height="129"
            />
            <div class="hero__text">
              <h1 class="hero__headline header-xl">
                Nice to<br />
                meet you! I'm <span>Ravshan</span>.
              </h1>
              <p class="hero__description">
                Based in the Uzbekistan, I'm a Fullstack developer passionate about
                building accessible web apps that users love.
              </p>
              <a href="index.html#contact" class="hero__contact underline">Contact me</a>
            </div>
          </div>
        </div>
      </section>

      <section class="skills">
        <div class="wrapper skills__wrapper bottom-border">
          <h2 class="visually-hidden">Skills</h2>
          <div class="skills__item">
            <h3 class="skills__title">HTML</h3>
            <p class="skills__description">No Experience</p>
          </div>
          <div class="skills__item">
            <h3 class="skills__title">CSS</h3>
            <p class="skills__description">No Experience</p>
          </div>
          <div class="skills__item">
            <h3 class="skills__title">JavaScript</h3>
            <p class="skills__description">No Experience</p>
          </div>
          <div class="skills__item">
            <h3 class="skills__title">Accessibility</h3>
            <p class="skills__description">No Experience</p>
          </div>
          <div class="skills__item">
            <h3 class="skills__title">React</h3>
            <p class="skills__description">No Experience</p>
          </div>
          <div class="skills__item">
            <h3 class="skills__title">Sass</h3>
            <p class="skills__description">No Experience</p>
          </div>
          <div class="skills__item">
            <h3 class="skills__title">Nodejs</h3>
            <p class="skills__description">No Experience</p>
          </div>
        </div>
        <img
          class="skills__rings"
          src="assets/images/pattern-rings.svg"
          alt=""
          width="530"
          height="129"
        />
      </section>

      <section class="projects">
        <div class="wrapper projects__wrapper">
          <div class="projects__grid">
            <h2 class="projects__headline header-xl">Projects</h2>
            <a href="index.html#contact" class="projects__contact underline"
              >Contact me</a
            >

            <div class="projects__item">
              <picture class="projects__picture">
                <source
                  media="(min-width: 62.5em)"
                  srcset="/yangi-img1.png"
                />
                <img
                  class="projects__image"
                  src="./yangi-img1.png"
                  alt="screenshot of design portfolio website"
                  width-="343"
                  height="253"
                />
              </picture>
              <h3 class="projects__name">Fast Food Site</h3>
              <p class="projects__tags">
                <span>HTML</span>
                <span>CSS</span>
              </p>
              <div class="projects__links">
                <a href="index.html" class="underline">View Project</a>
                <a href="index.html" class="underline">View Code</a>
              </div>
            </div>

            <div class="projects__item">
              <picture class="projects__picture">
                <source
                  media="(min-width: 62.5em)"
                  srcset="/yangi-img2.png"
                />
                <img
                  class="projects__image"
                  src="./yangi-img2.png"
                  alt="screenshot of learning platform website with different courses"
                  width-="343"
                  height="253"
                />
              </picture>
              <h3 class="projects__name">Clothing Site</h3>
              <p class="projects__tags">
                <span>HTML</span>
                <span>CSS</span>
              </p>
              <div class="projects__links">
                <a href="index.html" class="underline">View Project</a>
                <a href="index.html" class="underline">View Code</a>
              </div>
            </div>

            <div class="projects__item">
              <picture class="projects__picture">
                <source
                  media="(min-width: 62.5em)"
                  srcset="/yangi-img3.png"
                />
                <img
                  class="projects__image"
                  src="./yangi-img3.png"
                  alt="screenshot of To Do App showing a list of active and complete tasks"
                  width-="343"
                  height="253"
                />
              </picture>
              <h3 class="projects__name">Clothing Site</h3>
              <p class="projects__tags">
                <span>HTML</span>
                <span>CSS</span>
                <span>JavaScript</span>
              </p>
              <div class="projects__links">
                <a href="index.html" class="underline">View Project</a>
                <a href="index.html" class="underline">View Code</a>
              </div>
            </div>

            <div class="projects__item">
              <picture class="projects__picture">
                <source
                  media="(min-width: 62.5em)"
                  srcset="/yangi-img4.png"
                />
                <img
                  class="projects__image"
                  src="./yangi-img4.png"
                  alt="screenshot of video player app with grid of thumbnails of movies and TV shows"
                  width-="343"
                  height="253"
                />
              </picture>
              <h3 class="projects__name">Shopping Site</h3>
              <p class="projects__tags">
                <span>HTML</span>
                <span>CSS</span>
                <span>JavaScript</span>
              </p>
              <div class="projects__links">
                <a href="index.html" class="underline">View Project</a>
                <a href="index.html" class="underline">View Code</a>
              </div>
            </div>

            <div class="projects__item">
              <picture class="projects__picture">
                <source
                  media="(min-width: 62.5em)"
                  srcset="/yangi-img5.png"
                />
                <img
                  class="projects__image"
                  src="./yangi-img5.png"
                  alt="screenshot of 4-player memory game with circular tiles that have symbols"
                  width-="343"
                  height="253"
                />
              </picture>
              <h3 class="projects__name">Coffee Site</h3>
              <p class="projects__tags">
                <span>HTML</span>
                <span>CSS</span>
                <span>JavaScript</span>
              </p>
              <div class="projects__links">
                <a href="index.html" class="underline">View Project</a>
                <a href="index.html" class="underline">View Code</a>
              </div>
            </div>

            <div class="projects__item">
              <picture class="projects__picture">
                <source
                  media="(min-width: 62.5em)"
                  srcset="/yangi-img6.png"
                />
                <img
                  class="projects__image"
                  src="./yangi-img6.png"
                  alt="grid of thumbnails of famous works of art"
                  width-="343"
                  height="253"
                />
              </picture>
              <h3 class="projects__name">Cars Site</h3>
              <p class="projects__tags">
                <span>HTML</span>
                <span>CSS</span>
                <span>JavaScript</span>
              </p>
              <div class="projects__links">
                <a href="index.html" class="underline">View Project</a>
                <a href="index.html" class="underline">View Code</a>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="contact" class="contact bg-less-dark">
        <div class="wrapper contact__wrapper bottom-border">
          <div class="contact__text">
            <h2 class="contact__headline header-xl">Contact</h2>
            <p class="contact__description">
              I would love to hear about your project and how I could help.
              Please fill in the form, and I'll get back to you as soon as
              possible.
            </p>
          </div>
          <form action="index.html" class="contact__form">
            <div class="contact__control">
              <label for="name" class="visually-hidden">Name</label>
              <input
                type="text"
                id="name"
                name="name"
                placeholder="Name"
                required
              />
              <img
                src="assets/images/icon-invalid.svg"
                alt=""
                class="contact__invalid-icon"
                width="24"
                height="24"
              />
            </div>
            <div class="contact__control">
              <label for="email" class="visually-hidden">Email</label>
              <input
                type="email"
                id="email"
                name="email"
                placeholder="Email"
                required
              />
              <img
                src="assets/images/icon-invalid.svg"
                alt=""
                class="contact__invalid-icon"
                width="24"
                height="24"
              />
            </div>
            <div class="contact__control">
              <label for="message" class="visually-hidden">Message</label>
              <textarea
                name="message"
                id="message"
                cols="30"
                rows="3"
                placeholder="Message"
                required
              ></textarea>
              <img
                src="assets/images/icon-invalid.svg"
                alt=""
                class="contact__invalid-icon"
                width="24"
                height="24"
              />
            </div>
            <div class="contact__control align-right">
              <button type="submit">Send Message</button>
            </div>
          </form>
        </div>
        <img
          class="contact__rings"
          src="assets/images/pattern-rings.svg"
          alt=""
          width="530"
          height="129"
        />
      </section>
    </main>

    <footer class="footer bg-less-dark">
      <h2 class="visually-hidden">Footer</h2>
      <div class="wrapper">
        <nav class="header__nav">
          <h2 class="visually-hidden">Navigation</h2>
          <a href="index.html" class="header__home">
            Ravshan
            <span class="visually-hidden">(to home page)</span>
          </a>
          <a href="https://github.com/abdurahmon999" class="header__social">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="25"
              height="24"
              aria-labelledby="socialGitHub"
              role="img"
            >
              <title id="socialGitHub">GitHub</title>
              <path
                fill="#FFF"
                fill-rule="evenodd"
                d="M12.304 0C5.506 0 0 5.506 0 12.304c0 5.444 3.522 10.042 8.413 11.672.615.108.845-.261.845-.584 0-.292-.015-1.261-.015-2.291-3.091.569-3.891-.754-4.137-1.446-.138-.354-.738-1.446-1.261-1.738-.43-.23-1.046-.8-.016-.815.97-.015 1.661.892 1.892 1.261 1.107 1.86 2.876 1.338 3.584 1.015.107-.8.43-1.338.784-1.646-2.738-.307-5.598-1.368-5.598-6.074 0-1.338.477-2.446 1.26-3.307-.122-.308-.553-1.569.124-3.26 0 0 1.03-.323 3.383 1.26.985-.276 2.03-.415 3.076-.415 1.046 0 2.092.139 3.076.416 2.353-1.6 3.384-1.261 3.384-1.261.676 1.691.246 2.952.123 3.26.784.861 1.26 1.953 1.26 3.307 0 4.721-2.875 5.767-5.613 6.074.446.385.83 1.123.83 2.277 0 1.645-.015 2.968-.015 3.383 0 .323.231.708.846.584a12.324 12.324 0 0 0 8.382-11.672C24.607 5.506 19.101 0 12.304 0Z"
              />
            </svg>
          </a>
          <a href="https://www.instagram.com/x_abdurahmon309/" class="header__social">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="25"
              height="24"
              aria-labelledby="socialLinkedIn"
              role="img"
            >
              <title id="socialLinkedIn">Instagram</title>
              <path
                fill="#FFF"
                fill-rule="evenodd"
                d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"
              />
            </svg>
          </a>
          <a href="https://twitter.com/Abdurahmon_X" class="header__social">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="20"
              aria-labelledby="socialTwitter"
              role="img"
            >
              <title id="socialTwitter">Twitter</title>
              <path
                fill="#FFF"
                d="M23.492 2.705a9.563 9.563 0 0 1-2.742.751 4.788 4.788 0 0 0 2.1-2.643 9.536 9.536 0 0 1-3.033 1.159 4.778 4.778 0 0 0-8.14 4.357 13.564 13.564 0 0 1-9.844-4.99 4.774 4.774 0 0 0-.646 2.4 4.778 4.778 0 0 0 2.124 3.977 4.765 4.765 0 0 1-2.163-.598v.061a4.778 4.778 0 0 0 3.832 4.684 4.812 4.812 0 0 1-2.158.082 4.78 4.78 0 0 0 4.462 3.316 9.584 9.584 0 0 1-5.932 2.045c-.38 0-.762-.022-1.14-.067a13.508 13.508 0 0 0 7.32 2.146c8.787 0 13.59-7.277 13.59-13.589 0-.205-.004-.412-.013-.617a9.71 9.71 0 0 0 2.381-2.471l.002-.003Z"
              />
            </svg>
          </a>
        </nav>
      </div>
    </footer>
  </body>
</html>


<!--- Css-file --->
/* GLOBAL */

:root {
  --bg-body: hsl(0, 0%, 8%);
  --bg-body2: hsl(0, 0%, 14%);
  --accent: hsl(153, 71%, 59%);
  --text1: hsl(0, 0%, 100%);
  --text2: hsl(0, 0%, 85%);
  --invalid: hsl(7, 100%, 68%);
  --fs-18: 1.125rem;
  --fs-88: 5.5rem;
  --fs-72: 4.5rem;
  --fs-40: 2.5rem;
  --fs-48: 3rem;
  --fs-36: 2.25rem;
  --fs-32: 2rem;
  --fs-24: 1.5rem;
  --fs-20: 1.25rem;
  --container: 69.375rem;
  --transition: 250ms ease-in-out;
}

html,
body {
  overflow-x: hidden;
}

html {
  box-sizing: border-box;
  font-size: 100%;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}

body,
input,
textarea,
button {
  font-family: 'Space Grotesk', sans-serif;
}

body {
  margin: 0;
  background-color: var(--bg-body);
  color: var(--text1);
  font-size: var(--fs-18);
  line-height: 1.56;
  padding-bottom: 25rem;
}

.bg-less-dark {
  background-color: var(--bg-body2);
}

h1,
h2,
h3,
p {
  margin-block-start: 0;
}

h1,
h2,
h3 {
  line-height: 1;
}

.header-xl {
  font-size: 2.5rem;
  font-size: clamp(2.5rem, 0.7rem + 7.68vw, 5.5rem);
  letter-spacing: -0.028em;
  line-height: 1.1;
}

p {
  font-size: 1rem;
  font-size: clamp(1rem, 0.79rem + 0.89vw, 1.125rem);
  line-height: 1.5;
  color: var(--text2);
}

a {
  transition: color var(--transition);
}

a:focus-visible,
input:focus-visible,
textarea:focus-visible {
  outline: 2px dashed var(--accent);
  outline-offset: 2px;
}

input:invalid,
textarea:invalid {
  outline-color: var(--invalid);
}

a.underline,
button {
  display: inline-block;
  padding-bottom: 0.625rem;
  font-size: 1rem;
  line-height: 1.625;
  letter-spacing: 0.143em;
  font-weight: 700;
  text-transform: uppercase;
  color: var(--text1);
  text-decoration: none;
  background-image: linear-gradient(
    to right,
    var(--accent) 75%,
    var(--accent) 75%
  );
  background-position: 0 2.1em;
  background-repeat: repeat-x;
  background-size: 8px 2px;
}

a:hover {
  color: var(--accent);
}

img,
svg {
  display: block;
}

.visually-hidden {
  position: absolute;
  left: -10000px;
  top: auto;
  width: 1px;
  height: 1px;
  overflow: hidden;
}

.wrapper {
  width: calc(100% - 2rem);
  max-width: var(--container);
  margin-inline: auto;
}

/* 600px */
@media (min-width: 37.5em) {
  .wrapper {
    width: calc(100% - 3.75rem);
  }
}

/* UTILITY */

.bottom-border {
  border-bottom: 1px solid var(--text2);
}

/* HEADER */

.header {
  position: relative;
  z-index: 1;
  margin-block-start: 20px;
}

.header__nav {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  text-align: center;
  gap: 20px 25px;
}

.header__home {
  font-size: 1.5rem;
  font-size: clamp(1.5rem, 1.02rem + 2.04vw, 2rem);
  line-height: 1;
  color: var(--text1);
  text-decoration: none;
  flex: 1 0 100%;
}

.header__social > svg > path {
  transition: fill var(--transition);
}

.header__social:hover > svg > path {
  fill: var(--accent);
}

@media (min-width: 37.5em) {
  .header {
    margin-block-start: 30px;
    /* margin-block-end: 90px; */
  }

  .header__nav {
    justify-content: flex-start;
    align-items: center;
    text-align: left;
    gap: 32px;
  }

  .header__home {
    flex: 0 1 auto;
    margin-inline-end: auto;
  }
}

@media (min-width: 62.5em) {
  .header {
    margin-block-start: 40px;
    margin-block-end: 127px;
  }

  .header__nav {
    padding-right: 30px;
  }
}

/*  HERO */

.hero__wrapper {
  padding-bottom: 80px;
}

.hero__image {
  position: absolute;
  top: 0;
  left: 50%;
  translate: -50%;
  width: 174px;
  height: auto;
}

.hero__rings {
  position: absolute;
  right: 50%;
  top: 130px;
  /* 8.125rem; */
  z-index: -1;
  /* width: 33.125rem; */
  height: auto;
}

.hero__circle {
  position: relative;
  top: 171px;
  margin-bottom: -129px;
  translate: calc(100vw - 64px - 16px);
}

.hero__text {
  position: relative;
  text-align: center;
  margin-block-start: 335px;
}

.hero__headline {
  margin-block-end: 24px;
}

.hero__headline > br {
  display: none;
}

h1 > span {
  background-image: linear-gradient(
    to right,
    var(--accent) 75%,
    var(--accent) 75%
  );
  background-position: 0 1.18em;
  background-repeat: repeat-x;
  background-size: 8px 4px;
}

.hero__description {
  margin-block-end: 24px;
}

@media (min-width: 37.5em) {
  .hero {
    position: relative;
    margin-block-start: -62px;
  }

  .hero__wrapper {
    padding-bottom: 60px;
  }

  .hero__content {
    display: flex;
    align-items: center;
  }

  .hero__content picture {
    order: 2;
  }

  .hero__image {
    position: relative;
    width: 42vw;
    max-width: 445px;
    /* width: 322px; */
    height: auto;
    left: auto;
    right: 0;
    translate: 0;
  }

  .hero__rings {
    top: 90px;
    right: auto;
    left: 0;
    translate: -50%;
  }

  .hero__circle {
    position: absolute;
    top: auto;
    right: 0;
    bottom: 190px;
    translate: 50%;
    z-index: 1;
  }

  .hero__text {
    /* width: 62vw; */
    margin-block-start: 90px;
    margin-right: -30px;
    flex: 1 0 58vw;
    text-align: left;
    z-index: 1;
  }

  .hero__headline {
    margin-block-end: 60px;
  }

  .hero__headline > br {
    display: inline-block;
  }

  .hero__description {
    /* width: 70%; */
    margin-block-end: 34px;
  }
}

@media (min-width: 62.5em) {
  .hero {
    margin-block-start: 0px;
  }

  .hero__wrapper {
    position: relative;
    padding-bottom: 100px;
  }

  .hero__content {
    align-items: flex-start;
  }

  .hero__content picture {
    margin-left: -80px;
  }

  .hero__image {
    margin-block-start: -199px;
  }

  .hero__rings {
    top: 0px;
    translate: -50% -50%;
  }

  .hero__circle {
    top: 322px;
    right: 445px;
  }

  .hero__text {
    margin-block-start: 0;
    margin-right: 0;
    flex: 1;
  }

  .hero__headline {
    margin-block-end: 43px;
  }

  .hero__headline > br {
    display: none;
  }

  .hero__description {
    width: 38ch;
    margin-block-end: 66px;
  }
}

/* SKILLS */

.skills {
  position: relative;
}

.skills__wrapper {
  display: grid;
  grid-template-columns: 1fr;
  gap: 24px;
  padding-block: 40px;
}

.skills__item {
  text-align: center;
}

.skills__title {
  font-size: 2rem;
  font-size: clamp(2rem, 0.33rem + 7.11vw, 3rem);
  line-height: 1.17;
  margin-block-end: 2px;
}

.skills__description {
  margin-block-end: 0;
}

.skills__rings {
  position: absolute;
  bottom: 0;
  left: 50%;
  translate: 0 50%;
}

@media (min-width: 37.5em) {
  .skills__wrapper {
    grid-template-columns: repeat(2, 1fr);
    gap: 52px 24px;
    border: none;
    padding-block: 52px 0;
  }

  .skills__item {
    text-align: left;
  }

  .skills__rings {
    translate: 40% 50%;
  }
}

@media (min-width: 62.5em) {
  .skills__wrapper {
    grid-template-columns: repeat(3, 1fr);
    gap: 58px 30px;
    padding-block-start: 72px;
  }

  .skills__rings {
    translate: -40% 50%;
    left: 100%;
  }
}

/* PROJECTS */

.projects__wrapper {
  padding-block: 140px;
}

.projects__grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 40px;
  justify-items: center;
  text-align: center;
}

.projects__headline {
  grid-column: 1 / span 2;
  margin-block-end: 0;
}

.projects__contact {
  grid-column: 1 / span 2;
}

.projects__item {
  grid-column: 1 / span 2;
}

.projects__picture {
  display: block;
  margin-block-end: 20px;
}

.projects__image {
  width: 100%;
  height: auto;
}

.projects__name {
  font-size: 1.5rem;
  line-height: 1.3;
  font-weight: 700;
  text-transform: uppercase;
  margin-block-end: 7px;
}

.projects__tags {
  display: flex;
  justify-content: center;
  gap: 12px;
  margin-block-end: 20px;
  text-transform: uppercase;
}

.projects__links {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
}

@media (min-width: 37.5em) {
  .projects__grid {
    gap: 60px 24px;
    justify-items: start;
    text-align: left;
  }

  .projects__contact {
    justify-self: end;
  }

  .projects__item {
    grid-column: span 1;
  }

  .projects__headline,
  .projects__contact {
    grid-column: span 1;
  }

  .projects__contact {
    align-self: center;
  }

  .projects__tags,
  .projects__links {
    display: block;
  }

  .projects__tags span {
    margin-inline-end: 18px;
  }

  .projects__links a {
    margin-inline-end: 30px;
  }

  .project__links {
    display: block;
  }
}

@media (min-width: 62.5em) {
  .projects__grid {
    gap: 70px 30px;
  }

  .projects__item {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: repeat(4, auto);
  }

  .projects__picture {
    position: relative;
    grid-column: 1 / 2;
    grid-row: 1 / 2;
  }

  .projects__picture::after {
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    background-color: hsl(0, 0%, 0%);
    opacity: 0;
    transition: opacity 150ms ease-in-out;
  }

  .projects__item:hover .projects__picture::after {
    opacity: 0.5;
  }

  .projects__item:hover .projects__links {
    opacity: 1;
  }
  .projects__item:focus-within .projects__links {
    opacity: 1;
  }

  .projects__item:focus-within .projects__picture::after {
    opacity: 0.5;
  }

  .projects__image {
    width: 100%;
    height: auto;
  }

  .projects__links {
    grid-column: 1 / 2;
    grid-row: 1 / 2;
    justify-self: center;
    align-self: center;
    z-index: 1;
    opacity: 0;
    transition: opacity 400ms ease-in-out;
  }

  .projects__links:hover ~ .projects__picture::after {
    opacity: 0.5;
  }

  .projects__tags {
    margin-block-end: 0;
  }
}

/* CONTACT */

.contact {
  position: relative;
}

.contact__wrapper {
  padding-block: 84px;
}

.contact__headline {
  margin-block-end: var(--fs-20);
}

.contact__control {
  position: relative;
  margin-block-end: 16px;
}

.contact__control input,
.contact__control textarea {
  width: 100%;
  padding-block: 16px;
  padding-inline: 24px;
  border: none;
  border-bottom: 1px solid var(--text1);
  background: transparent;
  font-size: 1rem;
  line-height: 1.625;
  color: var(--text1);
}

.contact__control > *::placeholder {
  color: var(--text1);
  opacity: 0.5;
  text-transform: uppercase;
}

.contact__control textarea {
  margin-block-end: 32px;
}

.contact__control.align-right {
  display: flex;
  justify-content: flex-end;
}

.contact__control button {
  background-color: transparent;
  border: none;
}

.contact__invalid-icon {
  display: none;
  width: var(--fs-24);
  height: var(--fs-24);
  position: absolute;
  top: 50%;
  right: 0;
  translate: -50% -50%;
}

.contact input:focus-visible:invalid ~ .contact__invalid-icon,
.contact textarea:focus-visible:invalid ~ .contact__invalid-icon {
  display: inline-block;
}

.contact textarea:focus-visible:invalid ~ .contact__invalid-icon {
  top: 1.2rem;
  right: 1.5rem;
  translate: none;
}

.contact__rings {
  position: absolute;
  left: 0;
  bottom: 97px;
  translate: -75%;
}

@media (min-width: 37.5em) {
  .contact__rings {
    bottom: 47px;
    translate: -75%;
  }
}

@media (min-width: 62.5em) {
  .contact__wrapper {
    display: grid;
    grid-template-columns: repeat(2, 27.8rem);
    justify-content: space-between;
  }

  .contact__headline {
    margin-block-end: var(--fs-36);
  }

  .contact__rings {
    translate: -40%;
  }
}

/* 999.98px */
@media (max-width: 62.49875em) {
  .contact__wrapper {
    max-width: 27.8rem;
  }

  .contact__text {
    text-align: center;
  }
}

footer {
  padding-block: 40px 60px;
}

@media (min-width: 37.5em) {
  footer {
    padding-block: 30px 40px;
  }
}

@media (min-width: 62.5em) {
  footer {
    padding-block: 47px 92px;
  }
}


<!---
WebdDveloper1/WebdDveloper1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
