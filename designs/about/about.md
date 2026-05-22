# Diamond District Aesthetics NYC — About Sections (HTML + CSS)

```html
<section class="dda-about-wrapper">

  <!-- SECTION 1 -->
  <section class="dda-about-section">
    <div class="dda-container dda-grid">

      <!-- IMAGE -->
      <div class="dda-image-placeholder">
        <div class="placeholder-text">IMAGE PLACEHOLDER</div>
      </div>

      <!-- CONTENT -->
      <div class="dda-content">

        <span class="dda-label">
          MIDTOWN MANHATTAN AESTHETIC CLINIC
        </span>

        <h2>
          About Diamond District <br>
          Aesthetics NYC
        </h2>

        <p>
          Located in the heart of New York City’s Diamond District,
          Diamond District Aesthetics NYC is a trusted aesthetic clinic
          in Midtown Manhattan specializing in advanced, non-surgical
          aesthetic treatments designed to enhance natural beauty with
          minimal downtime.
        </p>

        <p>
          We combine medical expertise, artistic precision, and modern
          aesthetic technology to deliver personalized treatments that
          help patients look refreshed, confident, and naturally beautiful.
        </p>

        <p>
          Whether you are exploring facial rejuvenation, skin tightening,
          collagen-stimulating treatments, or injectables, our goal is
          always the same — subtle, balanced results tailored to your
          unique features and lifestyle.
        </p>

        <!-- FEATURES -->
        <div class="dda-feature-row">

          <div class="dda-feature-item">
            <span>📍</span>
            <p>Midtown Manhattan Location</p>
          </div>

          <div class="dda-feature-item">
            <span>✨</span>
            <p>Personalized Treatment Plans</p>
          </div>

          <div class="dda-feature-item">
            <span>⚕️</span>
            <p>Advanced Non-Surgical Technology</p>
          </div>

          <div class="dda-feature-item">
            <span>🌿</span>
            <p>Natural-Looking Results</p>
          </div>

        </div>

        <!-- BUTTONS -->
        <div class="dda-buttons">
          <a href="#" class="btn-primary">BOOK CONSULTATION</a>
          <a href="#" class="btn-secondary">EXPLORE TREATMENTS</a>
        </div>

      </div>

    </div>
  </section>


  <!-- SECTION 2 -->
  <section class="dda-philosophy-section">
    <div class="dda-container dda-grid reverse-grid">

      <!-- CONTENT -->
      <div class="dda-content philosophy-content">

        <span class="dda-label">
          OUR PHILOSOPHY
        </span>

        <h2>Who We Are</h2>

        <p>
          At Diamond District Aesthetics NYC, we believe aesthetics is
          about more than appearance — it’s about confidence,
          self-expression, and feeling comfortable in your own skin.
        </p>

        <p>
          Our Midtown Manhattan clinic focuses on patient-first care,
          offering customized treatment plans that support long-term
          skin health, facial harmony, and natural-looking enhancement.
        </p>

        <p>
          From Botox® and dermal fillers to advanced rejuvenation
          technologies like Emface®, Morpheus8, and PRP therapy,
          every treatment is carefully selected to align with your goals
          while preserving what makes you uniquely you.
        </p>

        <p>
          Patients throughout Midtown Manhattan, the Diamond District,
          and New York City trust our team for honest guidance,
          refined aesthetic care, and results that never feel overdone.
        </p>


        <!-- MINI CARDS -->
        <div class="dda-mini-cards">

          <div class="dda-card">
            <h4>Natural Results</h4>
            <p>
              Subtle enhancements designed to preserve your
              natural facial harmony.
            </p>
          </div>

          <div class="dda-card">
            <h4>Personalized Care</h4>
            <p>
              Every treatment plan is customized around your
              goals and lifestyle.
            </p>
          </div>

          <div class="dda-card">
            <h4>Advanced Technology</h4>
            <p>
              Modern non-surgical treatments with minimal downtime.
            </p>
          </div>

        </div>

      </div>


      <!-- IMAGE -->
      <div class="dda-image-placeholder second-image">
        <div class="placeholder-text">CONSULTATION IMAGE</div>
      </div>

    </div>
  </section>

</section>
```

---

# CSS

```css
.dda-about-wrapper {
  width: 100%;
  background: #f9f7f4;
  padding: 80px 20px;
}

.dda-container {
  max-width: 1300px;
  margin: 0 auto;
}

.dda-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 70px;
  align-items: center;
}

.dda-about-section {
  margin-bottom: 100px;
}

.dda-label {
  display: inline-block;
  margin-bottom: 18px;
  letter-spacing: 3px;
  font-size: 12px;
  color: #b88746;
  font-weight: 600;
}

.dda-content h2 {
  font-size: 58px;
  line-height: 1.1;
  color: #0f5c52;
  margin-bottom: 28px;
  font-family: 'Cormorant Garamond', serif;
  font-weight: 600;
}

.dda-content p {
  font-size: 17px;
  line-height: 1.9;
  color: #5e5e5e;
  margin-bottom: 20px;
  font-family: 'Inter', sans-serif;
}

.dda-image-placeholder {
  width: 100%;
  height: 720px;
  background: linear-gradient(135deg, #e7dfd5, #d8cbbd);
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  overflow: hidden;
}

.placeholder-text {
  font-size: 18px;
  letter-spacing: 2px;
  color: #7a6b5b;
  font-weight: 600;
}

.dda-feature-row {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
  margin-top: 40px;
  margin-bottom: 40px;
}

.dda-feature-item {
  border-top: 1px solid #d8d2ca;
  padding-top: 18px;
}

.dda-feature-item span {
  display: block;
  font-size: 22px;
  margin-bottom: 10px;
}

.dda-feature-item p {
  font-size: 15px;
  line-height: 1.5;
  margin: 0;
  color: #2c2c2c;
}

.dda-buttons {
  display: flex;
  gap: 18px;
  flex-wrap: wrap;
}

.btn-primary,
.btn-secondary {
  padding: 16px 32px;
  text-decoration: none;
  font-size: 14px;
  letter-spacing: 1.5px;
  font-weight: 600;
  transition: 0.3s ease;
}

.btn-primary {
  background: #0f5c52;
  color: #fff;
}

.btn-primary:hover {
  background: #0b483f;
}

.btn-secondary {
  border: 1px solid #0f5c52;
  color: #0f5c52;
  background: transparent;
}

.btn-secondary:hover {
  background: #0f5c52;
  color: #fff;
}

.dda-philosophy-section {
  padding-top: 20px;
}

.dda-mini-cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin-top: 45px;
}

.dda-card {
  background: #fff;
  padding: 30px;
  border-radius: 8px;
  border: 1px solid #ece7e0;
}

.dda-card h4 {
  font-size: 20px;
  color: #0f5c52;
  margin-bottom: 12px;
  font-family: 'Cormorant Garamond', serif;
}

.dda-card p {
  font-size: 15px;
  line-height: 1.7;
  margin: 0;
}

.second-image {
  height: 650px;
}

@media (max-width: 1024px) {

  .dda-grid {
    grid-template-columns: 1fr;
    gap: 50px;
  }

  .reverse-grid {
    display: flex;
    flex-direction: column-reverse;
  }

  .dda-content h2 {
    font-size: 44px;
  }

  .dda-feature-row {
    grid-template-columns: repeat(2, 1fr);
  }

  .dda-mini-cards {
    grid-template-columns: 1fr;
  }

  .dda-image-placeholder,
  .second-image {
    height: 500px;
  }
}

@media (max-width: 768px) {

  .dda-about-wrapper {
    padding: 60px 20px;
  }

  .dda-content h2 {
    font-size: 38px;
  }

  .dda-content p {
    font-size: 16px;
    line-height: 1.8;
  }

  .dda-feature-row {
    grid-template-columns: 1fr;
  }

  .dda-buttons {
    flex-direction: column;
  }

  .btn-primary,
  .btn-secondary {
    text-align: center;
  }

  .dda-image-placeholder,
  .second-image {
    height: 420px;
  }
}
```

---

# Recommended Fonts

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
```

---

# Image Replacement

Replace this:

```html
<div class="dda-image-placeholder">
```

With:

```html
<img src="YOUR-IMAGE.jpg" alt="Diamond District Aesthetics NYC" class="dda-real-image">
```

And add this CSS:

```css
.dda-real-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 10px;
}
```

---

# Why This Layout Works Better

* Cleaner reading flow for patients
* Better visual hierarchy
* SEO-rich content still preserved
* More luxury/premium aesthetic
* Better mobile responsiveness
* Easier image management
* Stronger conversion-focused structure
* More whitespace improves readability
* 1300px max width keeps premium website feel instead of “poster layout”
