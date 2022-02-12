<template>
  <section id="about" class="about">

    <div class="about-me container">

      <div class="section-title">
        <h2>About</h2>
        <p>Learn more about me</p>
      </div>

      <div class="row">
        <div class="col-lg-4" data-aos="fade-right">
          <img link="https://i.postimg.cc/5yvv0jfZ/sindile-min.jpg" class="img-fluid" alt="">
        </div>
        <div class="col-lg-8 pt-4 pt-lg-0 content" data-aos="fade-left">
          <h3>Aspiring &amp; Full Stack Developer</h3>
          <p class="fst-italic">
            I am a diligent, hard-working and thorough individual. I feel at ease
              only when I give my all. Not only that, but I love being around people and communicating with them. I am fascinated with being around computers and knowing how they work. I would like to become a software developer one day.
          </p>
          <div class="row">
            <div class="col-lg-6">
              <ul>
                <li><i class="bi bi-chevron-right"></i> <strong>Date of Birth:</strong> <span>03 December 1999</span></li>
                <li><i class="bi bi-chevron-right"></i> <strong>Phone:</strong> <span>+27 67 197 5655</span></li>
                <li><i class="bi bi-chevron-right"></i> <strong>City:</strong> <span>Cape Town, South Africa</span></li>
              </ul>
            </div>
            <div class="col-lg-6">
              <ul>
                <li><i class="bi bi-chevron-right"></i> <strong>Age:</strong> <span>22</span></li>
                <li><i class="bi bi-chevron-right"></i> <strong>Education:</strong> <span>NSC</span></li>
                <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>smakhathini24@gmail.com</span></li>
                <li><i class="bi bi-chevron-right"></i> <strong>Freelance:</strong> <span>Available</span></li>
              </ul>
            </div>
          </div>
         
        </div>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: 'About',
}
</script>

<style>
.about-me .content h3 {
  font-weight: 700;
  font-size: 26px;
  color: #18d26e;
}
.about-me .content ul {
  list-style: none;
  padding: 0;
}
.about-me .content ul li {
  margin-bottom: 20px;
  display: flex;
  align-items: center;
}
.about-me .content ul strong {
  margin-right: 10px;
}
.about-me .content ul i {
  font-size: 16px;
  margin-right: 5px;
  color: #18d26e;
  line-height: 0;
}
.about-me .content p:last-child {
  margin-bottom: 0;
}


</style>