# The Brand Alchemists – Creative Agency Website

This is a full-featured front-end website for **The Brand Alchemists**, a Nairobi-based creative agency offering branding, digital marketing, multimedia production, and more.

## 🌐 Live Features

- Responsive navigation bar with logo and anchor links
- Hero section with headline and call-to-action
- Unique Selling Proposition (USP) section
- Services overview in a structured grid
- Filterable portfolio gallery
- About section with agency story and team
- Contact form with WhatsApp integration
- Contact details and social media links

---

## 📁 Project Structure

```
.
├── index.html            # Main HTML file
├── style.css             # (Optional) Link your external CSS here
├── /assets               # Folder for custom images & icons
└── README.md             # Project documentation
```

---

## 🚀 How It Works

- **Contact Form:** The form data is collected and used to generate a pre-filled WhatsApp message to the agency's number.
- **Portfolio Filters:** Each portfolio item can be filtered by category using JavaScript (logic can be extended).
- **Icons:** Uses Font Awesome for scalable vector icons.

---

## 📌 Technologies Used

- HTML5
- CSS3 (add your external stylesheet if not included inline)
- JavaScript (for WhatsApp message generation)
- Font Awesome (for icons)

---

## ✅ How to Use

1. Clone this repo or download the HTML file.
2. Replace placeholder images with your actual project assets.
3. Update the WhatsApp number in the `<script>` with your own:  
   ```javascript
   const phoneNumber = '254112412041';
   ```
4. Customize the content, services, and team members to reflect your brand.

---

## 📞 Contact Information (Demo)

- **Studio:** Westlands Office Park, Nairobi  
- **Email:** hello@brandalchemists.co.ke  
- **Phone:** +254 700 123 456  
- **Hours:** Mon–Fri: 9AM – 5PM  
- **Socials:** Instagram, LinkedIn, Twitter, Facebook

---

## 📌 Notes

- The WhatsApp integration opens a new tab to initiate a chat with pre-filled client inquiry.
- Consider using a back-end form handler (like Formspree, Netlify Forms, or a PHP/Node.js backend) for email submissions if WhatsApp is not preferred.

---

## 💡 Future Enhancements

- Mobile responsiveness enhancements with CSS Flex/Grid
- Backend integration for form submissions
- Portfolio lightbox or modal previews
- Blog or news section

---

## 📷 License

This is a demo site and not under any open license. For client or agency use only.