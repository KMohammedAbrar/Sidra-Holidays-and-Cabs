Sidra Holidays & Cabs — image folder
====================================

The pages currently load royalty-free travel photography from the Unsplash CDN so the
site looks complete the moment you open it. To use your own photography instead:

  1. Drop your files in this folder using these names:
       hero.jpg, car-hire.jpg, corporate-travel.jpg, couples-travel.jpg, day-trip.jpg,
       family-trips.jpg, honeymoon.jpg, international-travel.jpg, about.jpg, cta.jpg
  2. In the HTML files, find and replace the https://images.unsplash.com/... src values
     with assets/images/<file>.jpg (relative paths already work from every page).
  3. Package images also live in js/script.js inside the PACKAGES object.

Recommended sizes: hero 1920x1080, cards 1200x750, all saved as optimised JPG or WebP.
logo.svg / logo.png in this folder are the brand mark; the header uses an inline copy.
Testimonial avatars in testimonials/ are monogram placeholders — swap in real photos.
