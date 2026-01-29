---
title: Case study 1
slug: case-study-1
date: '2022-01-05'
excerpt: >-
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante lorem,
  tincidunt ac leo efficitur, feugiat tempor odio. Curabitur at auctor sapien.
  Etiam at cursus enim. Suspendisse sed augue tortor. Nunc eu magna vitae lorem
  pellentesque fermentum. Sed in facilisis dui.
featuredImage:
  url: /images/img-placeholder.svg
  altText: Case study 1
  styles:
    self:
      borderRadius: large
  type: ImageBlock
bottomSections:
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - items:
      - title: About Company
        tagline: This is the tagline
        subtitle: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Curabitur at
          auctor sapien.
        image:
          url: /images/telus-logo.svg
          altText: Company logo
          styles:
            self:
              margin:
                - ml-3
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pl-6
              - pb-6
              - pr-6
            textAlign: left
            borderColor: border-neutralAlt
            borderStyle: none
            borderWidth: 0
            borderRadius: none
            flexDirection: row
        type: FeaturedItem
    variant: small-list
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mb-20
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
isFeatured: true
colors: bg-light-fg-dark
styles:
  self:
    padding:
      - pt-5
      - pl-5
      - pb-5
      - pr-5
    textAlign: center
    borderColor: border-light
    borderStyle: none
    borderWidth: 0
    borderRadius: none
    flexDirection: col
type: PostLayout
---
<!DOCTYPE html> <html lang="uk"> <head>   <meta charset="UTF-8" />   <meta name="viewport" content="width=device-width, initial-scale=1.0"/>   <title>ТОВ «МЕНОРА ЛТД» — теплопостачання</title>   <style>     :root {       --bg: #f8f9fa;       --text: #1a1a1a;       --accent: #2c3e50;       --light-gray: #6b7280;       --border: #e5e7eb;     }      \* {       margin: 0;       padding: 0;       box-sizing: border-box;     }      body {       font-family: system-ui, -apple-system, sans-serif;       background: var(--bg);       color: var(--text);       line-height: 1.6;       padding: 2rem 1rem;     }      .container {       max-width: 680px;       margin: 0 auto;       background: white;       border-radius: 12px;       box-shadow: 0 4px 20px rgba(0,0,0,0.06);       overflow: hidden;     }      .header {       background: var(--accent);       color: white;       padding: 1.8rem 2rem;     }      .header h1 {       font-size: 1.55rem;       font-weight: 600;       letter-spacing: -0.02em;     }      .content {       padding: 2rem;     }      .section {       margin-bottom: 2.2rem;     }      .section-title {       font-size: 1.05rem;       font-weight: 600;       color: var(--accent);       margin-bottom: 0.9rem;       padding-bottom: 0.5rem;       border-bottom: 1px solid var(--border);     }      .info-grid {       display: grid;       grid-template-columns: 1fr 2fr;       gap: 0.9rem 1.4rem;       font-size: 0.97rem;     }      .info-grid dt {       color: var(--light-gray);       font-weight: 500;     }      .info-grid dd {       margin: 0;     }      .status {       color: #d97706;       font-weight: 600;     }      .contacts-list {       list-style: none;       display: grid;       gap: 1.1rem;     }      .contact-item {       display: flex;       flex-direction: column;       gap: 0.35rem;       font-size: 0.97rem;     }      .contact-item .name {       font-weight: 600;       color: var(--accent);     }      .contact-item .role {       color: var(--light-gray);       font-size: 0.92rem;     }      .phone {       color: #2563eb;       text-decoration: none;       font-weight: 500;     }      .phone:hover {       text-decoration: underline;     }      .email {       color: #2563eb;       text-decoration: none;     }      .email:hover {       text-decoration: underline;     }      @media (max-width: 520px) {       .info-grid {         grid-template-columns: 1fr;         gap: 0.7rem;       }       .content {         padding: 1.6rem;       }     }   </style> </head> <body>  <div class="container">   <div class="header">     <h1>ТОВ «МЕНОРА ЛТД»</h1>   </div>    <div class="content">      <div class="section">       <div class="section-title">Діяльність</div>       <p>Забезпечуємо виробництво та постачання теплової енергії з дахової газової котельні за адресою:       <strong>м. Дніпро, вул. Шолом-Алейхема, буд. 4/26</strong>       для орендарів нежитлових приміщень будівлі       Меморіальний комплекс «Холокост» з багатофункціональним Центром «Менора»</p>     </div>      <div class="section">       <div class="section-title">Статус ліцензування</div>       <p class="status">Статус: подання документів до органу ліцензування…</p>     </div>      <div class="section">       <div class="section-title">Вид діяльності</div>       <div class="info-grid">         <dt>Вид діяльності</dt>         <dd>Виробництво та постачання теплової енергії</dd>          <dt>Орган</dt>         <dd>Обласна військова адміністрація (за місцезнаходженням об’єкта)</dd>          <dt>Сайт</dt>         <dd><a href="https\://menorah-center.com" class="email">menorah-center.com</a></dd>       </div>     </div>      <div class="section">       <div class="section-title">Засоби комунікації зі споживачами</div>              <ul class="contacts-list">         <li class="contact-item">           <span class="name">Гуцалюк Ю.А.</span>           <span class="role">Начальник дільниці теплогазопостачання, вентиляції та кондиціювання</span>           <a href="tel:+380567177110" class="phone">+38 (056) 717-71-10</a>           <a href="mailto:hutsaliuk\@menorah-center.com" class="email">hutsaliuk\@menorah-center.com</a>         </li>          <li class="contact-item">           <span class="name">Диспетчерська служба</span>           <a href="tel:+380567177101" class="phone">+38 (056) 717-71-01</a>           <span>Цілодобово</span>           <a href="mailto:office\@menorah-center.com" class="email">office\@menorah-center.com</a>         </li>       </ul>     </div>      <div class="section">       <div class="section-title">Контакти компанії</div>       <div class="info-grid">         <dt>Компанія</dt>         <dd>ТОВ "МЕНОРА ЛТД"</dd>          <dt>ЄДРПОУ</dt>         <dd>38114085</dd>          <dt>ІПН</dt>         <dd>381140804639</dd>          <dt>Адреса</dt>         <dd>49000, м. Дніпро, вул. Шолом-Алейхема, буд. 4/26</dd>          <dt>Телефон</dt>         <dd><a href="tel:+380567177770" class="phone">+38 (056) 717-77-70</a></dd>          <dt>E-mail</dt>         <dd><a href="mailto:office\@menorah-center.com" class="email">office\@menorah-center.com</a></dd>       </div>     </div>    </div> </div>  </body> </html>

