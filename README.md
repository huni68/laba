# laba
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="css/login.min.css">
</head>

<body>

  <header class="header">
  <div class="container">
    <div class="header__inner">
      <a class="logo" href="index.html">
        <img class="logo__img" src="images/logo.png" alt="logo">
      </a>
      <nav class="menu">
        <button class="menu__btn">
          <span></span>
        </button>
        <ul class="menu__list">
          <li class="menu__list-item">
            <a class="menu__list-link menu__list-link--active" href="index.html">HOME</a>
          </li>
          <li class="menu__list-item">
            <a class="menu__list-link" href="shop.html">SHOP</a>
          </li>
          <li class="menu__list-item">
            <a class="menu__list-link" href="register.html">SIGN UP</a>
          </li>
          <li class="menu__list-item">
            <a class="menu__list-link" href="blog.html">BLOG</a>
          </li>
          <li class="menu__list-item">
            <a class="menu__list-link" href="contacts.html">CONTACT</a>
          </li>
        </ul>
      </nav>
      <div class="user-nav">
        <a class="user-nav__link" href="login.html">
          <img class="user-nav__link-img" src="images/icons/user.svg" alt="user icon">
        </a>
        <a class="user-nav__link" href="404-page.html">
          <img class="user-nav__link-img" src="images/icons/search.svg" alt="search icon">
        </a>
        <a class="user-nav__link" href="#">
          <img class="user-nav__link-img" src="images/icons/heart.svg" alt="heart icon">
          <span class="user-nav__num">3</span>
        </a>
        <a class="user-nav__link" href="#">
          <img class="user-nav__link-img" src="images/icons/cart.svg" alt="cart icon">
          <span class="user-nav__num">7</span>
        </a>
      </div>
    </div>
  </div>
</header>

  <main class="main">

    <section class="top">
      <div class="top__container" style="background-image: url('images/top-bg.jpg')">
        <div class="container">
          <h2 class="top__title">REGISTER</h2>
          <div class="breadcrumbs">
            <ul class="breadcrumbs__list">
              <li class="breadcrumbs__item">
                <a class="breadcrumbs__link" href="index.html">
                  Home
                </a>
              </li>
              <li class="breadcrumbs__item">
                <a class="breadcrumbs__link" href="#">
                  Register
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section class="modal">
      <div class="container">
        <div class="modal__links">
          <a class="modal__link modal__link--active" href="register.html">
            REGISTER
          </a>
          <a class="modal__link" href="login.html">
            LOGIN
          </a>
        </div>
        <form class="modal__form" action="#">
          <label class="modal__label">
            Username or email address*
            <input class="modal__input" type="text" required>
          </label>
          <label class="modal__label">
            Password*
            <input class="modal__input" type="password" required>
          </label>
          <p class="modal__text">A password will be sent to your email address.</p>
          <p class="modal__text">Your personal data will be used to support your experience throughout this website, to
            manage access to your account, and for other purposes described in our privacy policy.</p>
          <label class="modal__label">
            <input type="checkbox" required>
            Agree with Terms & Conditions
          </label>
          <button class="modal__btn" type="submit">REGISTER</button>
        </form>
      </div>
    </section>

  </main>
  <footer class="footer">
    <div class="container">
      <div class="footer-top">
        <div class="footer-top__contact">
          <a class="logo footer-top__logo" href="index.html">
            <img class="logo__img" src="images/logo.png" alt="logo">
          </a>
          <a class="footer-top__adress" href="#">
            No. 342 - London Oxford Street,
            012 United States
          </a>
          <a class="footer-top__email" href="mailto:Youremail@gmail.com">Youremail@gmail.com</a>
          <a class="footer-top__phone" href="tel:+02838388393">+0283 838 8393</a>
          <ul class="footer-top__social-list">
            <li class="footer-top__social-item">
              <a class="footer-top__social-link" href="https://twitter.com/">
                <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="11px"
                  height="18px" viewBox="0 0 11 17" version="1.1">
                  <g>
                    <path
                      d="M 9.59375 9.5625 L 10.085938 6.484375 L 7.027344 6.484375 L 7.027344 4.488281 C 7.027344 3.648438 7.453125 2.828125 8.824219 2.828125 L 10.214844 2.828125 L 10.214844 0.207031 C 10.214844 0.207031 8.953125 0 7.746094 0 C 5.230469 0 3.585938 1.472656 3.585938 4.140625 L 3.585938 6.484375 L 0.785156 6.484375 L 0.785156 9.5625 L 3.585938 9.5625 L 3.585938 17 L 7.027344 17 L 7.027344 9.5625 Z M 9.59375 9.5625 " />
                  </g>
                </svg>
              </a>
            </li>
            <li class="footer-top__social-item">
              <a class="footer-top__social-link" href="https://twitter.com/">
                <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="14px"
                  height="14px" viewBox="0 0 14 14" version="1.1">
                  <g>
                    <path
                      d="M 12.5625 4.148438 C 12.570312 4.273438 12.570312 4.398438 12.570312 4.523438 C 12.570312 8.316406 9.683594 12.683594 4.40625 12.683594 C 2.78125 12.683594 1.269531 12.214844 0 11.398438 C 0.230469 11.425781 0.453125 11.433594 0.691406 11.433594 C 2.035156 11.433594 3.269531 10.980469 4.253906 10.207031 C 2.992188 10.179688 1.9375 9.355469 1.574219 8.21875 C 1.75 8.242188 1.925781 8.261719 2.113281 8.261719 C 2.371094 8.261719 2.628906 8.226562 2.871094 8.164062 C 1.554688 7.898438 0.570312 6.742188 0.570312 5.347656 L 0.570312 5.3125 C 0.949219 5.527344 1.394531 5.660156 1.867188 5.675781 C 1.09375 5.160156 0.585938 4.28125 0.585938 3.285156 C 0.585938 2.753906 0.726562 2.265625 0.976562 1.839844 C 2.390625 3.578125 4.511719 4.71875 6.894531 4.839844 C 6.847656 4.628906 6.824219 4.40625 6.824219 4.183594 C 6.824219 2.601562 8.101562 1.316406 9.691406 1.316406 C 10.519531 1.316406 11.265625 1.660156 11.789062 2.222656 C 12.4375 2.097656 13.058594 1.855469 13.609375 1.527344 C 13.394531 2.195312 12.941406 2.753906 12.347656 3.109375 C 12.925781 3.046875 13.484375 2.886719 14 2.664062 C 13.609375 3.234375 13.121094 3.738281 12.5625 4.148438 Z M 12.5625 4.148438 " />
                  </g>
                </svg>
              </a>
            </li>
            <li class="footer-top__social-item">
              <a class="footer-top__social-link" href="https://twitter.com/">
                <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="14px"
                  height="16px" viewBox="0 0 14 16" version="1.1">
                  <g>
                    <path
                    d="M 3.132812 14 L 0.230469 14 L 0.230469 4.652344 L 3.132812 4.652344 Z M 1.679688 3.378906 C 0.753906 3.378906 0 2.609375 0 1.679688 C 0 0.753906 0.753906 0 1.679688 0 C 2.609375 0 3.363281 0.753906 3.363281 1.679688 C 3.363281 2.609375 2.609375 3.378906 1.679688 3.378906 Z M 13.996094 14 L 11.101562 14 L 11.101562 9.449219 C 11.101562 8.367188 11.078125 6.976562 9.589844 6.976562 C 8.082031 6.976562 7.851562 8.152344 7.851562 9.371094 L 7.851562 14 L 4.953125 14 L 4.953125 4.652344 L 7.734375 4.652344 L 7.734375 5.929688 L 7.777344 5.929688 C 8.164062 5.195312 9.109375 4.417969 10.523438 4.417969 C 13.460938 4.417969 14 6.351562 14 8.867188 L 14 14 Z M 13.996094 14 " />
                  </g>
                </svg>
              </a>
            </li>
            <li class="footer-top__social-item">
              <a class="footer-top__social-link" href="https://twitter.com/">
                <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="15px"
                  height="16px" viewBox="0 0 15 15" version="1.1">
                  <g>
                    <path
                      d="M 15 7.671875 C 15 11.816406 12.023438 14.765625 7.621094 14.765625 C 3.40625 14.765625 0 11.519531 0 7.5 C 0 3.480469 3.40625 0.234375 7.621094 0.234375 C 9.675781 0.234375 11.402344 0.953125 12.734375 2.136719 L 10.660156 4.039062 C 7.945312 1.539062 2.898438 3.414062 2.898438 7.5 C 2.898438 10.035156 5.023438 12.085938 7.621094 12.085938 C 10.640625 12.085938 11.773438 10.027344 11.949219 8.957031 L 7.621094 8.957031 L 7.621094 6.457031 L 14.878906 6.457031 C 14.949219 6.828125 15 7.1875 15 7.671875 Z M 15 7.671875 " />
                  </g>
                </svg>
              </a>
            </li>
            <li class="footer-top__social-item">
              <a class="footer-top__social-link" href="https://twitter.com/">
                <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="12px"
                  height="16px" viewBox="0 0 12 16" version="1.1">
                  <g>
                    <path
                      d="M 6.375 0.203125 C 3.167969 0.203125 0 2.339844 0 5.800781 C 0 8 1.238281 9.25 1.988281 9.25 C 2.296875 9.25 2.476562 8.386719 2.476562 8.144531 C 2.476562 7.851562 1.734375 7.234375 1.734375 6.023438 C 1.734375 3.511719 3.648438 1.730469 6.121094 1.730469 C 8.25 1.730469 9.824219 2.941406 9.824219 5.164062 C 9.824219 6.820312 9.160156 9.933594 7.003906 9.933594 C 6.226562 9.933594 5.558594 9.371094 5.558594 8.566406 C 5.558594 7.382812 6.382812 6.242188 6.382812 5.023438 C 6.382812 2.953125 3.449219 3.328125 3.449219 5.828125 C 3.449219 6.351562 3.515625 6.933594 3.75 7.414062 C 3.320312 9.269531 2.4375 12.035156 2.4375 13.945312 C 2.4375 14.539062 2.523438 15.117188 2.578125 15.710938 C 2.683594 15.828125 2.632812 15.816406 2.792969 15.757812 C 4.367188 13.601562 4.3125 13.179688 5.023438 10.355469 C 5.410156 11.085938 6.402344 11.480469 7.191406 11.480469 C 10.507812 11.480469 12 8.246094 12 5.332031 C 12 2.226562 9.320312 0.203125 6.375 0.203125 Z M 6.375 0.203125 " />
                  </g>
                </svg>
              </a>
            </li>
          </ul>
        </div>
        <div class="footer-top__nav">
          <h6 class="footer-top__title">
            Useful Links
          </h6>
          <ul class="footer-top__list">
            <li class="footer-top__item">
              <a class="footer-top__link" href="#">About Us</a>
            </li>
            <li class="footer-top__item">
              <a class="footer-top__link" href="#">Privacy Policy</a>
            </li>
            <li class="footer-top__item">
              <a class="footer-top__link" href="#">Terms & Conditions</a>
            </li>
            <li class="footer-top__item">
              <a class="footer-top__link" href="contacts.html">Contact Us</a>
            </li>
            <li class="footer-top__item">
              <a class="footer-top__link" href="contacts.html">Help & Support</a>
            </li>
          </ul>
        </div>
        <div class="footer-top__nav">
          <h6 class="footer-top__title">
            My Account
          </h6>
          <ul class="footer-top__list">
            <li class="footer-top__item">
              <a class="footer-top__link" href="#">My Account</a>
            </li>
            <li class="footer-top__item">
              <a class="footer-top__link" href="#">My Cart</a>
            </li>
            <li class="footer-top__item">
              <a class="footer-top__link" href="#">My WIshlist</a>
            </li>
            <li class="footer-top__item">
              <a class="footer-top__link" href="register.html">Registration</a>
            </li>
            <li class="footer-top__item">
              <a class="footer-top__link" href="#">Check Out</a>
            </li>
          </ul>
        </div>
        <div class="footer-top__item-form">
          <h6 class="footer-top__title">
            Subscribe Our Newsletter
          </h6>
          <p class="footer-top__text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore magna aliqua. Quis ipsum suspendisse ultrices gravida.
          </p>
          <form class="footer-top__form" action="#">
            <input class="footer-top__form-input" type="email" placeholder="Your email address" required>
            <button class="footer-top__form-btn" type="submit">Subscribe</button>
          </form>
        </div>
      </div>
      <div class="footer-bottom">
        <p class="footer-bottom__copy">
          © 2023 All Rights Reserved.
        </p>
        <div class="footer-bottom__accept">
          We Accept
          <img class="footer-bottom__accept-img" src="images/icons/mastercard.png" alt="we accept mastercard">
          <img class="footer-bottom__accept-img" src="images/icons/visa.png" alt="we accept visa">
          <img class="footer-bottom__accept-img" src="images/icons/paypal.png" alt="we accept paypal">
        </div>
      </div>
    </div>
  </footer>

  <script src="js/main.min.js"></script>
</body>

</html>
