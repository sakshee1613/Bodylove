<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BodyLove - Natural Hair & Skin Care</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #fff; color: #333; line-height: 1.6; }
    header { background: #e3f2d4; padding: 20px; text-align: center; }
    header h1 { color: #a1b315; font-size: 36px; }
    nav { background: #a1b315; display: flex; justify-content: center; }
    nav a { color: white; padding: 15px 20px; text-decoration: none; font-weight: bold; }
    nav a:hover { background: #7d9312; }
    .hero { padding: 40px 20px; text-align: center; background: #f9f9f9; }
    .hero img { width: 90%; max-width: 700px; border-radius: 10px; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    .about, .contact, .videos { background: #f5f5f5; border-radius: 10px; margin-bottom: 40px; padding: 20px; }
    footer { text-align: center; padding: 20px; background: #a1b315; color: white; }
    .contact p { margin-bottom: 10px; }
    iframe { width: 100%; height: 400px; border-radius: 10px; }
  </style>
</head>

<body>


 <header style="background: #e3f2d4; padding: 20px; text-align: center;">
  <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/338006906_544748601127734_1407991151731545728_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=OSVywqeeQAAQ7kNvwGlUfn3&_nc_oc=Adk9-kcP6ENPg1AcbsJvmYkBpw2S-dtl3iKFX5nTCD3erFXR-t9iiBdE4nwqDpXn7dA&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=I2kqYXJXp0oW7T0k2fO1Uw&oh=00_AfSK2aBuhyR9zekCk_syLB7FVYhgr_FV0NJx__dS-eHb0A&oe=688FF04D" 
       alt="BodyLove Logo" 
       style="width: 100px; height: auto; margin-bottom: 10px; border-radius: 50%; box-shadow: 0 4px 10px rgba(0,0,0,0.1);" />

  <h1 style="color: #3c7a57; font-size: 36px;">BODYLOVE</h1>
  <p style="font-size: 18px;">Natural Hair and Skin Care</p>
</header>

 


  <nav>
    <a href="#about">About Us</a>
    <a href="#videos">Product Videos</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="product-image" style="text-align:center; padding: 30px;">
  <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/468664355_505923275793143_5152998839127612965_n.jpg?stp=dst-jpg_s960x960_tt6&_nc_cat=100&ccb=1-7&_nc_sid=cc71e4&_nc_ohc=ry1fBeNz4GAQ7kNvwGygH7y&_nc_oc=AdkQHUyfrXVEn5DRnzlj-_lQsvXOmlepg3abb4ap7ewI7DhwcYPo8MKLcny-riFL8NQ&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=VFMjTuURmBmBF12mLg17zw&oh=00_AfSx7cdBFbIf2_oXd8KVWnU-rlf6uRO69_uCD3TFIUb4hg&oe=688FE95C" 
       alt="BodyLove Product" 
       style="width:90%; max-width:600px; border-radius:12px;" />
    <h1>100% Pure🎯| Natural Ingredients | Available Pan India</h1>
  </section>

  <section id="about" class="about" style="padding: 40px; background: #f9f9f9; border-radius: 10px;">
  <h1 style="text-align: center; color: #3c7a57; margin-bottom: 20px;">✨ About Us</h1>
  <p id="typing-text" style="font-size: 18px; color: #333; line-height: 1.8; text-align: center; max-width: 800px; margin: 0 auto;"></p>
</section>

<!-- ✅ Typing Animation Script -->
<script>
  const text = "Welcome to BodyLove – where purity meets beauty. We believe true beauty starts with pure care. Founded by Dr. Muskan Biyani our mission is to provide natural, handcrafted skin and hair care solutions made with 100% pure and chemical-free ingredients.";
  let i = 0;
  const speed = 10;

  function typeEffect() {
    if (i < text.length) {
      document.getElementById("typing-text").innerHTML += text.charAt(i);
      i++;
      setTimeout(typeEffect, speed);
    }
  }

  window.onload = typeEffect;
</script>



  <section id="videos" class="videos">
    <h2>Product Videos-👩🏻‍⚕Dr.Muskan Biyani</h2>
    <p>Watch how our natural products work and learn the secrets behind our ingredients:</p>
    <iframe src="https://www.youtube.com/embed/x5kFbsHym9w" allowfullscreen></iframe>
  </section>


<section class="hero" style="position: relative; text-align: center; padding: 40px 20px; background: #f9f9f9;">
  <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/470189017_17949553298877626_9115663294694481885_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=127cfc&_nc_ohc=ZFaFkoLn-skQ7kNvwHlpHLj&_nc_oc=Adm22zZXbvVP3qQPx02oHlm56CdlYhN8miFDb4hs9ED4fQETfMtY4wr25QcEEMTD3-s&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=lZnO00TfsVknvu0pXwaL0w&oh=00_AfQsnaDkM0Smwl8QxfZFRCFW7z0u7QnFStofFUPAIssrTw&oe=688AE8A2" 
       alt="BodyLove Product" 
       style="width:90%; max-width:600px; border-radius:10px;" />

  <!-- 🔽 Stylish popup badge -->
  <div style="
    position: absolute;
    bottom: 30px;
    right: 40px;
    background: rgba(255, 255, 255, 0.95);
    padding: 18px 22px;
    border-left: 6px solid #a1b315;
    border-radius: 10px;
    max-width: 300px;
    box-shadow: 0 6px 30px rgba(0,0,0,0.15);
    font-size: 16px;
    animation: fadeInSlide 0.8s ease-out;
    text-align: left;
  ">
    <h3 style="margin: 0 0 8px 0; color: #7a9723;">🌿BodyLove Benefits</h3>
    <p style="margin: 0; color: #333;">
      ✔️ 100% Natural & Organic<br>
      ✔️ Dermatologist Approved<br>
      ✔️ Natural Ingredients<br>
      ✔️ Hair Repair and Restoration<br>
      ✔️ Deep Hydration<br>
      ✔️ Sulfate and Paraben-Free<br>
    </p>
  </div>
</section>

<!-- 🔽 Add this animation style inside <style> OR at the bottom of your HTML file -->
<style>
@keyframes fadeInSlide {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>


<!-- ✨ Animation Styles -->
<style>
@keyframes fadeInSlide {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>



<section style="background: #f9f9f9; padding: 40px 0;">
  <h2 style="text-align: center; color: #648c1b; margin-bottom: 30px; font-size: 28px;">
    🌸BodyLove Product Showcase🌸<br>
    !!Glow Naturally with BodyLove!!
  </h2>

  <!-- ✅ Auto-scrolling container -->
  <div style="
    overflow: hidden;
    position: relative;
    width: 100%;
  ">
    <div class="auto-slider" style="
      display: flex;
      width: max-content;
      animation: scrollGallery 30s linear infinite;
      gap: 20px;
      padding: 10px 0;
    ">

      <!-- ✅ Your actual images (you can add more) -->
 <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/474741837_540071539044983_123816622132046754_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=127cfc&_nc_ohc=fRgkQwmWnhwQ7kNvwHrWUUy&_nc_oc=Adn-82SioRj4sVxubzlY5U8jDM0YSYz2UKGzO5TOGZkw44jvhv_4TAZqJQ6iB-rbdrM&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=CfpdWoN_mwUMpKsu8QTc-g&oh=00_AfR9TAUygokoHrTxkv4XB5Rbl8jBe485U_1DNHedQywTkg&oe=688ADE30" style="width: 300px; border-radius: 10px; flex-shrink: 0;" alt="Product 1">
    <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/474489695_539722705746533_6742658476887699647_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=127cfc&_nc_ohc=X84dG8o170QQ7kNvwFPPAG4&_nc_oc=AdngCXQkrmgl_fHEgrfynm7PiD-6xdkWyTXXfJ6IS2lQOrpnQwYMbJZTepeqvC_DxN8&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=zYk0SagZj5pon94RXMCdQg&oh=00_AfS6txx-lqyad1dhqJVLM4hBaDrkNXCYm9zu5Oqgnq69LQ&oe=688B0E8F" style="width: 300px; border-radius: 10px; flex-shrink: 0;" alt="Product 2">
    <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/469447003_507371135648357_1655320329694104821_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=127cfc&_nc_ohc=711LKwhRjSQQ7kNvwGYKJ1N&_nc_oc=Adkk8_lu20QGFWo5k93MOZ-_Ef0L_q9Bxz0P3kOdz31Zhd8SLuW8mRPi7ja-iCYzLsA&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=XvDPLnSqOM0r6hN_glrl4Q&oh=00_AfRFW-kPs2bSW89WbXn4-gFx51i9mbVFeM2EkXq6CAbX1g&oe=688B0A13" style="width: 300px; border-radius: 10px; flex-shrink: 0;" alt="Product 3">
    <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/469353861_506420669076737_4381969031696431182_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=127cfc&_nc_ohc=pjLtDe6LK2wQ7kNvwH4GNo8&_nc_oc=AdkPAzJvDOEH9knZPvAQzEcKhxe5ffgCmLCxMYauQUHh8REH8ipuAiJKy3_ngZlZecI&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=_zqPTFK_04JAJSziI66Itw&oh=00_AfRkM9lx40wPA4WHRn4bssTaRK5G-aw-nqQUZpFS8I4P1A&oe=688B117D" style="width: 300px; border-radius: 10px; flex-shrink: 0;" alt="Product 4">
    <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/474697417_540080405710763_6193392588635238719_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=127cfc&_nc_ohc=_l6R6wk_qxwQ7kNvwE7s36M&_nc_oc=Adntnq_iaPzDtgllG0DnxT7e-5WMNAiyyCoT9L-7VIyHAcCbt82KfBaCkp-c8GT9VvQ&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=J7my7eXM_mfea-mTFsFQkQ&oh=00_AfSOlmFN6mxeSxZDgE8vYm0h1EhwuOBTJebR2S05VfWNqw&oe=688AE34B" style="width: 300px; border-radius: 10px; flex-shrink: 0;" alt="Product 5">

      <!-- ✅ Duplicate images for smooth infinite loop -->
<img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/474741837_540071539044983_123816622132046754_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=127cfc&_nc_ohc=fRgkQwmWnhwQ7kNvwHrWUUy&_nc_oc=Adn-82SioRj4sVxubzlY5U8jDM0YSYz2UKGzO5TOGZkw44jvhv_4TAZqJQ6iB-rbdrM&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=CfpdWoN_mwUMpKsu8QTc-g&oh=00_AfR9TAUygokoHrTxkv4XB5Rbl8jBe485U_1DNHedQywTkg&oe=688ADE30" style="width: 300px; border-radius: 10px; flex-shrink: 0;" alt="Product 1">
    <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/474489695_539722705746533_6742658476887699647_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=127cfc&_nc_ohc=X84dG8o170QQ7kNvwFPPAG4&_nc_oc=AdngCXQkrmgl_fHEgrfynm7PiD-6xdkWyTXXfJ6IS2lQOrpnQwYMbJZTepeqvC_DxN8&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=zYk0SagZj5pon94RXMCdQg&oh=00_AfS6txx-lqyad1dhqJVLM4hBaDrkNXCYm9zu5Oqgnq69LQ&oe=688B0E8F" style="width: 300px; border-radius: 10px; flex-shrink: 0;" alt="Product 2">
    <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/469447003_507371135648357_1655320329694104821_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=127cfc&_nc_ohc=711LKwhRjSQQ7kNvwGYKJ1N&_nc_oc=Adkk8_lu20QGFWo5k93MOZ-_Ef0L_q9Bxz0P3kOdz31Zhd8SLuW8mRPi7ja-iCYzLsA&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=XvDPLnSqOM0r6hN_glrl4Q&oh=00_AfRFW-kPs2bSW89WbXn4-gFx51i9mbVFeM2EkXq6CAbX1g&oe=688B0A13" style="width: 300px; border-radius: 10px; flex-shrink: 0;" alt="Product 3">
    <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/469353861_506420669076737_4381969031696431182_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=127cfc&_nc_ohc=pjLtDe6LK2wQ7kNvwH4GNo8&_nc_oc=AdkPAzJvDOEH9knZPvAQzEcKhxe5ffgCmLCxMYauQUHh8REH8ipuAiJKy3_ngZlZecI&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=_zqPTFK_04JAJSziI66Itw&oh=00_AfRkM9lx40wPA4WHRn4bssTaRK5G-aw-nqQUZpFS8I4P1A&oe=688B117D" style="width: 300px; border-radius: 10px; flex-shrink: 0;" alt="Product 4">
    <img src="https://scontent.fpnq20-1.fna.fbcdn.net/v/t39.30808-6/474697417_540080405710763_6193392588635238719_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=127cfc&_nc_ohc=_l6R6wk_qxwQ7kNvwE7s36M&_nc_oc=Adntnq_iaPzDtgllG0DnxT7e-5WMNAiyyCoT9L-7VIyHAcCbt82KfBaCkp-c8GT9VvQ&_nc_zt=23&_nc_ht=scontent.fpnq20-1.fna&_nc_gid=J7my7eXM_mfea-mTFsFQkQ&oh=00_AfSOlmFN6mxeSxZDgE8vYm0h1EhwuOBTJebR2S05VfWNqw&oe=688AE34B" style="width: 300px; border-radius: 10px; flex-shrink: 0;" alt="Product 5">
    </div>
  </div>
</section>

<!-- ✅ Animation style -->
<style>
@keyframes scrollGallery {
  0%   { transform: translateX(0); }
  100% { transform: translateX(-50%); }
}
</style>

    




  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> +91-7385558369</p>
    <p><strong>Email:</strong> bodyloveconsumers@gmail.com</p>
    <p><strong>Instagram:</strong> @drm2b</p>
    <p><strong>Linkdin:</strong>Dr. Muskan Biyani
 
  </section>

  <footer>
    <p>&copy; 2025 BODYLOVE. All rights reserved.</p>
  </footer>

</body>
</html>
  








