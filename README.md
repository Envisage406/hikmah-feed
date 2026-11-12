# Hikmah cards feed

The Hikmah app downloads `feed.json` when it has internet (at most every 3 hours) and keeps it on the phone.

- `hijriOffset`: whole days (-2 to 2) added before working out the Hijri date. Use it when the moon is sighted
  a day earlier or later than the Umm al-Qura calendar (Ramadan, Eid).
- `cards`: extra cards. Each has either `"date": "YYYY-MM-DD"` (a Gregorian day) or `"hijri": "M-D"`
  (for example `"9-27"` = 27 Ramadan), then `en` and `ar`, each with `t` (title), `x` (text) and `s` (source).
  An online card wins over the built-in card for that day.

Only put text here that has been checked: Qur'an references and authentic hadith.
