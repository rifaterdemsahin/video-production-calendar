# 📦 video-production-calendar

## 🔗 Live links

- 📦 **Repo:** https://github.com/rifaterdemsahin/video-production-calendar
- 🌐 **GitHub Pages (live):** https://rifaterdemsahin.github.io/video-production-calendar/
- 📅 **Calendar View:** https://rifaterdemsahin.github.io/video-production-calendar/5_Symbols/production_calendar.html
- 🎬 **Production pipeline:** https://github.com/rifaterdemsahin/VideoProductionPipeline
- 📝 **Weekly specs:** https://github.com/rifaterdemsahin/weekly-video-spec-template
- 📚 **Claude Associate dictionary:** https://github.com/rifaterdemsahin/ai-dictionary-timeline
- ▶️ **YouTube:** https://www.youtube.com/@RifatErdemSahin

---

**OKR-focused video production calendar** for AI certification courses on Skool — YouTube long + short, LinkedIn, and X releases.

## 🎯 OKRs (Objectives & Key Results)

### Objective
Create a reliable video production calendar for Skool AI certification courses, with releases across YouTube (long + short), LinkedIn, and X.

### Key Results
1. ✅ Maintain the published weekly cadence across all four platforms
2. 🎓 Ship Sprint 1 Claude Associate dictionary videos from ai-dictionary-timeline
3. 🔗 Keep every planned item linked to VideoProductionPipeline + weekly-video-spec-template
4. 🌐 Landing page + calendar docs stay deployable on GitHub Pages

## 📅 Production Cadence

| Platform | Frequency | Day(s) | Notes |
|----------|-----------|--------|-------|
| 🎥 YouTube long-form | 1× / week | **Monday** | 10–20 min deep-dives |
| 📱 YouTube Shorts | 3× / week | **Tue / Thu / Sat** | ~60s tips / terms |
| 💼 LinkedIn | 2× / week | **Wed / Fri** | Video + context |
| 🐦 X | 3–5× / week | **Varies** | Clips / threads |

### 📊 Visual Calendar

The **[📅 Calendar View](https://rifaterdemsahin.github.io/video-production-calendar/5_Symbols/production_calendar.html)** provides a digestible month/week view of the production schedule with color-coded platform indicators.

See `4_Formula/video_production_calendar.md` for Sprint 1 details and checklists.

## Framework

Built from the [delivery-pilot-template](https://github.com/rifaterdemsahin/delivery-pilot-template) 7-stage agentic workflow. Start in `1_Real_Unknown/`.

## Deploy note

CI runs `5_Symbols/toolbox/smoke_test.py` before Pages deploy. New markdown files must be registered in `5_Symbols/toolbox/nav_sync.py` MENU, then run `python3 5_Symbols/toolbox/nav_sync.py` so Nav 3-Way Sync stays green.
