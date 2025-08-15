# TheLastRockNRolla — WhenTheLi0nsHungry

**Tribute: One in a Billion**

---

## **Features**
- **Auto-updating malware/phishing protection:**  
  Pulls daily from [Hagezi TIF Mini](https://github.com/hagezi/dns-blocklists) & [DandelionSprout Mobile Malware](https://github.com/DandelionSprout/adfilt).
- **Hand-curated, mobile-first privacy filter:**  
  Blocks advanced trackers, fingerprinting, session replay, crypto/Web3, sketchy TLDs, shortlinks, and more.
- **Zero overlap with Brave’s built-in shields or major public lists.**
- **Performance-optimized:** Fast on Brave Android, minimal cosmetic rules.
- **Easy subscription:** Brave Android can subscribe directly to the latest filter.

---

## **How to use in Brave Android**
1. Copy the raw URL of `filters/brave-ultimate.txt`.
2. Paste it in Brave Android:  
   Settings → AdBlock → Custom Filters → Add Filter List.
3. Stay protected by the freshest, most advanced mobile filter.

---

## **Repo structure**
- `filters/legacy-custom.txt` — Your unique, hand-picked privacy rules.
- `filters/auto-malware.txt` — Auto-updating malware/phishing blocklist.
- `filters/brave-ultimate.txt` — Combined, deduplicated master filter.
- `.github/workflows/update.yml` — GitHub Action for daily updates.

---

## **Contributing**
- Submit PRs for new mobile threats, trackers, or feedback.
- All contributions are reviewed for Brave Android optimization.

---

## **Tribute**
> **One in a Billion**