---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: hero
    content:
      title: Damla & Endre
      text: 👋 Düğünümüze hoş geldiniz! 👋
      primary_action:
        text: Lütfen katılım durumunuzu bize bildirin (form için buraya tıklayın)
        url: https://forms.gle/Bw9dwZUoYgspjnuJ9
        icon: calendar-days
      announcement:
        text: Sizden düğün tarihimizi not almanızı ve katılım durumunuzu bize
        link:
          text: bildirmenizi rica ediyoruz.
          url: https://forms.gle/ZPfoa3HFsrnePHmeA
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: lupines.jpg
          filters:
            brightness: 0.2
  - block: markdown
    id: schedule
    content:
      title: Program
      text: Düğünümüz 10 Ağustos 2024 tarihinde saat 18:30'da gerçekleşecektir. Detayları sizlerle yakında paylaşacağız.
  - block: cta-image-paragraph
    id: venue
    content:
      items:
        - title: Mekan
          text: ⭐ A11 Hotel Bosphorus ⭐
          feature_icon: check
          features:
            - "Adres: Mimar Sinan, Paşa Limanı Cd. No:4, 34550 Üsküdar/İstanbul"
            - "Web sitesi: https://a11hotel.com/"
            - "Not: Davetlilerimiz için otelde sınırlı sayıda oda ayırtılmıştır. Bilgi ve rezervasyon için Hasret Hanım'a ulaşabilirsiniz: +90 542 229 88 99"
          # Upload image to `assets/media/` and reference the filename here
          image: A11_wedding.jpeg
          button:
            text: Google maps link📍
            url: https://maps.app.goo.gl/GtT4GBTT9orkwY8c8
          design:
            css_class: "bg-gray-100 dark:bg-gray-900"
  - block: markdown
    id: contact
    content:
      title: İletişim
      text: |-
        Bizimle aşağıdaki yollardan iletişime geçebilirsiniz:
        - 📧 [damlaendre@gmail.com](email:damlaendre@gmail.com)
        - 📞 Damla: +49 172 665 85 68
        - 📞 Hilal: +90 532 424 38 96

---