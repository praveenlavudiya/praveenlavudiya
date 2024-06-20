<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">  
    <title>Links website</title>
    <style>

      body {
        background: #232526;  /* fallback for old browsers */
        background: -webkit-linear-gradient(to right, #414345, #232526);  /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to right, #414345, #232526); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
      }

        .container {
          width: 100%;
          height: 100%;
          padding-right: 15px;
          padding-left: 15px;
          margin-right: auto;
          margin-left: auto;
        }

        .image {
          background-image: url("https://spaces.w3schools.com/images/iLNPS0N_6J4.jpg");
          background-size: cover;
          background-repeat: no-repeat;
          background-position: center; 
          width: 200px;
          height: 200px;
          border-radius: 50%;
          margin: 0 auto;
          border: 5px solid #fdf5e6;
        }

        a {
          font-size: large;
        }

        .w3-border {
          border: 3px solid #ccc !important;
        }

        .links-container {
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          gap: 20px;
        }

        .links-container a {
          width: 100%;
          color: #414345 !important;
          transition: 0.2s;
        }

        .links-container a:hover {
          opacity: 1;
        }

        .profession {
          margin-top: 15px !important;
        }

        .profession span {
          font-size: 14px;
        }

        .icons {
          display: flex;
          justify-content: center;
          gap: 10px;
        }

        .icons a {
          text-decoration: none;
        }

        .icons a svg {
          fill: #fdf5e6 !important;
          transform: scale(1);
        }

        .border {
          border: 3px ridge #fdf5e6;
        }

        .contact {
          text-align: center;
          color: #fdf5e6;
        }

        .contact .info {
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          gap: 15px;
        }

        .contact .info span {
          display: flex;
          align-items: center;
          gap: 15px;
        }

        .bio {
          font-size: 11px;
          text-align: center;
        }

        @media screen and (min-width: 768px) {
          .link {
            width: 100%;
          }

          a {
            font-size: x-large;
          }

        }
        @media screen and (min-width: 576px) {
          .container {
            max-width: 540px;
          }

          .profession span {
            font-size: 24px;
          }
          
          .bio {
            font-size: 15px;
          }

        }

    </style>
    <script src="https://unpkg.com/feather-icons@4.28.0/dist/feather.min.js"></script>
  </head>
  <body>
    <!-- Content container -->
    <div class="container">

      <!-- Image and name container -->
      <div class="w3-margin-top" style="text-align: center">
        <div class="image w3-round"></div>
        <p class="profession"><span class="w3-padding w3-margin" style="font-weight: bolder; color: #fdf5e6"><span style="color: #ffcc66">PRAVEEN LAVUDIYA</span></span></p>
        <p class="bio"><span class="w3-padding w3-margin" style="font-weight: bolder; color: #fdf5e6">FINANCE MANAGER</span></p><br>
      </div>

      <!-- Links section 1 -->
      <div class="links-container">
        <a href="#" class="w3-button w3-sand w3-hover-pale-green link border" target="https://www.linkedin.com/in/praveenlavudiya"> website</a>
       
      </div>
      
      <!-- Links section 2 -->
      <div class="icons w3-padding">
        <a href="#" target="_blank">
          <i data-feather="facebook"></i>
        </a>
        <a href="#" target="_blank">
          <i data-feather="twitter"></i>
        </a>
        <a href="#" target="_blank">
          <i data-feather="linkedin"></i>
        </a>
        <a href="#" target="_blank">
          <i data-feather="github"></i>
        </a>
      </div><br>
      
        <div class="contact">
          <p class=""><span class="w3-padding w3-margin" style="font-weight: bolder; color: #fdf5e6">CONTACT US</span></p>
          <div class="info">
            <a href = "tel: 8919625572"><span><i data-feather="phone"></i> 8919625572</span></a>
            <a href = "mailto: email@company.com"><span><i data-feather="mail"></i> praveenlavudiya@gmail.com</span></a>
          </div>
        </div><br>
        <div class="contact">
          <p class=""><span class="w3-padding w3-margin" style="font-weight: bolder; color: #fdf5e6">FIND US</span></p>
          <iframe src="https://maps.google.com/maps?q=India,+hyderabad uppal&output=embed" width="100%" height="250" frameborder="0" style="border:0" allowfullscreen></iframe>
        </div>
      <!-- Footer. This section contains an ad for W3Schools Spaces. You can leave it to support us. -->
      
      </div>

    </div>
    <script>
      feather.replace()
    </script>
  </body>  
</html>
