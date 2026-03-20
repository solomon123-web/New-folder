# KINGDOM WORSHIP - Project Structure

## 📁 Project Organization

The project has been reorganized with the following structure:

```
KINGDOM WORSHIP/
├── pages/                    # HTML Pages
│   ├── Index.html
│   ├── About.html
│   ├── Contact.html
│   ├── Event.html
│   ├── Facebook.html
│   ├── Home.html
│   ├── Instagram.html
│   ├── Kingdom.html
│   ├── New.html
│   ├── online.html
│   ├── Prayer.html
│   ├── Prayers.html
│   ├── Registerforinperson.html
│   ├── Registernow.html
│   ├── Sermons.html
│   ├── TikTok.html
│   ├── Twiter.html
│   ├── Upcoming.html
│   ├── Watch Sermons.html
│   ├── YouTube.html
│   └── MY IMAGE.jpg
│
├── css/                      # Stylesheets
│   └── style.css
│
├── js/                       # JavaScript Files
│   └── script.js
│
├── Images/                   # Images & Media
│   ├── edwin-andrade-6liebVeAfrY-unsplash.jpg
│   ├── WhatsApp Image 2025-12-30 at 2.36.04 AM.jpeg
│   ├── BISHOP.jpg
│   ├── IMG-20250818-WA0001.jpg
│   ├── Sunday1.jpg
│   ├── Sunday.jpg
│   ├── Church.jpg
│   ├── Church....jpg
│   ├── Church..jpg
│   ├── youtube.png
│   ├── facebook1.png
│   ├── tiktok logo.png
│   ├── instagram.png
│   └── x logo.png
│
└── README.md                 # This file
```

## 🔄 Updated File References

All HTML files have been updated to use the correct paths:

- **CSS**: `href="../css/style.css"`
- **Images**: `src="../Images/[filename]"`
- **JavaScript**: `src="../js/script.js"`
- **Internal Links**: HTML-to-HTML links remain unchanged (e.g., `href="Index.html"`)

The CSS file has also been updated to reference images correctly:
- **Image URLs in CSS**: `url("../Images/[filename]")`

## 📋 File Count Summary

- **HTML Pages**: 20 files
- **CSS Stylesheets**: 1 file
- **JavaScript Files**: 1 file
- **Images**: 14 files

## 🚀 Benefits of This Structure

1. **Organization**: Clear separation of concerns (pages, styles, scripts)
2. **Maintainability**: Easier to find and update specific asset types
3. **Scalability**: Ready for expansion (e.g., adding more pages, styles, or scripts)
4. **Professional**: Follows standard web project best practices
5. **Performance**: Easier to implement caching and optimize file loading

## 💡 Notes

- All internal page links in the navigation remain unchanged since all HTML files are in the same `pages` folder
- The `Images` folder contains all media assets used throughout the website
- All paths have been automatically updated to work with the new folder structure
