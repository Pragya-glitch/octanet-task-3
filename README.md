# octanet-task-3
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Disney+hotstar</title>
    <link rel="stylesheet" href="styles.css" />
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  </head>
  <body>
    <nav class="navbar">
      <img src="images/logo.png" class="brand-logo" alt="" />
      <ul class="nav-links">
        <li class="nav-items"><a href="#">TV</a></li>
        <li class="nav-items"><a href="#">Movies</a></li>
        <li class="nav-items"><a href="#">Sports</a></li>
        <li class="nav-items"><a href="#">Premium</a></li>
      </ul>
      <div class="right-container">
        <input type="text" class="search-box" placeholder="search" />
        <button class="sub-btn">subscribe</button>
        <a href="#" class="login-link">Login</a>
      </div>
    </nav>

    <div class="carousel-container">
      <div class="carousel">
        <!-- <div class="slider">
          <div class="slide-content">
            <h1 class="movie-title">Loki</h1>
            <p class="movie-des">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Recusandae inventore, repudiandae optio nesciunt blanditiis
              deleniti?
            </p>
          </div>
          <img src="images/slider 1.png" alt="" />
        </div> -->
      </div>
    </div>
    <div class="video-card-container">
      <div class="video-card">
        <img src="images/disney.png" class="video-card-image" alt="" />
        <video src="videos/disney.mp4" muted loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/pixar.png" class="video-card-image" alt="" />
        <video src="videos/pixar.mp4" muted loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/marvel.png" class="video-card-image" alt="" />
        <video src="videos/marvel.mp4" muted loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/star-wars.png" class="video-card-image" alt="" />
        <video src="videos/star-war.mp4" muted loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/geographic.png" class="video-card-image" alt="" />
        <video
          src="videos/geographic.mp4"
          muted
          loop
          class="card-video"
        ></video>
      </div>
    </div>
    <h1 class="title">Recommended For You</h1>
    <div class="movies-list">
      <button class="pre-btn" title="btn">
        <img src="images/pre.png" alt="" />
      </button>
      <button class="nxt-btn" title="btn">
        <img src="images/nxt.png" alt="" />
      </button>
      <div class="card-container">
        <div class="card">
          <img src="images/poster 1.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 2.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 3.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 4.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 5.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 6.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 7.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 8.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 9.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 10.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 11.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 12.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
      </div>
    </div>

    <h1 class="title">Recommended For You</h1>
    <div class="movies-list">
      <button class="pre-btn" title="btn">
        <img src="images/pre.png" alt="" />
      </button>
      <button class="nxt-btn" title="btn">
        <img src="images/nxt.png" alt="" />
      </button>
      <div class="card-container">
        <div class="card">
          <img src="images/poster 12.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 11.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 10.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 9.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 8.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 7.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 6.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 5.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 4.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 3.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 2.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
        <div class="card">
          <img src="images/poster 1.png" class="card-img" alt="" />
          <div class="card-body">
            <h2 class="name">Movie Name</h2>
            <h6 class="des">
              Lorem ipsum dolor sit amet consectetur adipisicing.
            </h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
      </div>
    </div>
    <script src="index.js" async></script>
  </body>
</html>

index.js
let movies = [
  {
    name: "falcon and the winter soldier",
    des:
      "Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit porro et veniam excepturi, eaque voluptatem impedit nulla laboriosam facilis ut laboriosam libero!",
    image: "images/slider 2.png"
  },
  {
    name: "loki",
    des:
      "Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit porro et veniam excepturi, eaque voluptatem impedit nulla laboriosam facilis ut laboriosam libero!",
    image: "images/slider 1.png"
  },
  {
    name: "wanda vision",
    des:
      "Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit porro et veniam excepturi, eaque voluptatem impedit nulla laboriosam facilis ut laboriosam libero!",
    image: "images/slider 3.png"
  },
  {
    name: "Failure",
    des:
      "Upcoming movie in future,Stars are like a daimond in the Sky,Failures are like a daimond on the world",
    image: "images/failure.jpg"
  },
  {
    name: "luca",
    des:
      "Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit porro et veniam excepturi, eaque voluptatem impedit nulla laboriosam facilis ut laboriosam libero!",
    image: "images/slider 5.png"
  }
];

const carousel = document.querySelector(".carousel");
let sliders = [];

let slideIndex = 0; // to track current slide index.

const createSlide = () => {
  if (slideIndex >= movies.length) {
    slideIndex = 0;
  }

  // creating DOM element
  let slide = document.createElement("div");
  var imgElement = document.createElement("img");
  let content = document.createElement("div");
  let h1 = document.createElement("h1");
  let p = document.createElement("p");

  // attaching all elements
  imgElement.appendChild(document.createTextNode(""));
  h1.appendChild(document.createTextNode(movies[slideIndex].name));
  p.appendChild(document.createTextNode(movies[slideIndex].des));
  content.appendChild(h1);
  content.appendChild(p);
  slide.appendChild(content);
  slide.appendChild(imgElement);
  carousel.appendChild(slide);

  // setting up image
  imgElement.src = movies[slideIndex].image;
  slideIndex++;

  // setting elements classname
  slide.className = "slider";
  content.className = "slide-content";
  h1.className = "movie-title";
  p.className = "movie-des";

  sliders.push(slide);

  if (sliders.length) {
    sliders[0].style.marginLeft = `calc(-${100 * (sliders.length - 2)}% - ${
      30 * (sliders.length - 2)
    }px)`;
  }
};

for (let i = 0; i < 3; i++) {
  createSlide();
}

setInterval(() => {
  createSlide();
}, 3000);

//Video Cards

const videoCards = [...document.querySelectorAll(".video-card")];

videoCards.forEach((item) => {
  item.addEventListener("mouseover", () => {
    let video = item.children[1];
    video.play();
  });
  item.addEventListener("mouseleave", () => {
    let video = item.children[1];
    video.pause();
  });
});

//card sliders

let cardContainers = [...document.querySelectorAll(".card-container")];
let preBtns = [...document.querySelectorAll(".pre-btn")];
let nxtBtns = [...document.querySelectorAll(".nxt-btn")];

cardContainers.forEach((item, i) => {
  let containerDimensions = item.getBoundingClientRect();
  let containerWidth = containerDimensions.width;

  nxtBtns[i].addEventListener("click", () => {
    item.scrollLeft += containerWidth - 200;
  });

  preBtns[i].addEventListener("click", () => {
    item.scrollLeft -= containerWidth + 200;
  });
});

PACKAGE.JSON

{
  "name": "hotstar-clone",
  "version": "1.0.0",
  "description": "",
  "main": "index.html",
  "scripts": {
    "start": "serve",
    "build": "echo This is a static template, there is no bundler or bundling involved!"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/codesandbox-app/static-template.git"
  },
  "keywords": [],
  "author": "Ives van Hoorne",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/codesandbox-app/static-template/issues"
  },
  "homepage": "https://github.com/codesandbox-app/static-template#readme",
  "devDependencies": {
    "serve": "^11.2.0"
  }
}

style.css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  background: #0c111b;
  position: relative;
  font-family: roboto, sans-serif;
}

.navbar {
  width: 100%;
  height: 80px;
  position: fixed;
  top: 0;
  left: 0;
  padding: 0 4%;
  background: #0c111b;
  z-index: 9;
  display: flex;
  align-items: center;
}

.brand-logo {
  height: 70px;
}

.nav-links {
  margin-top: 10px;
  display: flex;
  list-style: none;
}

.nav-items a {
  text-decoration: none;
  margin-left: 20px;
  text-transform: capitalize;
  color: #fff;
  opacity: 0.9;
}

.right-container {
  display: block;
  margin-left: auto;
}

.search-box {
  border: none;
  border-bottom: 1px solid #aaa;
  background: transparent;
  outline: none;
  height: 30px;
  color: #fff;
  width: 250px;
  text-transform: capitalize;
  font-size: 16px;
  font-weight: 500;
  transition: 0.5s;
}

.search-box:focus {
  width: 400px;
  border-color: #1f80e0;
}

.sub-btn {
  background: #1f80e0;
  height: 30px;
  padding: 0 20px;
  color: #fff;
  border-radius: 5px;
  border: none;
  outline: none;
  text-transform: uppercase;
  font-weight: 700;
  font-size: 12px;
  margin: 0 10px;
}

.login-link {
  color: #fff;
  opacity: 0.9;
  text-transform: uppercase;
  font-size: 15px;
  font-weight: 700;
  text-decoration: none;
}

.carousel-container {
  position: relative;
  width: 100%;
  height: 450px;
  padding: 20px 0;
  overflow-x: hidden;
  margin-top: 80px;
}

.carousel {
  display: flex;
  width: 92%;
  height: 100%;
  position: relative;
  margin: auto;
}

.slider {
  flex: 0 0 auto;
  margin-right: 30px;
  position: relative;
  background: rgba(0, 0, 0, 0.5);
  border-radius: 5px;
  width: 100%;
  height: 100%;
  left: 0;
  transition: 1s;
  overflow: hidden;
}

.slider img {
  width: 70%;
  min-height: 100%;
  object-fit: cover;
  display: block;
  margin-left: auto;
}

.slide-content {
  position: absolute;
  width: 50%;
  height: 100%;
  z-index: 2;
  background: linear-gradient(to right, #030b17 80%, #0c111b00);
  color: #fff;
}

.movie-title {
  padding-left: 50px;
  text-transform: capitalize;
  margin-top: 80px;
}

.movie-des {
  width: 80%;
  line-height: 30px;
  padding-left: 50px;
  margin-top: 30px;
  opacity: 0.8;
}

.video-card-container {
  position: relative;
  width: 92%;
  margin: auto;
  height: 10vw;
  display: flex;
  margin-bottom: 20px;
  justify-content: space-between;
}

.video-card {
  position: relative;
  min-width: calc(100% / 5 - 10px);
  width: calc(100% / 5 - 10px);
  height: 100%;
  border-radius: 5px;
  overflow: hidden;
  background: #030b17;
}

.video-card-image,
.card-video {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.card-video {
  position: absolute;
}

.video-card:hover .video-card-image {
  display: none;
}

.title {
  color: #fff;
  opacity: 0.9;
  padding-left: 4%;
  text-transform: capitalize;
  font-size: 22px;
  font-weight: 500;
}

.movies-list {
  width: 100%;
  height: 220px;
  position: relative;
  margin: 10px 0 20px;
}

.card-container {
  position: relative;
  width: 92%;
  padding-left: 10px;
  height: 220px;
  display: flex;
  margin: 0 auto;
  align-items: center;
  overflow-x: auto;
  overflow-y: visible;
  scroll-behavior: smooth;
}

.card-container::-webkit-scrollbar {
  display: none;
}

.card {
  position: relative;
  min-width: 150px;
  width: 150px;
  height: 200px;
  border-radius: 5px;
  overflow: hidden;
  margin-right: 10px;
  transition: 0.5s;
}

.card-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.card:hover {
  transform: scale(1.1);
}

.card:hover .card-body {
  opacity: 1;
}

.card-body {
  opacity: 0;
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  left: 0;
  z-index: 2;
  background: linear-gradient(to bottom, rgba(4, 8, 15, 0), #192133 90%);
  padding: 10px;
  transition: 0.5s;
}

.name {
  color: #fff;
  font-size: 15px;
  font-weight: 500;
  text-transform: capitalize;
  margin-top: 60%;
}

.des {
  color: #fff;
  opacity: 0.8;
  margin: 5px 0;
  font-weight: 500;
  font-size: 12px;
}

.watchlist-btn {
  position: relative;
  width: 100%;
  text-transform: capitalize;
  background: none;
  border: none;
  font-weight: 500;
  text-align: right;
  color: rgba(255, 255, 255, 0.5);
  margin: 5px 0;
  cursor: pointer;
  padding: 10px 5px;
  border-radius: 5px;
}

.watchlist-btn::before {
  content: "";
  position: absolute;
  top: 0;
  left: -5px;
  height: 35px;
  width: 35px;
  background-image: url(images/add.png);
  background-size: cover;
  transform: scale(0.4);
}

.watchlist-btn:hover {
  color: #fff;
  background: rgba(255, 255, 255, 0.1);
}

.pre-btn,
.nxt-btn {
  position: absolute;
  top: 0;
  width: 5%;
  height: 100%;
  z-index: 2;
  border: none;
  cursor: pointer;
  outline: none;
}

.pre-btn {
  left: 0;
  background: linear-gradient(to right, #0c111b 0%, #0c111b00);
}

.nxt-btn {
  right: 0;
  background: linear-gradient(to left, #0c111b 0%, #0c111b00);
}

.pre-btn img,
.nxt-btn img {
  width: 15px;
  height: 20px;
  opacity: 0;
}

.pre-btn:hover img,
.nxt-btn:hover img {
  opacity: 1;
}
