# 📋 Trosta Chairs — Site Data Template

Use this template to provide product data, logo, and reviews from **www.trostachairs.com** so the website can be updated with real content.

> **How to use:** Fill in the sections below and either:
> - Paste it as a comment on the GitHub Pull Request
> - Open a new GitHub Issue with this content
> - Edit `index.html` directly using the format shown here

---

## 🏷️ Logo

Upload your logo to [imgbb.com](https://imgbb.com/) and paste the direct image URL here:

```
Logo URL: (paste URL here)
```

---

## 🪑 Products

Fill in each product. Add or remove rows as needed.

### Product 1
- **Name:** Bubble
- **Price (₹):** 13570
- **Category:** Executive Chairs
- **Image URL:** https://i.ibb.co/whXmQStP/Bubble-1.jpg
- **Description:** Premium executive chair for Boss cabin with high-back support and luxurious cushioning.

### Product 2
- **Name:** Amaze HB
- **Price (₹):** 4956
- **Category:** Ergonomic Chairs
- **Image URL:** https://i.ibb.co/gLRhvmsv/12.jpg
- **Description:** Ergonomic high-back chair with adjustable lumbar support and breathable mesh.

### Product 3
- **Name:** Monarch
- **Price (₹):** 13570
- **Category:** Executive Chairs
- **Image URL:** https://i.ibb.co/KjgM7VL0/Monarch.jpg
- **Description:** Premium executive chair with luxurious leather finish and multi-lock tilt mechanism.

### Product 4
- **Name:** Cherry
- **Price (₹):** 4956
- **Category:** Staff Chairs
- **Image URL:** https://i.ibb.co/5WwXHBfx/Cherry.jpg
- **Description:** Durable and comfortable staff chair with padded seat and ergonomic backrest.

### Product 5
- **Name:** (enter name)
- **Price (₹):** (enter price)
- **Category:** (Executive Chairs / Ergonomic Chairs / Staff Chairs / Visitor Chairs)
- **Image URL:** (upload to imgbb.com and paste URL)
- **Description:** (1-line description)

### Product 6
- **Name:** (enter name)
- **Price (₹):** (enter price)
- **Category:** (Executive Chairs / Ergonomic Chairs / Staff Chairs / Visitor Chairs)
- **Image URL:** (upload to imgbb.com and paste URL)
- **Description:** (1-line description)

*(Copy and paste more product blocks as needed)*

---

## ⭐ Customer Reviews

Fill in each review. Add or remove as needed.

### Review 1
- **Customer Name:** (e.g. Rajesh Patel)
- **Rating:** ★★★★★ (1–5 stars)
- **Review Text:** "(paste the review here)"
- **Company/Role:** (e.g. IT Company, Ahmedabad)

### Review 2
- **Customer Name:** 
- **Rating:** ★★★★★
- **Review Text:** ""
- **Company/Role:** 

### Review 3
- **Customer Name:** 
- **Rating:** ★★★★★
- **Review Text:** ""
- **Company/Role:** 

---

## 🖼️ Hero/Banner Images

Upload any hero section images and paste URLs:

```
Hero Banner: https://i.ibb.co/KcwRq3XY/Main-Banner.png
About Section Image: (paste URL)
```

---

## 📝 How the Data Gets Used

Once you provide this data, it will be plugged into `index.html`:

**Products** go into the JavaScript array:
```javascript
const products = [
    { id: 1, name: "Bubble", price: 13570, category: "Executive Chairs", image: "https://...", desc: "..." },
    { id: 2, name: "Amaze HB", price: 4956, category: "Ergonomic Chairs", image: "https://...", desc: "..." },
    // ... more products
];
```

**Reviews** go into the testimonials HTML section:
```html
<div class="testimonial-card reveal">
    <div class="testimonial-stars">★★★★★</div>
    <p class="testimonial-text">"Review text here"</p>
    <div class="testimonial-author">
        <div class="author-avatar">R</div>
        <div class="author-info">
            <h4>Customer Name</h4>
            <p>Company, City</p>
        </div>
    </div>
</div>
```

**Logo** replaces the text brand or gets added as an `<img>` in the header.

---

> 💡 **Tip:** The fastest way is to upload all product images to [imgbb.com](https://imgbb.com/) and share the links along with the product details!
