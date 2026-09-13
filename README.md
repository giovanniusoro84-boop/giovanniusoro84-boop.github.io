# giovanniusoro84-boop.github.ioindex.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <meta name="description"
        content="ZephanGoods — Smart finds. Great deals. Delivered.">

  <title>ZephanGoods | Shop & Order</title>

  <style>
    :root {
      --blue: #0b5cff;
      --blue-dark: #063fb3;
      --green: #16a34a;
      --yellow: #fffc00;
      --ink: #101828;
      --muted: #667085;
      --line: #e4e7ec;
      --bg: #f6f8fc;
      --white: #ffffff;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      font-family: Inter, Arial, Helvetica, sans-serif;
      color: var(--ink);
      background:
        radial-gradient(
          circle at top right,
          rgba(11, 92, 255, .10),
          transparent 35%
        ),
        var(--bg);
    }

    .wrap {
      width: min(100% - 32px, 520px);
      margin: 0 auto;
      padding: 28px 0 35px;
    }

    .card {
      background: var(--white);
      border: 1px solid rgba(16, 24, 40, .07);
      border-radius: 28px;
      padding: 30px 22px 22px;
      box-shadow: 0 18px 55px rgba(16, 24, 40, .08);
    }

    /* BRAND */
    .brand {
      display: flex;
      align-items: center;
      gap: 12px;
      margin-bottom: 26px;
    }

    .mark {
      width: 58px;
      height: 58px;
      border-radius: 15px;
      display: grid;
      place-items: center;
      background: linear-gradient(
        145deg,
        var(--blue),
        #2f7aff
      );
      color: white;
      font-weight: 900;
      font-size: 21px;
      letter-spacing: -1px;
      overflow: hidden;
    }

    .mark img {
      width: 100%;
      height: 100%;
      object-fit: contain;
    }

    .brand-name {
      font-size: 20px;
      font-weight: 900;
      letter-spacing: -.5px;
    }

    .verified {
      color: var(--blue);
      font-size: 14px;
      margin-left: 5px;
    }

    .brand-sub {
      margin-top: 3px;
      color: var(--muted);
      font-size: 12px;
    }

    /* HERO */
    .hero {
      text-align: center;
      padding: 8px 8px 24px;
    }

    .hero-logo {
      width: 140px;
      height: 140px;
      object-fit: contain;
      margin: 0 auto 15px;
      display: block;
      border-radius: 20px;
    }

    .hero h1 {
      margin: 0 0 10px;
      font-size: clamp(30px, 8vw, 42px);
      line-height: 1.05;
      letter-spacing: -1.8px;
    }

    .hero p {
      margin: 0 auto;
      max-width: 390px;
      color: var(--muted);
      line-height: 1.55;
      font-size: 15px;
    }

    /* TRUST */
    .trust {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 8px;
      margin: 4px 0 22px;
    }

    .trust div {
      padding: 12px 6px;
      text-align: center;
      border: 1px solid var(--line);
      border-radius: 14px;
      font-size: 11px;
      font-weight: 700;
    }

    .trust span {
      display: block;
      font-size: 18px;
      margin-bottom: 5px;
    }

    /* PRODUCTS */
    .section-title {
      font-size: 13px;
      font-weight: 800;
      text-transform: uppercase;
      letter-spacing: .9px;
      margin: 0 0 10px;
      color: #344054;
    }

    .products {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
      margin-bottom: 22px;
    }

    .product {
      border: 1px solid var(--line);
      border-radius: 16px;
      padding: 15px;
      background: #fbfcfe;
    }

    .product strong {
      display: block;
      font-size: 14px;
      margin-bottom: 5px;
    }

    .product small {
      color: var(--muted);
      line-height: 1.4;
    }

    /* BUTTONS */
    .actions {
      display: grid;
      gap: 11px;
    }

    .btn {
      width: 100%;
      border: 0;
      border-radius: 15px;
      padding: 16px 18px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 9px;
      text-decoration: none;
      font-size: 15px;
      font-weight: 800;
      cursor: pointer;
      transition: transform .15s ease;
    }

    .btn:active {
      transform: scale(.98);
    }

    .whatsapp {
      color: white;
      background: var(--green);
      box-shadow: 0 8px 20px rgba(22, 163, 74, .20);
    }

    .snapchat {
      color: #111;
      background: var(--yellow);
      box-shadow: 0 8px 20px rgba(0, 0, 0, .08);
    }

    .browse {
      color: var(--ink);
      background: white;
      border: 1px solid var(--line);
    }

    /* NOTE */
    .note {
      text-align: center;
      color: var(--muted);
      font-size: 11px;
      line-height: 1.5;
      margin: 17px 8px 0;
    }

    /* FOOTER */
    footer {
      text-align: center;
      color: #98a2b3;
      font-size: 11px;
      padding-top: 18px;
    }

    @media (max-width: 360px) {
      .trust div {
        font-size: 10px;
      }

      .products {
        grid-template-columns: 1fr;
      }

      .hero-logo {
        width: 115px;
        height: 115px;
      }
    }
  </style>
</head>

<body>

  <main class="wrap">

    <section class="card">

      <!-- BRAND -->
      <div class="brand">

        <div class="mark">
          <!-- Upload your logo to GitHub as logo.png -->
          <img src="logo.png" alt="ZephanGoods logo">
        </div>

        <div>
          <div class="brand-name">
            ZephanGoods
            <span class="verified">✓</span>
          </div>

          <div class="brand-sub">
            Smart finds. Great deals. Delivered.
          </div>
        </div>

      </div>


      <!-- HERO -->
      <div class="hero">

        <img
          class="hero-logo"
          src="logo.png"
          alt="ZephanGoods"
        >

        <h1>Shop smarter.</h1>

        <p>
          Discover useful gadgets, accessories,
          lifestyle products and trending finds —
          all from one place.
        </p>

      </div>


      <!-- TRUST -->
      <div class="trust">

        <div>
          <span>🛍️</span>
          Quality Finds
        </div>

        <div>
          <span>📦</span>
          Delivery Available
        </div>

        <div>
          <span>💬</span>
          Easy Ordering
        </div>

      </div>


      <!-- PRODUCTS -->
      <p class="section-title">
        What we offer
      </p>

      <div class="products">

        <div class="product">
          <strong>📱 Phone Accessories</strong>
          <small>
            Stands, holders and useful mobile gadgets.
          </small>
        </div>

        <div class="product">
          <strong>🎧 Electronics</strong>
          <small>
            Earbuds and everyday tech essentials.
          </small>
        </div>

        <div class="product">
          <strong>🏠 Home & Lifestyle</strong>
          <small>
            Practical products for everyday life.
          </small>
        </div>

        <div class="product">
          <strong>🔥 Trending Finds</strong>
          <small>
            New products worth checking out.
          </small>
        </div>

      </div>


      <!-- ACTION BUTTONS -->
      <div class="actions">

        <!-- WHATSAPP ORDER -->
        <a
          class="btn whatsapp"
          href="https://wa.me/2348129569302?text=Hello%20ZephanGoods%20%F0%9F%91%8B%0A%0AI%27d%20like%20to%20place%20an%20order.%0A%0AProduct%3A%20%0AQuantity%3A%20%0AName%3A%20%0ADelivery%20Location%3A%20%0A%0APlease%20confirm%20availability%2C%20price%20and%20delivery%20details.%20Thank%20you!"
          target="_blank"
          rel="noopener"
        >
          💬 Order on WhatsApp
        </a>


        <!-- SNAPCHAT -->
        <a
          class="btn snapchat"
          href="https://www.snapchat.com/add/giozecode"
          target="_blank"
          rel="noopener"
        >
          👻 Contact on Snapchat
        </a>


        <!-- CATALOGUE -->
        <a
          class="btn browse"
          href="https://wa.me/2348129569302?text=Hello%20ZephanGoods%2C%20please%20send%20me%20your%20latest%20catalogue%20and%20prices."
          target="_blank"
          rel="noopener"
        >
          📋 Request Catalogue & Prices
        </a>

      </div>


      <!-- INFO -->
      <p class="note">
        Click WhatsApp to order directly.
        For product availability, pricing and
        delivery information, our team will respond.
      </p>

    </section>


    <!-- FOOTER -->
    <footer>
      © 2026 ZephanGoods · All rights reserved.
    </footer>

  </main>

</body>
</html>
