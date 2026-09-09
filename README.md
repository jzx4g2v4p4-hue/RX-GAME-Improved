# 💊 RxReady — Pharmacy Arcade

A retro-arcade training game for retail pharmacists. Behind the CRT scanlines and
pixel sprites is a full bench-skills trainer: work a live counter against the clock,
or drill the individual skills that feed it. Responsive — plays on desktop and phone.

> ⚠️ **Training tool only.** Drug facts, schedules, reject codes, DEA-checksum logic,
> and Virginia rules are for study/practice. Defer to current references, package
> labeling, your pharmacy's policies, and the Virginia Board of Pharmacy / DHP in real
> practice. Pill imprints, NDCs, and DEA numbers shown are illustrative.

## 🎮 Modes

**Story mode — The Shift:** patients queue with 8-bit sprites carrying real tasks;
keep the line moving, earn tips, build combos, protect your reputation.

**Stage select — the drills:** Rapid Refill · Fill the Rx · At the Counter ·
Drug Mastery (300+ drug DB) · Rx Verification (clinical/DUR) · Script Lab (sig builder) ·
Insurance Desk (NCPDP reject codes) · Virginia Law · Verify Bench (data verification) ·
**Data Entry** · Fill Check (verify the technician's fill).

**Data Entry** is the deep one: pick the product/NDC and prescriber, type the sig with
a live system-style expander + shorthand autocomplete, get an auto days-supply
suggestion (handles tablets, mL, insulin units, inhaler puffs), set refills, DAW, and
origin code — and for controlled scripts, enter the prescriber's DEA number with a live
checksum validator.

## 🚀 Run locally

```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # production build → dist/
```

Requires Node.js 18+.

## 📦 Deploy to GitHub Pages

Includes `.github/workflows/deploy.yml`. After your first push: **Settings → Pages →
Source: GitHub Actions**. Site goes live at `https://<you>.github.io/<repo>/`.

## 📄 License

MIT — see [LICENSE](LICENSE).
