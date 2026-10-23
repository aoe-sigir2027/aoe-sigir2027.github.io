# AOE@SIGIR 2027 Workshop Website

Proposal-stage website for the Workshop on Agent-in-the-Loop Optimization for E-commerce AI Systems (AOE), targeting SIGIR 2027.

## Status and dates

Workshop acceptance and official SIGIR 2027 workshop dates are pending. Every page labels the timeline as provisional, based on the [SIGIR 2026 workshop call](https://sigir2026.org/en-AU/pages/submissions/workshop-proposals) with the year changed to 2027. Paper submission: April 17; notification: May 21; workshop: July 24. CFP announcement follows proposal acceptance. Dates are AoE; program times are local to San Jose (PDT, UTC−7).

See `../paper/README.md` for the separate proposal timeline and outstanding proposal requirements. [SIGIR 2027](https://sigir2027.org/) lists San Jose, California, USA as the host city. Speaker participation must be reconfirmed for the new event.

## Local preview

```bash
python3 -m http.server 8000
```

Visit http://localhost:8000. The static site has no build step.

## GitHub migration

Organization and repository renamed successfully: `aoe-sigir2027/aoe-sigir2027.github.io`.
Local `origin`: `https://github.com/aoe-sigir2027/aoe-sigir2027.github.io.git`.
Site URL: https://aoe-sigir2027.github.io/

Publication configuration: public repository, with GitHub Pages serving `main` from the repository root. The site is static; `.nojekyll` disables unnecessary Jekyll processing. The tentative program matches the proposal, and all submission types use 4–8 pages excluding references.

Existing portraits and historical photo attribution are retained in `assets/photo-sources.txt`. The Hong Kong hero image has been replaced with a neutral CSS gradient for the venue change.
