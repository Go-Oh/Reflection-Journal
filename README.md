# Reflection-Journal

h2,h4 {
    margin: 20px;
    font-family: 'Montserrat', sans-serif;
    text-align: center;
  }
  
  body {
    padding-top:0px;
    width:100%;
    height:100%;
    margin:0%;
    background: ;
  }
  
  .container {
    width: 100%;
    margin: 0;
    padding: 0;
  }
  
  .header {
    margin: auto;
    padding-top: 0px;
    height:600px;
    width: 100%;
    background:#5fcf80;
  
  }
  
  .navbar {
    background-color: rgba(255, 255, 255, .90)
  }
  
  .navbar-toggle {
    float: left;
    margin-left: 15px
  }
  
  .navbar-default .navbar-nav>li>a {
    font-weight: bold;
    color: #252525;
  }
  
  .social {
    padding-top: 35px;
    color: #5fcf80;
  }
  
  .social li {
    display: inline;
    padding: 20px;
    
  }
  
  
  .portfolio {
    margin: 0;
    padding: 100px 20px;
    height:350px;
    width: 100%;
    background-color: #5fcf80;
  }
  
  #home {
    background-color: rgba(255, 255, 255, .93);
    border-radius: 15px;
    color: #252525;
    width: 450px;
    height: auto;
    margin-top: 200px;
    padding: 65px 30px;
  }
  
  .no-padding {
    padding-left: 0;
    padding-right: 0;
  }
  
  .about {
    margin: 0;
    padding: 150px 20px;
    height:550px;
    width: 100%;
    background-color: #5fcf80;
  }
  
  .content {
    max-width: 900px;
    margin: auto;
  }
  
  .background {
     background: url("http://www.sactownmag.com/Blog/2015/New-time-lapse-video-shows-Sacramento-on-the-rise/Skyline.png") no-repeat;
    overflow: hidden;
    background-size: cover;
    width: 100%;
    height: 100%;
  }
  
  .section {
      padding-top: 70px;
  }
  
  .section-box {
      padding: 40px 50px;
  }
  
  .section-title {
      font-size: 40px;
      font-weight: 300;
      line-height: 1.2;
      text-align: center;
  }
  
  
  .clearfix:before, .clearfix:after {
      content: " ";
      display: table;
  }
  
  .clearfix:after {
      clear: both;
  }
  
  .clearfix {
      *zoom: 1;
  }
    
  .grid:before, .grid:after {
      content: " ";
      display: table;
  }
  
  .grid:after {
      clear: both;
  }
  
  .grid {
      *zoom: 1;
  }
  
  .grid .grid-item,
  .grid .grid-sizer {
      width: 33.33%;
  }
  
  .grid .grid-sizer {
      height: 0;
      visibility: hidden;
  }
  
  .grid .grid-item {
      float: left;
      padding: 0 10px;
      margin-bottom: 20px;
  }
  
  .grid .grid-box {
      width: 100%;
      height: 0;
      padding-top: 95%;
      position: relative;
      overflow: hidden;
      background: rgba(0, 0, 0, 0.15);
  }
  
  .grid .size11 {
      width: 33.33%;
  }
  
  .grid .size11 .portfolio-title {
      font-size: 18px;
  }
  
  .grid .size22 {
      width: 66.66%;
  }
  
  .grid .size22 .portfolio-title {
      font-size: 24px;
  }
  
  .grid-more {
      margin-top: 20px;
      text-align: center;
  }
  
  .grid-more .btn {
      margin: 0;
      padding: 0;
      width: 60px;
      height: 60px;
      display: inline-block;
      line-height: 1;
  }
  
  .grid-more .btn .icon {
      font-size: 30px;
      -webkit-transition: all 0.2s;
      -moz-transition: all 0.2s;
      -ms-transition: all 0.2s;
      -o-transition: all 0.2s;
      transition: all 0.2s;
  }
  
  .grid-more .btn:hover .icon {
      -webkit-transform: rotate(90deg);
      -moz-transform: rotate(90deg);
      -ms-transform: rotate(90deg);
      -o-transform: rotate(90deg);
      transform: rotate(90deg);
  }
  
  .grid-more .ajax-loader {
      display: none;
      width: 72px;
      height: 24px;
      vertical-align: middle;
      background: url("img/ajax-loader.gif");
  }
  
  .filter {
      text-align: center;
      margin-bottom: 30px;
  }
  
  .filter button {
      border: 0;
      margin: 0 20px 0 0;
      padding: 0 12px;
      background: transparent;
      color: #000;
      font-size: 13px;
      font-weight: 600;
      font-family: "Open Sans", sans-serif;
      text-transform: uppercase;
  }
  
  .filter button:first-child {
      padding-left: 0;
  }
  
  .filter button:last-child {
      margin-right: 0;
      padding-right: 0;
  }
  
  .filter-inner {
      display: inline-block;
      position: relative;
  }
  
  .filter-bar {
      height: 5px;
      margin: 10px auto 0;
      background-color: #fff;
      position: relative;
  }
  
  .filter-bar, .filter-bar .filter-bar-line {
      -webkit-border-radius: 5px;
      -moz-border-radius: 5px;
      -ms-border-radius: 5px;
      -o-border-radius: 5px;
      border-radius: 5px;
  }
  
  .filter-bar .filter-bar-line {
      top: 0;
      left: 0;
      width: 0;
      height: 100%;
      display: block;
      position: relative;
      -webkit-transition: all 1s cubic-bezier(0.23, 1, 0.32, 1) 0ms;
      -moz-transition: all 1s cubic-bezier(0.23, 1, 0.32, 1) 0ms;
      -ms-transition: all 1s cubic-bezier(0.23, 1, 0.32, 1) 0ms;
      -o-transition: all 1s cubic-bezier(0.23, 1, 0.32, 1) 0ms;
      transition: all 1s cubic-bezier(0.23, 1, 0.32, 1) 0ms;
  }
  
  .portfolio-figure {
      top: 0;
      left: 0;
      z-index: 1;
      width: 100%;
      height: 100%;
      position: absolute;
  }
  
  .portfolio-figure img {
      position: relative;
      display: block;
      width: 100%;
      opacity: 1;
      -webkit-transform: scale3d(1.02, 1.02, 1);
      -moz-transform: scale3d(1.02, 1.02, 1);
      -ms-transform: scale3d(1.02, 1.02, 1);
      -o-transform: scale3d(1.02, 1.02, 1);
      transform: scale3d(1.02, 1.02, 1);
      -webkit-transition: opacity 1s, transform 1s;
      -moz-transition: opacity 1s, transform 1s;
      -ms-transition: opacity 1s, transform 1s;
      -o-transition: opacity 1s, transform 1s;
      transition: opacity 1s, transform 1s;
      -webkit-backface-visibility: hidden;
      -moz-backface-visibility: hidden;
      -ms-backface-visibility: hidden;
      -o-backface-visibility: hidden;
      backface-visibility: hidden;
  }
  
  .portfolio-figure .portfolio-caption {
      top: -2px;
      left: -2px;
      right: -2px;
      bottom: -2px;
      opacity: 0;
      position: absolute;
      background-color: rgba(32, 39, 52, 0.8);
      -webkit-transition: opacity 0.35s linear 0s;
      -moz-transition: opacity 0.35s linear 0s;
      -ms-transition: opacity 0.35s linear 0s;
      -o-transition: opacity 0.35s linear 0s;
      transition: opacity 0.35s linear 0s;
      -webkit-backface-visibility: hidden;
      -moz-backface-visibility: hidden;
      -ms-backface-visibility: hidden;
      -o-backface-visibility: hidden;
      backface-visibility: hidden;
  }
  
  .portfolio-figure .portfolio-caption-inner {
      left: 0;
      bottom: 0;
      width: 100%;
      padding: 5%;
      position: absolute;
      -webkit-transition: transform 0.35s;
      -moz-transition: transform 0.35s;
      -ms-transition: transform 0.35s;
      -o-transition: transform 0.35s;
      transition: transform 0.35s;
      -webkit-transform: translate3d(0, 100%, 0);
      -moz-transform: translate3d(0, 100%, 0);
      -ms-transform: translate3d(0, 100%, 0);
      -o-transform: translate3d(0, 100%, 0);
      transform: translate3d(0, 100%, 0);
      -webkit-backface-visibility: hidden;
      -moz-backface-visibility: hidden;
      -ms-backface-visibility: hidden;
      -o-backface-visibility: hidden;
      backface-visibility: hidden;
  }
  
  .portfolio-figure .portfolio-title,
  .portfolio-figure .portfolio-cat {
      opacity: 0;
      -webkit-transition: opacity 0.35s;
      -moz-transition: opacity 0.35s;
      -ms-transition: opacity 0.35s;
      -o-transition: opacity 0.35s;
      transition: opacity 0.35s;
      -webkit-backface-visibility: hidden;
      -moz-backface-visibility: hidden;
      -ms-backface-visibility: hidden;
      -o-backface-visibility: hidden;
      backface-visibility: hidden;
  }
  
  .portfolio-figure .portfolio-title {
      color: #fff;
      font-weight: 700;
      line-height: 1.3;
      margin-bottom: 13px;
  }
  
  .portfolio-figure .portfolio-cat {
      color: #a7a9ab;
      font-size: 13px;
      line-height: 1.1;
      text-transform: uppercase;
  }
  
  .portfolio-figure .btn-group a {
      width: 50px;
      height: 50px;
      margin-right: 5px;
      text-align: center;
      display: inline-block;
      background: transparent;
      border: 1px solid #767475;
      border: 1px solid rgba(255, 255, 255, 0.2);
      -webkit-border-radius: 3px;
      -moz-border-radius: 3px;
      -ms-border-radius: 3px;
      -o-border-radius: 3px;
      border-radius: 3px;
      -webkit-transition: transform 0.35s;
      -moz-transition: transform 0.35s;
      -ms-transition: transform 0.35s;
      -o-transition: transform 0.35s;
      transition: transform 0.35s;
      -webkit-transform: translate3d(0, 200%, 0);
      -moz-transform: translate3d(0, 200%, 0);
      -ms-transform: translate3d(0, 200%, 0);
      -o-transform: translate3d(0, 200%, 0);
      transform: translate3d(0, 200%, 0);
      -webkit-backface-visibility: hidden;
      -moz-backface-visibility: hidden;
      -ms-backface-visibility: hidden;
      -o-backface-visibility: hidden;
      backface-visibility: hidden;
  }
  
  .portfolio-figure .btn-group a:hover {
      text-decoration: none;
  }
  
  .portfolio-figure .btn-group .icon {
      display: block;
      line-height: 50px;
      font-size: 25px;
  }
  
  .portfolio-figure:hover img {
      opacity: 0.85;
      -webkit-transform: scale3d(1.1, 1.1, 1);
      -moz-transform: scale3d(1.1, 1.1, 1);
      -ms-transform: scale3d(1.1, 1.1, 1);
      -o-transform: scale3d(1.1, 1.1, 1);
      transform: scale3d(1.1, 1.1, 1);
  }
  
  .portfolio-figure:hover .portfolio-caption,
  .portfolio-figure:hover .portfolio-title,
  .portfolio-figure:hover .portfolio-cat {
      opacity: 1;
      
  }
  
  .portfolio-figure:hover .portfolio-caption-inner {
      -webkit-transform: translate3d(0, 0, 0);
      -moz-transform: translate3d(0, 0, 0);
      -ms-transform: translate3d(0, 0, 0);
      -o-transform: translate3d(0, 0, 0);
      transform: translate3d(0, 0, 0);
  }
  
  .portfolio-figure:hover .btn-group a {
      -webkit-transform: translate3d(0, 0, 0);
      -moz-transform: translate3d(0, 0, 0);
      -ms-transform: translate3d(0, 0, 0);
      -o-transform: translate3d(0, 0, 0);
      transform: translate3d(0, 0, 0);
  }
  
  .portfolio-figure:hover .btn-group .btn-zoom {
      -webkit-transition-delay: 0.3s;
      -moz-transition-delay: 0.3s;
      -ms-transition-delay: 0.3s;
      -o-transition-delay: 0.3s;
      transition-delay: 0.3s;
  }
  
  .portfolio-figure:hover .btn-group .btn-link {
      -webkit-transition-delay: 0.2s;
      -moz-transition-delay: 0.2s;
      -ms-transition-delay: 0.2s;
      -o-transition-delay: 0.2s;
      transition-delay: 0.2s;
  }
  
  @media (max-width: 767px) {
      .filter-bar {
          display: none;
      }
  
      .filter-inner {
          display: block;
      }
  
      .filter button {
          width: 100%;
          margin: 0;
          padding: 10px 0;
          display: block;
          border-bottom: 1px solid #d7dbde;
          position: relative;
      }
  
      .filter .active:after {
          content: '';
          left: 0;
          bottom: -1px;
          height: 3px;
          width: 100%;
          position: absolute;
      }
  
      .grid .grid-item,
      .grid .grid-sizer {
          width: 50%;
      }
  
      .grid .size11,
      .grid .size22 {
          width: 50%;
      }
  
      .grid .size11 .portfolio-title,
      .grid .size22 .portfolio-title {
          font-size: 18px;
      }
  }
  
  @media (max-width: 480px) {
      .grid .grid-item,
      .grid .grid-sizer {
          width: 100%;
      }
  
      .grid .size11,
      .grid .size22 {
          width: 100%;
      }
  
      .grid .size11 .portfolio-title,
      .grid .size22 .portfolio-title {
          font-size: 22px;
      }
  }
  
  .fancybox-portfolio .fancybox-error {
      background: #fff;
      margin-right: 70px;
      min-height: 225px;
  }
  
  .fancybox-portfolio .fancybox-skin {
      box-shadow: none;
      background-color: transparent;
      -webkit-border-radius: 0px;
      -moz-border-radius: 0px;
      -ms-border-radius: 0px;
      -o-border-radius: 0px;
      border-radius: 0px;
  }
  
  .fancybox-portfolio .fancybox-nav,
  .fancybox-portfolio .fancybox-close {
      left: auto;
      right: 0px;
      width: 45px;
      height: 45px;
      border: 1px solid #767475;
      border: 1px solid rgba(255, 255, 255, 0.3);
      -webkit-transition: all 0.3s ease-out;
      -moz-transition: all 0.3s ease-out;
      -ms-transition: all 0.3s ease-out;
      -o-transition: all 0.3s ease-out;
      transition: all 0.3s ease-out;
  }
  
  .fancybox-portfolio .fancybox-nav:hover,
  .fancybox-portfolio .fancybox-close:hover {
      background-color: rgba(255, 255, 255, 0.1);
      box-shadow: 0 1px 6px rgba(0, 0, 0, 0.12), 0 1px 4px rgba(0, 0, 0, 0.24);
  }
  
  .fancybox-portfolio .fancybox-close,
  .fancybox-portfolio .fancybox-prev span,
  .fancybox-portfolio .fancybox-next span {
      background-image: url("img/fancybox_sprite.png");
  }
  
  .fancybox-portfolio .fancybox-close {
      top: 0;
      background-position: -91px 0px;
  }
  
  .fancybox-portfolio .fancybox-nav span {
      top: 0;
      left: 0;
      margin: 0;
      right: auto;
      width: 100%;
      height: 100%;
      visibility: visible;
  }
  
  .fancybox-portfolio .fancybox-prev {
      top: 127px;
  }
  
  .fancybox-portfolio .fancybox-prev span {
      background-position: -1px 0px;
  }
  
  .fancybox-portfolio .fancybox-next {
      top: 180px;
  }
  
  .fancybox-portfolio .fancybox-next span {
      background-position: -46px 0px;
  }
  
  .fancybox-inline-box {
      width: 730px;
      z-index: 0;
      opacity: 0;
      visibility: hidden;
      position: relative;
      background: #fff;
      overflow-y: auto;
      overflow-x: hidden;
      margin-right: 65px;
      -webkit-box-sizing: content-box;
      -moz-box-sizing: content-box;
      box-sizing: content-box;
  }
  
  .fancybox-inline-box.opened {
      height: 100%;
      min-height: 225px;
      opacity: 1;
      visibility: visible;
  }
  
  .fancybox-inline-box .inline-cont {
      padding: 25px 40px;
  }
  
  .fancybox-inline-box .inline-title {
      color: #000;
      font-size: 20px;
      line-height: 1.25;
      margin-bottom: 20px;
  }
  
  .fancybox-inline-box .inline-text {
      color: #757575;
      font-size: 16px;
      line-height: 1.3;
  }
  
  .fancybox-inline-box .inline-text p {
      margin-bottom: 15px;
  }
  
  .fancybox-inline-box .inline-text p:last-child {
      margin-bottom: 0;
  }
  
  .fancybox-inline-box .inline-embed-image {
      width: 100%;
  }
  
  .fancybox-inline-box .inline-embed-image img {
      width: 100%;
      height: auto;
      display: block;
  }
  
  .fancybox-inline-box .inline-embed-iframe,
  .fancybox-inline-box .inline-embed-video {
      width: 100%;
      height: 410px;
  }
  
  .fancybox-inline-box .inline-embed-iframe iframe {
      width: 100%;
      height: 100%;
      border: 0;
  }
  
  .fancybox-inline-box .inline-embed-video .mejs-video {
      width: 100% !important;
      height: 100% !important;
  }
  
  @media only screen and (min--moz-device-pixel-ratio: 2), only screen and (-o-min-device-pixel-ratio: 2 / 1), only screen and (-webkit-min-device-pixel-ratio: 2), only screen and (min-device-pixel-ratio: 2) {
      .fancybox-portfolio .fancybox-nav span,
      .fancybox-portfolio .fancybox-close {
          background-image: url("img/fancybox_sprite@2x.png");
          background-size: 135px 45px;
      }
  }
  
  @media (max-width: 992px) {
      .fancybox-inline-box {
          width: 650px;
      }
  
      .fancybox-inline-box .inline-embed-iframe,
      .fancybox-inline-box .inline-embed-video {
          height: 360px;
      }
  }
  
  @media (max-width: 767px) {
      .fancybox-portfolio .fancybox-error {
          background: #fff;
          margin-right: 0;
          min-height: 0px;
      }
  
      .fancybox-portfolio .fancybox-nav,
      .fancybox-portfolio .fancybox-close {
          width: 30px;
          height: 30px;
      }
  
      .fancybox-portfolio .fancybox-close {
          top: -40px;
          right: 0;
          background-position: -99px -8px;
      }
  
      .fancybox-portfolio .fancybox-prev {
          top: -40px;
          left: 0;
          right: auto;
      }
  
      .fancybox-portfolio .fancybox-prev span {
          background-position: -9px -8px;
      }
  
      .fancybox-portfolio .fancybox-next {
          top: -40px;
          left: 40px;
          right: auto;
      }
  
      .fancybox-portfolio .fancybox-next span {
          background-position: -53px -8px;
      }
  
      .fancybox-inline-box {
          margin-right: 0;
          width: 420px;
      }
  
      .fancybox-inline-box .inline-embed-iframe,
      .fancybox-inline-box .inline-embed-video {
          height: 230px;
      }
  
      .fancybox-inline-box .inline-cont {
          padding: 20px;
      }
  }
  
  @media (max-width: 480px) {
      .fancybox-inline-box {
          width: 350px;
      }
  
      .fancybox-inline-box .inline-embed-iframe,
      .fancybox-inline-box .inline-embed-video {
          height: 187px;
      }
  }
  
  @media (max-width: 360px) {
      .fancybox-inline-box {
          width: 250px;
      }
  
      .fancybox-inline-box .inline-embed-iframe,
      .fancybox-inline-box .inline-embed-video {
          height: 150px;
      }
  }
  
  /**** HTML FORM ****/
  
  form {
    max-width: 300px;
    margin: 10px auto;
    padding: 10px 20px;
    background: #f4f7f8;
    border-radius: 8px;
  }
  
  h1 {
    margin: 0 0 30px 0;
    text-align: center;
  }
  
  input[type="text"],
  input[type="password"],
  input[type="date"],
  input[type="datetime"],
  input[type="email"],
  input[type="number"],
  input[type="search"],
  input[type="tel"],
  input[type="time"],
  input[type="url"],
  textarea,
  select {
    background: rgba(255,255,255,0.1);
    border: none;
    font-size: 16px;
    height: auto;
    margin: 0;
    outline: 0;
    padding: 15px;
    width: 100%;
    background-color: #e8eeef;
    color: #8a97a0;
    box-shadow: 0 1px 0 rgba(0,0,0,0.03) inset;
    margin-bottom: 30px;
  }
  
  input[type="radio"],
  input[type="checkbox"] {
    margin: 0 4px 8px 0;
  }
  
  select {
    padding: 6px;
    height: 32px;
    border-radius: 2px;
  }
  
  button {
    padding: 19px 39px 18px 39px;
    color: #FFF;
    background-color: #4bc970;
    font-size: 18px;
    text-align: center;
    font-style: normal;
    border-radius: 5px;
    width: 100%;
    border: 1px solid #3ac162;
    border-width: 1px 1px 3px;
    box-shadow: 0 -1px 0 rgba(255,255,255,0.1) inset;
    margin-bottom: 10px;
  }
  
  fieldset {
    margin-bottom: 30px;
    border: none;
  }
  
  legend {
    font-size: 1.4em;
    margin-bottom: 10px;
  }
  
  label {
    display: block;
    margin-bottom: 8px;
  }
  
  label.light {
    font-weight: 300;
    display: inline;
  }
  
  .number {
    background-color: #5fcf80;
    color: #fff;
    height: 30px;
    width: 30px;
    display: inline-block;
    font-size: 0.8em;
    margin-right: 4px;
    line-height: 30px;
    text-align: center;
    text-shadow: 0 1px 0 rgba(255,255,255,0.2);
    border-radius: 100%;
  }
  
  @media screen and (min-width: 480px) {
  
    form {
      max-width: 75%;
    }
  
  
    #footer-links {
    text-align: center;
    color: #252525;
    height: 140px;
    background: #5fcf80;
    padding-top: 50px;
  }
  
  #footer-links li {
    display: inline;
    padding: 0 40px;
    border-right: 1px solid white;
  }
  
    #footer-links li:nth-child(7) {
    border-right: none;
  }
    
    #footer-links p {
      text-align: center;
    }
    
    #contact-form {
      float: left;
      width: 50%;
    }
    
    #social-box {
      width: 50%;
      float: left;
    }
    
    #social-box h1 {
      padding: 20px;
      font-size: 60px;
      font-weight: bold;
    }
    
    #social-contact {
      padding-left: 150px;
      list-style: none;
      font-size: 18px;
      font-weight: bold;
      
    }
    
    #social-contact li {
      margin: 40px;
    }
    
    a {
      text-decoration: none;
      color: inherit;
     
    }
    
    .fa-4x {
      color: #5fcf80;
    }
    
fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff  
