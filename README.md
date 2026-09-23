# 📦 video-production-calendar

## 🔗 Live links

- 📦 **Repo:** https://github.com/rifaterdemsahin/video-production-calendar
- 🌐 **GitHub Pages (live):** https://rifaterdemsahin.github.io/video-production-calendar/
- 🎬 **Production pipeline:** https://github.com/rifaterdemsahin/VideoProductionPipeline
- 📝 **Weekly specs:** https://github.com/rifaterdemsahin/weekly-video-spec-template
- 📚 **Claude Associate dictionary:** https://github.com/rifaterdemsahin/ai-dictionary-timeline
- ▶️ **YouTube:** https://www.youtube.com/@RifatErdemSahin
- 🧭 **Calendar artifact:** https://rifaterdemsahin.github.io/video-production-calendar/5_Symbols/markdown_renderer.html?file=4_Formula/video_production_calendar.md

---

Video production calendar for AI certification courses on Skool — YouTube long + short, LinkedIn, and X releases.

## Goal

- **Objective:** create a video production calendar
- **Key result:** creating videos with cadence and releasing them to their medium
- **Environment:** producing with tools in VideoProductionPipeline
- **Sources:** research via weekly-video-spec-template
- **Current delivery:** Claude Associate course dictionary (ai-dictionary-timeline)

## Cadence (starting point)

| Platform | Frequency | Notes |
|----------|-----------|--------|
| YouTube long-form | 1× / week (Monday) | 10–20 min deep-dives |
| YouTube Shorts | 3× / week (Tue / Thu / Sat) | ~60s tips / terms |
| LinkedIn | 2× / week (Wed / Fri) | Video + context |
| X | 3–5× / week | Clips / threads |

See `4_Formula/video_production_calendar.md` for Sprint 1 and checklists.

## Framework

Built from the [delivery-pilot-template](https://github.com/rifaterdemsahin/delivery-pilot-template) 7-stage agentic workflow. Start in `1_Real_Unknown/`.

## Deploy note

CI runs `5_Symbols/toolbox/smoke_test.py` before Pages deploy. New markdown files must be registered in `5_Symbols/toolbox/nav_sync.py` MENU, then run `python3 5_Symbols/toolbox/nav_sync.py` so Nav 3-Way Sync stays green.
