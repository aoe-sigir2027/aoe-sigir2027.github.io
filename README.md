# AOE@SIGIR 2027 Workshop Website

Website for the Workshop on Agent-in-the-Loop Optimization for E-commerce AI Systems (AOE) at SIGIR 2027.

## Content source

Workshop content is synchronized with `../paper/main-sigir2027.tex` and its `aoe@sigir2027/Section/` inputs as of November 24, 2026, paper commit `e05cf01`.

The invited-speaker pages list Chao Huang (The University of Hong Kong) and Qilin Qi (Amazon), without participation-status or duration badges. Chao Huang's expanded biography draws on his HKU Institute of Data Science profile. Qilin Qi's portrait comes from the WSDM 2026 GenAI4SM keynote page, with the source recorded in `assets/photo-sources.txt`. The eight-session afternoon agenda matches the proposal, without the earlier lightning introductions, small-group discussions, or plenary synthesis. All submission types remain 4–8 pages excluding references, with double-blind review.

The separate `../website/` checkout is the archived WSDM website and is not the deployment source for this SIGIR site.

## Status and dates

Displayed dates are unchanged from the proposal source: paper submission April 17, author notification May 21, and workshop July 24, 2027. Public pages omit proposal-stage notices and date qualifiers at the organizers' request. Paper deadlines are AoE, and program times are local to San Jose (PDT, UTC−7).

See `../paper/README.md` for the separate proposal timeline and outstanding proposal requirements. [SIGIR 2027](https://sigir2027.org/) lists San Jose, California, USA as the host city.

## Local preview

```bash
python3 -m http.server 8000
```

Visit http://localhost:8000. The static site has no build step.

## GitHub migration

Organization and repository renamed successfully: `aoe-sigir2027/aoe-sigir2027.github.io`.
Local `origin`: `git@github.com:aoe-sigir2027/aoe-sigir2027.github.io.git`.
Site URL: https://aoe-sigir2027.github.io/

Publication configuration: public repository, with GitHub Pages serving `main` from the repository root. The site is static; `.nojekyll` disables unnecessary Jekyll processing. The program matches the proposal, and all submission types use 4–8 pages excluding references.

Existing portraits and historical photo attribution are retained in `assets/photo-sources.txt`. The Hong Kong hero image has been replaced with a neutral CSS gradient for the venue change.
