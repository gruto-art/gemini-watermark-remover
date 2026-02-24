# Gemini & Veo Watermark Remover

הסרת סימני מים מתמונות Gemini וסרטוני Veo - 100% מקומי, חינמי, ללא העלאה לשרת.

## Live Demo
- **תמונות Gemini**: https://gruto-art.github.io/gemini-watermark-remover/
- **וידאו Veo**: https://gruto-art.github.io/gemini-watermark-remover/video.html

## איך זה עובד?

הכלי משתמש ב-**Reverse Alpha Blending** - נוסחה מתמטית שמשחזרת את הפיקסלים המקוריים:

```
Original = (Current - White × α) / (1 - α)
```

זו שיטה מתמטית טהורה שלא פוגעת באיכות (בניגוד ל-inpainting עם AI).

## תכונות

### תמונות Gemini
- הסרת לוגו Gemini מתמונות
- תמיכה ב-JPG, PNG, WebP
- העלאת תיקיות שלמות
- הורדה אוטומטית (ZIP לתיקיות)

### וידאו Veo
- הסרת טקסט "Veo" מסרטונים
- תמיכה ב-MP4, WebM, MOV
- הגדרות מתכווננות (שקיפות, גודל, מיקום)
- פלט WebM באיכות גבוהה

## הרצה מקומית

```bash
# Clone
git clone https://github.com/gruto-art/gemini-watermark-remover.git
cd gemini-watermark-remover

# Open in browser
open index.html        # תמונות
open video.html        # וידאו
```

או פשוט להשתמש ב-Live Server:
```bash
npx serve .
```

## תמיכה בדפדפנים

| דפדפן | תמונות | וידאו |
|-------|--------|-------|
| Chrome 94+ | ✅ | ✅ |
| Edge 94+ | ✅ | ✅ |
| Firefox | ✅ | ✅ |
| Safari | ✅ | ✅ |

## ערכים מכוילים (Veo)

הערכים נמדדו מניתוח תמונה אמיתית:
- **שקיפות**: 52%
- **גופן**: Poppins / Google Sans
- **מרווח מימין**: 20px
- **מרווח מלמטה**: 12px

## Credits

- מבוסס על [gemini-watermark-remover](https://github.com/journey-ad/gemini-watermark-remover) מאת journey-ad
- פותח על ידי [@ELI_MALKA_AI](https://www.tiktok.com/@elimalka_ai)

## License

MIT
