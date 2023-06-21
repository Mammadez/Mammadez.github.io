# Mammadez.github.io
<!DOCTYPE html>
<html lang="fa">

<head>
  <meta charset="UTF-8" />
  <meta http-uiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>You Got this!</title>
  <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
  <link rel="stylesheet" href="assests/CSS/style-grid-system.css" />
  <link rel="stylesheet" href="assests/CSS/style.css" />
  <link rel="stylesheet"
    href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>

<body>
  <header>
    <!-- start header -->
    <!-- start contact section -->
    <section class="container-fluid" id="contact">
      <div class="row">
        <div class=" col-s-12 col-xs-12 col-md-12 col-l-12 col-xl-12 container-fluid-custom">
          <div class=" col-s-6 col-xs-6 col-md-8 col-l-8 col-xl-6 contact">
            <i class='bx bxs-envelope md-hidden s-hidden xs-hidden'><span>Mohammad.ezlegini24480@gmail.com</span></i>
            <i class='bx bx-phone'><span>09363142126</span></i>
          </div>
          <!-- end contact section -->
          <!-- start social media section -->
          <div class="col-s-6 col-xs-6 col-md-4 col-l-4 col-xl-6 social-meida" id="social-meida">
            <a href=""><i class='bx bxl-telegram '></i></a>
            <a href=""><i class='bx bxl-instagram-alt'></i></a>
            <a href=""><i class='bx bxl-twitter'></i></a>
            <a href=""><i class='bx bxl-youtube xs-hidden'></i></a>
            <a href=""><i class='bx bxl-linkedin s-hidden '></i></a>
            <a href="" style="color: #171515;"><i class="fa fa-github" aria-hidden="true"></i></a>
          </div>
        </div>
      </div>
    </section>
    <!-- End social-meida section  -->
    <!--  Start Navbar section -->
    <nav class="navbar col-xl-12 col-l-12 col-md-12 col-s-12 col-xs-12" id="mynav">
      <div class="container-fluid">
        <div class="row">
          <div
            class="col-xl-9 col-xl-offset-3 col-l-9 col-l-offset-3 col-md-10 col-md-offset-2 col-s-11 col-s-offset-1 col-xs-12 Menu-hover">
            <a href="" class="Main-icon"><i class='bx bx-expand-horizontal'></i></a>
            <a href="" class="active">Home</a>
            <a href="">Tutorials</a>
            <a href="">Articles</a>
            <a href="">Team</a>
            <a href="">About Us</a>
            <a href="javascript:void(0);" class="Menu-icon" onclick="myFunc();"><i class='bx bx-menu'></i></a>
          </div>
        </div>
      </div>
    </nav>
    <!-- End Navbar section -->
    <!-- End header section -->
  </header>
  <main>
    <!--  Start wallpaper section -->
    <section class="container-fluid" id="wallpaper">
      <div class="row">
        <div class="col-xl-12 col-l-12 col-s-12 col-md-12" style="margin-bottom: -20px;">
          <figure class="relative">
            <div class="overlay absolute">
              <div class="textbox">
                <h1>!Hello world</h1>
                <h2>It's Mohammad Ezlegini</h2>
                <h3>"known as"Mammadez</h3>
                <a href="">More</a>
              </div>
            </div>
            <img src="./assests/img/wallpaper 1.jpg" alt="Rick & Morty" class="wallpaper img-responsive">
          </figure>
        </div>
      </div>
    </section>
    <!-- End wallpaper section -->
    <!-- start cards section -->
    <section class="container-fluid col-xl-12 col-l-12 col-md-12 col-s-12 col-xs-12 p-20" id="course-section">
      <div>
        <div class="row">
          <div class="course-head-title center mt-20">
            <h5>
              <i class="material-symbols-outlined">
                school</i>
              <span>
                دوره های آموزشی
              </span>
              <i class="material-symbols-outlined">
                school</i>
            </h5>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-4 col-l-4 col-md-6 col-s-6 col-xs-10 col-xs-offset-1 ">
          <div class="card" id="Python">
            <div class="card-header relative ">
              <div class="card-overlay absolute">
                <p class="absolute">Phy</p>
                <pre class="absolute">thon</pre>
              </div>
              <img class="img-responsive" src="./assests/img/python.jpg" alt="python">
            </div>
            <div class="card-body">
              <span>
                <i class='bx bxl-python bx-tada'></i> دوره آموزش پایتون
              </span>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-l-4 col-md-6 col-s-6 col-xs-10 col-xs-offset-1">
          <div class="card" id="JavaScript">
            <div class="card-header relative ">
              <div class="card-overlay absolute">
                <p class="absolute JS">JavaScript</p>
              </div>
              <img class="img-responsive" src="./assests/img/javascript.jpg" alt="JavaScript">
            </div>
            <div class="card-body">
              <span>
                <i class='bx bxl-javascript bx-tada'></i> دوره آموزش جاوا اسکریپت
              </span>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-l-4 col-md-6 col-s-6 col-xs-10 col-xs-offset-1 ">
          <div class="card" id="Frontend">
            <div class="card-header relative ">
              <div class="card-overlay absolute">
                <p class="absolute Frontend">Frontend</p>
              </div>
              <img class="img-responsive" src="./assests/img/frontend.png" alt="Frontend">
            </div>
            <div class="card-body">
              <span>
                <i class='bx bxl-sketch bx-tada'></i>
                دوره آموزش فرانت اند
              </span>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-l-4 col-md-6 col-s-6 col-xs-10 col-xs-offset-1 ">
          <div class="card" id="Bootstrap">
            <div class="card-header relative ">
              <div class="card-overlay absolute">
                <p class="absolute Bootstrap">Bootstrap</p>
              </div>
              <img class="img-responsive" src="./assests/img/BOOTSTRAP EDITED.jpg" alt="Bootstrap">
            </div>
            <div class="card-body">
              <span>
                <i class='bx bxl-bootstrap bx-tada'></i> دوره آموزش بوت استرپ
              </span>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-l-4 col-md-6 col-s-6 col-xs-10 col-xs-offset-1 ">
          <div class="card" id="CSS">
            <div class="card-header relative ">
              <div class="card-overlay absolute">
                <p class="absolute CSS">CSS</p>
              </div>
              <img class="img-responsive" src="./assests/img/sta-je-css.png" alt="CSS">
            </div>
            <div class="card-body">
              <span>
                <i class='bx bxl-css3 bx-tada'></i> دوره آموزش CSS
              </span>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-l-4 col-md-6 col-s-6 col-xs-10 col-xs-offset-1 ">
          <div class="card" id="HTML">
            <div class="card-header relative ">
              <div class="card-overlay absolute">
                <p class="absolute HTML">HTML</p>
              </div>
              <img class="img-responsive" src="./assests/img/sta-je-html.jpg" alt="HTML">
            </div>
            <div class="card-body">
              <span>
                <i class='bx bxl-html5 bx-tada'></i>
                دوره آموزش HTML
              </span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- end card section -->
    <!-- start articles section -->
    <article class="container-fluid col-xl-12 col-l-12 col-md-12 col-s-12 col-xs-12" id="articles">
      <div class="row">
        <div class="articles-head-title center">
          <h5>
            <span class="material-symbols-outlined">
              feed
            </span>
            <span>
              مقالات
            </span>
            <span class="material-symbols-outlined">
              feed
            </span>
          </h5>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-3 col-l-3 col-md-6 col-s-6 col-xs-12">
          <div class="articles-card article1">
            <div class="card-header relative">
              <img src="./assests/img/articles/photo_2023-06-14_18-09-53.jpg" alt="" class="img-responsive article1">
              <div class="articles-overlay absolute">
                <p href="" class="nametag">Backend Developer</p>
              </div>
            </div>
            <div class="card-body">
              <span> رود مپ بک اند
              </span>
            </div>
            <div class="card-footer">
              <ul>
                <li><i class='bx bxs-like'></i><span>24</span></li>
                <li><i class='bx bxs-dislike'></i><span>24</span></li>
                <li><i class="fa fa-eye" aria-hidden="true"></i><span>24</span></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-l-3 col-md-6 col-s-6 col-xs-12">
          <div class="articles-card article2">
            <div class="card-header relative">
              <img src="./assests/img/articles/photo_2023-06-14_18-10-14.jpg" alt="" class="img-responsive">
              <div class="articles-overlay absolute">
                <p href="" class="nametag">Frontend Developer</p>
              </div>
            </div>
            <div class="card-body">
              <span>
                رود مپ فرانت اند
              </span>
            </div>
            <div class="card-footer">
              <ul>
                <li><i class='bx bxs-like'></i><span>24</span></li>
                <li><i class='bx bxs-dislike'></i><span>24</span></li>
                <li><i class="fa fa-eye" aria-hidden="true"></i><span>24</span></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-l-3 col-md-6 col-s-6 col-xs-12">
          <div class="articles-card article3">
            <div class="card-header">
              <img src="./assests/img/articles/photo_2023-06-14_18-10-19.jpg" alt="" class="img-responsive">
            </div>
            <div class="card-body">
              <span>
                چگونه تگ div را center کنیم؟
              </span>
            </div>
            <div class="card-footer">
              <ul>
                <li><i class='bx bxs-like'></i><span>24</span></li>
                <li><i class='bx bxs-dislike'></i><span>24</span></li>
                <li><i class="fa fa-eye" aria-hidden="true"></i><span>24</span></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-l-3 col-md-6 col-s-6 col-xs-12">
          <div class="articles-card article4">
            <div class="card-header">
              <img src="./assests/img/articles/photo_2023-06-14_18-10-23.jpg" alt="" class="img-responsive">
            </div>
            <div class="card-body">
              <span>
                پشتیبانی تخصصی با مدرسین جهانی
              </span>
            </div>
            <div class="card-footer">
              <ul>
                <li><i class='bx bxs-like'></i><span>24</span></li>
                <li><i class='bx bxs-dislike'></i><span>24</span></li>
                <li><i class="fa fa-eye" aria-hidden="true"></i><span>24</span></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </article>
    <!-- end articles section -->
  </main>
  <!-- start team section -->
  <section class="col-xl-12 col-l-12 col-md-12 col-s-12 col-xs-12 p-20" id="team">
    <div class="container-fluid">
      <div class="center mt-20 mb-20">
        <div class="team-head-title">
          <h5>
            <i class="fa fa-users" aria-hidden="true"></i> <span class="relative">
              اعضای تیم
            </span>
            <i class="fa fa-users" aria-hidden="true"></i>
          </h5>
        </div>
      </div>
      <div class="row ">
        <div class="col-xl-4 col-l-4 col-md-6 col-s-12 col-xs-12">
          <div class="team-card Steve-Jobs ">
            <div class="card-header">
              <img src="./assests/img/Team/TEAM STEVE JOBS-fotor-20230613041.png" alt="">
            </div>
            <div class="card-body">
              <samp>Steve Jobs</samp>

            </div>
          </div>
        </div>
        <div class="col-xl-4 col-l-4 col-md-6 col-s-12 col-xs-12">
          <div class="team-card Linux-Torvalds">
            <div class="card-header">
              <img src="./assests/img/Team/TEAM LINUX TORVALDS-fotor-20230613035.png" alt="">
            </div>
            <div class="card-body">
              <samp>Linux Torvalds</samp>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-l-4 col-md-12 col-s-12 col-xs-12">
          <div class="team-card Timber-Lee">
            <div class="card-header">
              <img src="./assests/img/Team/TEAM TIMBER LEE-fotor-202306130318.png" alt="">
            </div>
            <div class="card-body">
              <samp>Tim Timber Lee</samp>
            </div>

          </div>
        </div>
      </div>
    </div>
    </div>

  </section>
  <!-- end team section -->
  <!-- start aboutus section -->
  <section class="container-fluid" id="aboutus">
    <div class="row">
      <div class="aboutus-head-title center mt-20 mb-20">
        <h5>
          <i class='bx bx-expand-horizontal'></i>
          <span>
            درباره ما
          </span>
          <i class='bx bx-expand-horizontal'></i>
        </h5>
      </div>
    </div>
    <div class="row p-20">
      <div class="col-xl-6 col-l-6 col-md-6 col-s-12 col-xs-12 aboutus-right-side">
        <img src="./assests/img/aboutus 2.avif" alt="" class="img-responsive wallpaper-aboutus">
      </div>
      <div class="col-xl-6 col-l-6 col-md-6 col-s-12 col-xs-12 aboutus-left-side ">
        <span class="relative">درباره ما</span>
        <div>
          <p>
            سلام من محمد ازلگینی هستم. معلم زبان و طراح سایت. این اولین قالبیه که دارم صرفا با HTML/CSS طراحی میکنم.
            امیدوارم روزی که به این صفحه برمیگردم و نگاهش میکنم اون بالا بالا ها وایستاده باشم و به این روزام بخندم (:
          </p>
        </div>
      </div>
    </div>
  </section>
  <!-- end  aboutus section -->
  <!-- start stats section -->
  <section class="container-fluid" id="stats">
    <div class="row col-xl-12 col-l-12 col-md-12 col-s-12 col-xs-12 mt-20">
      <div class="col-xl-3 col-l-3 col-md-3  col-s-3 col-xs-3">
        <div class="stats-card courses">
          <div class="card-header">

            <i class="fa fa-code" aria-hidden="true"></i>

          </div>
          <div class="card-body">
            4
          </div>
          <div class="card-footer">
            <p>مدرس</p>
          </div>
        </div>
      </div>
      <div class="col-xl-3 col-l-3 col-md-3 col-s-3 col-xs-3">
        <div class="stats-card masters">
          <div class="card-header">
            <i class="fa fa-flag-o" aria-hidden="true"></i>
          </div>
          <div class="card-body">
            10
          </div>
          <div class="card-footer">
            <p>دوره</p>
          </div>
        </div>
      </div>
      <div class="col-xl-3 col-l-3 col-md-3 col-s-3 col-xs-3">
        <div class="stats-card users">
          <div class="card-header">
            <i class="fa fa-users" aria-hidden="true"></i>
          </div>
          <div class="card-body">
            8480
          </div>
          <div class="card-footer">
            <p>کاربر</p>
          </div>
        </div>
      </div>
      <div class="col-xl-3 col-l-3 col-md-3 col-s-3 col-xs-3">
        <div class="stats-card active-users">
          <div class="card-header">
            <i class="fa fa-user" aria-hidden="true"></i>
          </div>
          <div class="card-body">
            24
          </div>
          <div class="card-footer">
            <p>کاربر فعال</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- end  stats section -->
  <!-- start faq section -->
  <section class="col-xl-12 col-l-12 col-md-12 col-s-12 col-xs-12 p-20" id="faq">
    <div class="container-fluid">
      <div class="center mb-20">
        <div class="faq-head-title">
          <h5>
            <i class="fa fa-users" aria-hidden="true"></i> <span class="relative">
              پشتیبانی
            </span>
            <i class="fa fa-users" aria-hidden="true"></i>
          </h5>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-6 col-l-6 col-md-12 col-s-12 col-s-offset-03 col-xs-12 col-xs-offset-03">
          <div class="faq-rightside">
            <ul>
              <li><span class="material-symbols-outlined">
                  support_agent
                </span><span>پشتیبانی تخصصی توسط مدرسین</span></li>
              <li><span class="material-symbols-outlined">
                  support
                </span><span>پشتیبانی 24 ساعته توسط کارشناسان</span></li>
              <li><span class="material-symbols-outlined">
                  help_center
                </span><span>پشتیبانی آنلاین توسط ثبت تیکت</span></li>
            </ul>
          </div>
        </div>
        <div class="col-xl-6  col-l-6  col-md-12 col-s-12 col-s-offset-02 col-xs-12 col-xs-offset-03">
          <div class="faq-leftside">
            <div class="tabs">
              <div class="tab">
                <input class="" type="checkbox" name="check1" id="chk1">
                <label class="tab-label" for="chk1">سوالات متداول</label>
                <div class="tab-content">
                  چگونه با مدیر مجموعه "Mammadez" ارتباط داشته باشیم؟
                </div>
                <div class="tab-content">
                  نحوه استفاده از API سایت به چه صورت است؟
                </div>
              </div>
              <div class="tab">
                <input class="" type="checkbox" name="check2" id="chk2">
                <label class="tab-label" for="chk2">نحوه همکاری </label>
                <div class="tab-content">
                  چگونه با مجموعه همکاری کنیم؟
                </div>
                <div class="tab-content">
                  مدت زمان انتظار برای تایید اولیه چقدر است؟
                </div>
              </div>
              <div class="tab">
                <input class="" type="checkbox" name="check3" id="chk3">
                <label class="tab-label" for="chk3">دوره ها</label>
                <div class="tab-content">
                  امکان استفاده از دوره ها تا چه مدتی بعد از خرید فراهم است؟
                </div>
                <div class="tab-content">
                  دورۀ "برنامه نویس شو!" برای چه سطحی مناسب است؟
                </div>
              </div>
              <div class="tab">
                <input class="" type="checkbox" name="check4" id="chk4">
                <label class="tab-label" for="chk4">برنامه نویسی برای همه</label>
                <div class="tab-content">
                  چگونه صلاحیت خود را برای طرح "برنامه نویسی برای همه" تایید کنیم؟
                </div>
                <div class="tab-content">
                  افرادی که در این طرح شرکت می کنند چه تفاوتی با اعضای عادی دارند؟
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- end  faq section -->
  <!-- start footer section -->
  <footer class="col-xl-12 col-l-12 col-md-12 col-s-12 col-xs-12 container-flui" id="footer">
    <div class="row mt-20 mb-20">
      <div class="col-xl-4 col-l-4 col-md-6 col-s-12 col-xs-12 section1">
        <span>
          <i class='bx bx-expand-horizontal'></i>
          درباره ما
        </span>
        <p> لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و
          متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای
          متنوع با هدف بهبود ابزارهای کاربردی می باشد.</p>
      </div>
      <div class="col-xl-4 col-l-4 col-md-6 col-s-6 col-xs-12 section2">
        <span><i class='bx bxs-fast-forward-circle bx-rotate-180'></i>دسترسی سریع</span>
        <ul>
          <li><a href="#wallpaper"><i class='bx bxs-left-arrow-circle'></i>خانه</a></li>
          <li><a href="#course-section"><i class='bx bxs-left-arrow-circle'></i>دوره های آموزشی</a></li>
          <li><a href="#articles"><i class='bx bxs-left-arrow-circle'></i>مقالات</a></li>
          <li><a href="#team"><i class='bx bxs-left-arrow-circle'></i>اعضای تیم</a></li>
          <li><a href="#aboutus"><i class='bx bxs-left-arrow-circle'></i>درباره ما</a></li>
        </ul>
      </div>
      <div class="col-xl-4 col-l-4 col-md-12 col-s-6 col-xs-12 section3">
        <div class="social-footer">
          <a href=""><i class='bx bxl-telegram '></i></a>
          <a href=""><i class='bx bxl-instagram-alt xs-hidden'></i></a>
          <a href=""><i class='bx bxl-twitter xs-hidden'></i></a>
          <a href=""><i class='bx bxl-youtube xs-hidden '></i></a>
          <a href=""><i class='bx bxl-linkedin'></i></a>
          <a href="" style="color: #171515;"><i class="fa fa-github" aria-hidden="true"></i></a>
        </div>
        <form class="mail">
          <input type="email" placeholder="Get news!" autocomplete="email">
          <button type="submit" class="absolute"><i class='bx bx-envelope'></i></button>
        </form>
      </div>
    </div>
    <div class="copy-right center col-xl-12 col-l-12 col-md-12 col-s-12 col-xs-12">
      <span>کلیه حقوق این سایت متعلق به Mammadez است</span>
    </div>
  </footer>
  <!-- end  footer section -->
  <!-- start Movement section -->
  <div class="Movement">
    <div class="go-up-link">
      <a href="#contact">
        <i class="fa fa-arrow-up" aria-hidden="true"></i>
      </a>
    </div>
    <div class="go-down-link">
      <a href="#footer">
        <i class="fa fa-arrow-down" aria-hidden="true"></i>
      </a>
    </div>
  </div>
  <!-- End Movement section -->
  <!-- start JavaScript section  -->
  <script src="assests/JS/main.js"></script>
  <!-- End JavaScript section  -->
</body>

</html>
