# Hotstar-Clone
Hotstar clone using HTML,CSS,BOOTSTRAP
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Disney+ Hotstar Clone</title>

    <link rel="stylesheet" href="style.css" />

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  </head>
  <body>
    <nav class="navbar">
      <img
        src="https://secure-media.hotstarext.com/web-assets/prod/images/brand-logos/disney-hotstar-logo-dark.svg"
        alt=""
      />
      <ul class="nav-links">
        <li class="nav-items"><a href="#">TV</a></li>
        <li class="nav-items"><a href="#">movies</a></li>
        <li class="nav-items"><a href="#">sports</a></li>
        <li class="nav-items"><a href="#">disney+</a></li>
      </ul>

      <div class="right-container">
        <input type="text" class="search-box" placeholder="search" />
        <button class="sub-btn">subscribe</button>
        <a href="#" class="login-link">login</a>
      </div>
    </nav>

    <div class="carousel-container">
      <div class="carousel">
        <!--	<div class="slider">
					<div class="slide-content">
						<h1 class="movie-title">loki</h1>
						<p class="movie-des">
							The mercurial villain Loki resumes his role as the God of Mischief
							in a new series that takes place after the events of "Avengers
							Endgame."
						</p>
					</div>
					<img src="images/slider 1.PNG" alt="" />
				</div>-->
      </div>
    </div>

    <div class="video-card-container">
      <div class="video-card">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/disney.PNG"
          class="video-card-image"
          alt=""
        />
        <video
          src="https://github.com/pritam1923/csb-u1lfwu/blob/gh-pages/videos/disney.mp4?raw=true"
          mute
          loop
          class="card-video"
        ></video>
      </div>

      <div class="video-card">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/pixar.PNG"
          class="video-card-image"
          alt=""
        />
        <video
          src="https://github.com/pritam1923/csb-u1lfwu/blob/gh-pages/videos/pixar.mp4?raw=true"
          mute
          loop
          class="card-video"
        ></video>
      </div>

      <div class="video-card">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/geographic.PNG"
          class="video-card-image"
          alt=""
        />
        <video
          src="https://github.com/pritam1923/csb-u1lfwu/blob/gh-pages/videos/geographic.mp4?raw=true"
          mute
          loop
          class="card-video"
        ></video>
      </div>

      <div class="video-card">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/marvel.PNG"
          class="video-card-image"
          alt=""
        />
        <video
          src="https://github.com/pritam1923/csb-u1lfwu/blob/gh-pages/videos/marvel.mp4?raw=true"
          mute
          loop
          class="card-video"
        ></video>
      </div>

      <div class="video-card">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/star-wars.PNG"
          class="video-card-image"
          alt=""
        />
        <video
          src="https://github.com/pritam1923/csb-u1lfwu/blob/gh-pages/videos/star-war.mp4?raw=true4"
          mute
          loop
          class="card-video"
        ></video>
      </div>
    </div>

    <h1 class="title">recommended for you</h1>

    <div class="movies-list">
      <button class="pre-btn" title="btn">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/pre.png"
          alt=""
        />
      </button>
      <button class="nxt-btn" title="btn">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/nxt.png"
          alt=""
        />
      </button>
      <div class="card-container">
        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%201.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%202.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%203.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%204.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%205.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%206.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%207.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%208.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%209.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%2010.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%2011.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%2012.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
      </div>
    </div>

    <h1 class="title">popular shows</h1>

    <div class="movies-list">
      <button class="pre-btn" title="btn">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/pre.png"
          alt=""
        />
      </button>
      <button class="nxt-btn" title="btn">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/nxt.png"
          alt=""
        />
      </button>
      <div class="card-container">
        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%2012.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%2011.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%2010.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%209.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%208.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%207.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%206.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%205.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%204.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%203.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%202.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%201.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
      </div>
    </div>

    <h1 class="title">latest & trending</h1>

    <div class="movies-list">
      <button class="pre-btn" title="btn">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/pre.png"
          alt=""
        />
      </button>
      <button class="nxt-btn" title="btn">
        <img
          src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/nxt.png"
          alt=""
        />
      </button>
      <div class="card-container">
        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/244/1280244-v-58d850cbecc4"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/3195/1263195-v-b44cc0202665"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/3455/1283455-v-6883176a7972"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/1901/1231901-v-17c820e1cbe4"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/4158/1254158-v-8293462a94f2"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://raw.githubusercontent.com/pritam1923/csb-u1lfwu/7b9d7c8735a36506652af96236645ae3fe59c1d5/images/poster%203.png"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/9317/1269317-v-c851767a526b"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/1518/1161518-v-8d86a7ed8500"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/4965/1094965-v-185c17cd9ace"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/3017/1083017-v-4ab3c2456f2a"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/2213/1042213-v-1416e8e25397"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>

        <div class="card">
          <img
            src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_3x/sources/r1/cms/prod/2733/1122733-v-5df3bdae2d7a"
            class="card-img"
            alt=""
          />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watchlist</button>
          </div>
        </div>
      </div>
    </div>

    <script src="index.js" async></script>
  </body>
</html>
