let currentLang = 'pl';

const translations = {
  pl: {
    siteTitle: "Studio Graficzne Pixel",
    nav: ["O nas", "Sklep", "Kontakt"],
    aboutTitle: "O nas",
    aboutText: "Tworzymy unikalne projekty graficzne – od logo po pełną identyfikację wizualną. Studio Pixel to pasja, kreatywność i profesjonalizm.",
    shopTitle: "Sklep",
    product1Title: "Logo Premium",
    product1Desc: "Profesjonalne logo dostosowane do Twojej marki.",
    product1Btn: "Dodaj do koszyka",
    contactTitle: "Kontakt",
    form: {
      name: "Twoje imię",
      email: "Twój email",
      message: "Wiadomość",
      submit: "Wyślij"
    },
    footer: "© 2025 Studio Graficzne Pixel"
  },
  en: {
    siteTitle: "Pixel Graphic Studio",
    nav: ["About Us", "Shop", "Contact"],
    aboutTitle: "About Us",
    aboutText: "We create unique graphic designs – from logos to complete brand identity. Pixel Studio is passion, creativity, and professionalism.",
    shopTitle: "Shop",
    product1Title: "Premium Logo",
    product1Desc: "A professional logo tailored to your brand.",
    product1Btn: "Add to cart",
    contactTitle: "Contact",
    form: {
      name: "Your name",
      email: "Your email",
      message: "Message",
      submit: "Send"
    },
    footer: "© 2025 Pixel Graphic Studio"
  }
};

document.getElementById('lang-toggle').addEventListener('click', () => {
  currentLang = currentLang === 'pl' ? 'en' : 'pl';
  updateLanguage();
});

function updateLanguage() {
  const t = translations[currentLang];
  document.getElementById('site-title').textContent = t.siteTitle;
  document.getElementById('nav-about').textContent = t.nav[0];
  document.getElementById('nav-shop').textContent = t.nav[1];
  document.getElementById('nav-contact').textContent = t.nav[2];
  document.getElementById('about-title').textContent = t.aboutTitle;
  document.getElementById('about-text').textContent = t.aboutText;
  document.getElementById('shop-title').textContent = t.shopTitle;
  document.getElementById('product1-title').textContent = t.product1Title;
  document.getElementById('product1-desc').textContent = t.product1Desc;
  document.getElementById('product1-btn').textContent = t.product1Btn;
  document.getElementById('contact-title').textContent = t.contactTitle;
  document.getElementById('form-name').placeholder = t.form.name;
  document.getElementById('form-email').placeholder = t.form.email;
  document.getElementById('form-message').placeholder = t.form.message;
  document.getElementById('form-submit').textContent = t.form.submit;
  document.getElementById('footer-text').textContent = t.footer;
  document.getElementById('lang-toggle').textContent = currentLang === 'pl' ? "🇬🇧" : "🇵🇱";
}

updateLanguage();
