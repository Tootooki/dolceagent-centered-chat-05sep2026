# DOLCE AGENT — Smaller Centered Chat

Based on `dolceagent-scrolling-totals-05sep2026`.

The chat opens as a smaller window centered within the available space between the header and footer. Its default size is capped at 640px wide and 560px high, with 24px side clearance and a reduced height on taller screens. Expand/restore uses the same centered area. Short screens and an active keyboard use the available height to keep the composer and tools accessible.

The launcher retains its position. Only chat layout CSS and its stylesheet version changed; message handling, tools, keyboard inset logic and the rest of the website are preserved.

Verification: all 8 chat unit tests and 9 chat integration tests passed. Browser checks covered 393×680, 320×500, 700×280 and 1440×900 layouts, expand/restore, tool scrolling and close/reopen. The default mobile window measured 345×510px, and desktop measured 640×560px. The composer remained visible in landscape and no browser errors were reported.

Publish with `npm run publish`.
