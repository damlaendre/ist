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
      text: 👋 Welcome to our wedding website! 👋
      primary_action:
        text: RSVP by the 30th of April (click here)
        url: https://forms.gle/kxCG22e8vi8JcfM86
        icon: calendar-days
      announcement:
        text: At this stage, we only ask you to take note of the date and 
        link:
          text: RSVP by the 30th of April (click here).
          url: https://forms.gle/2Eq7oZhvQa5VHxc87/
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
      title: Schedule
      text: The wedding will take place on Aug. 10, starting at 18:30. Please RSVP by the 30th of April. More details will follow.
  - block: cta-image-paragraph
    id: venue
    content:
      items:
        - title: Venue
          text: ⭐ A11 Hotel Bosphorus ⭐
          feature_icon: check
          features:
            - "Address: Mimar Sinan, Paşa Limanı Cd. No:4, 34550 Üsküdar/İstanbul"
            - "[See here the Google maps link📍](https://maps.app.goo.gl/GtT4GBTT9orkwY8c8)"
            - "Website: https://a11hotel.com/"
            - "Instagram: https://www.instagram.com/a11hotelbosphorus/"
            - "Note: We suggest you write to us before approaching the hotel for any kind of issues, as their English-speaking staff is very limited. We negotiated a more favorable price at the hotel for wedding guests. See below."
          # Upload image to `assets/media/` and reference the filename here
          image: A11_wedding.jpeg
          button:
            text: How to get there & around
            url: /ist/en/travel
          design:
            css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: accommodation
    content:
      items:
        - title: Accommodation
          text: 🛏️ A11 Hotel Bosphorus !!!Discount until 31 April 2024!!!
          feature_icon: check
          features:
            - "We have a deal with the hotel until the end of April 2024, 15 rooms are reserved for us at a discounted price of 170 Euros (two people room) + 45 Euro per any extra person in the same room. Those who want to book a room should contact Mrs. Hasret at this number on WhatsApp +90 542 229 88 99. If the 15 rooms fill very fast, the hotel is flexible in extending the discounted rate for other rooms for our guests. We suggest you to make your room booking as soon as possible so we can negotiate further discounts for the rest of the rooms."
            - "The rooms vary in size, so while there are single/double ones, bigger ones can accommodate up to 4 people. Some rooms have a circular bed, others have a normal shaped bed, some room have a jacuzzi inside. All rooms have a Bosphorus view."
            - "If you wish to stay elsewhere, there are a few serviced apartments around the venue, as well as other hotels in the area. Unfortunately, Booking.com does not work anymore in Turkey and you should look for local alternatives for it."
            - "We strongly advice to stay in an area close to the wedding venue on the night of the wedding. Because you never know how the traffic might be in terms of arriving on time, or how the taxi situation would be in the evening without getting scammed."
          # Upload image to `assets/media/` and reference the filename here
          image: A11_hotel.jpg
          design:
            css_class: "bg-gray-100 dark:bg-gray-900"
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        You can get in touch with us at:
        - 📧 [damlaendre@gmail.com](email:damlaendre@gmail.com)
        - 📞 Damla: +49 172 665 85 68
        - 📞 Hilal: +90 532 424 38 96
---
