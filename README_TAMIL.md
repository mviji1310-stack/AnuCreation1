# Anu Creation Website — React + Vite

## தேவைகள்
- Node.js LTS நிறுவவும்: https://nodejs.org/
- VS Code விருப்பமான editor.

## இயக்குவது
1. `anu-creation` folder-ஐ extract செய்யவும்.
2. VS Code-ல் அந்த folder-ஐ திறக்கவும்.
3. Terminal → New Terminal திறக்கவும்.
4. கீழே உள்ள commands ஒவ்வொன்றாக இயக்கவும்:

```bash
npm install
npm run dev
```

5. Terminal-ல் வரும் local URL-ஐ browser-ல் திறக்கவும். பொதுவாக `http://localhost:5173`.

## Production build
```bash
npm run build
npm run preview
```

## மாற்ற வேண்டிய முக்கிய தகவல்கள்
- WhatsApp number: `src/App.jsx`-ல் `WHATSAPP` மாறியை மாற்றவும். இந்திய எண்ணை 10 இலக்கங்களாக country code இல்லாமல் எழுதவும்.
- Email: `src/App.jsx`-ல் `Replace with your business email` என்பதை உங்கள் email-ஆல் மாற்றவும்.
- Location: Coimbatore, Tamil Nadu என்பதை உங்கள் business address-க்கு மாற்றவும்.
- Gallery: Admin → Gallery → Add image மூலம் நேரடி image URL சேர்க்கலாம்.
- Property listings: Admin → Properties → Add listing மூலம் listings சேர்க்கலாம்.
- Services: Admin → Services → Add service மூலம் services சேர்க்கலாம்.

## Admin demo
Footer-ல் `Admin Login` கிளிக் செய்யவும்.
Demo password: `anu123`

**முக்கிய பாதுகாப்பு குறிப்பு:** இது front-end demo மட்டுமே. Password browser code-ல் உள்ளது; பாதுகாப்பான login அல்ல. Enquiries மற்றும் content அந்த browser-ன் LocalStorage-ல் மட்டுமே சேமிக்கப்படும். வேறு சாதனங்களுக்கு sync ஆகாது; browser data அழிந்தால் இழக்கப்படலாம். Public production பயன்பாட்டிற்கு முன் secure authentication, backend/database மற்றும் privacy policy அமைக்க வேண்டும்.

## இலவச hosting
- Static website-ஐ GitHub Pages, Netlify அல்லது Vercel-ல் deploy செய்யலாம். இலவச plan-களின் வரம்புகள் மாறக்கூடும்.
- Custom domain பொதுவாக தனியாக வாங்க வேண்டும்.
- Google Maps embed இந்த demo-வில் Coimbatore-ஐக் காட்டுகிறது; சரியான business location-க்கு மாற்றவும்.
- Gallery மற்றும் property images sample remote images. வெளியிடும் முன் உங்கள் சொந்த images பயன்படுத்தவும்.
