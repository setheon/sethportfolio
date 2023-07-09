---
images:
# - /images/background.png
title: about
url: about
hideTitle: true
hideExif: true
hideDate: true
---


<style>

/* Donate */
 .donate-button-container {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .donate-button  {
    display: flex;
    align-items: center;
    padding: 10px;
    border-radius: 10px;
    background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
    width: 250px;
    transition: background-color 0.3s, filter 0.3s, border-color 0.3s;
    border: 2px solid transparent; /* Add transparent border */
    box-sizing: border-box; /* Include border in dimensions */
  }

  .donate-button:hover {
    background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
    animation: gradient 15s ease infinite;
    background-size: 400% 400%;
    filter: brightness(210%); /* Increase brightness by 10% */
  }

  .donate-button:hover .text {
    color: yellow;
  }

  .donate-button .icon {
    margin-right: 10px;
  }

  .donate-button .text {
    text-align: center;
    flex-grow: 1;
    transition: color 0.3s;
  }
  @keyframes gradient {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }
</style>

<div align="center">
    <h1>about me.</h1>
</div>

<script>
  // Calculate the number of years since a particular date
  var startDate = new Date("2002-03-14");
  var currentDate = new Date();
  var yearsSince = currentDate.getFullYear() - startDate.getFullYear();

  // Create the HTML string
  var htmlString = "<p><strong>Welcome to my portfolio website!</strong> My name is Seth Copeland, a " + yearsSince + "-year-old creative based in Wellington, New Zealand. I am currently working towards my Bachelor of Screen Arts at Massey University with a Major in Film Production, where I am honing my skills and passion for the visual arts/film.</p>";

  // Display the HTML string
  document.write(htmlString);
</script>

**Throughout my journey,** I have developed a diverse range of interests and hobbies that fuel my creativity. From the captivating world of photography, where I capture moments and tell stories through the lens, to the realm of graphic design, where I combine my artistic vision with digital tools to create visually stunning and impactful designs. <br> 

**Lastly,** I have an insatiable wanderlust that drives me to explore new places, experience different cultures, and broaden my perspectives.

<div align="center">
<h1 style="color: #FF7A59"> what is seth.nz? </h1>
</div>

**My website 'seth.nz' serves as a digital sanctuary for my creative work.** Here, you will find a carefully curated collection of my graphic design and photography projects, showcasing my ability to blend aesthetics with purpose, while conveying unique narratives. As my journey progresses, I am excited to expand my creative horizons into the realm of videography, where I aim to craft compelling visual stories that resonate with audiences.

**Immerse yourself in my creative portfolio** and explore the various projects I have undertaken. Whether you are seeking a collaborator for your next creative endeavor or simply appreciate art in its many forms, I hope that my work resonates with you and inspires you in some way.

**Thank you for visiting my portfolio website,** and I look forward to connecting with you soon. 
<br> Make sure to check out the other pages on this website. 
<br> I suggest starting out with <a style="color: #7EC2E6;" href="https://seth.nz/graphics">Graphic Design</a> </strong> then moving onto the <a style="color: #7EC2E6;" href="https://seth.nz/photography">Photography</a> </strong> page.



<div align="center">
<h1 style="color: #FF7A59"> thank you for visiting my portfolio</h1>
</div>




<div align="center">
    <h3>like my work? donate below.</h3>
</div>


<div class="donate-button-container">
  <a href="https://www.buymeacoffee.com/setheon/" class="donate-button">
    <span style="color: #ffffff;" class="fab fa-dollar fa-lg"></span>
    <span style="color: #ffffff; font-family:Open Sans Bold;" class="text">Buy me a Coffee</span>
  </a>
</div>
