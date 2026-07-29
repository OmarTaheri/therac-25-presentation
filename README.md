# Interactive presentations

Browser-based talks that use simulations, visual storytelling, and source-driven case studies to explain software failure, media systems, and power.

Live collection: [therac25.omartaheri.com](https://therac25.omartaheri.com)

<!-- Add a montage of both decks here. -->

## Presentations

### When Architecture Kills

Three software and numerical-failure case studies:

- Ariane 5 Flight 501;
- the Patriot missile timing error;
- the Therac-25 radiation overdoses.

The deck includes interactive explanations of overflow, floating-point drift, race conditions, and the organizational failures surrounding the code.

Entry point: `therac-25.html`

### Media Ownership in Morocco

An interactive look at media ownership, regulation, platform power, protest movements, surveillance, and the tension between national sovereignty and global technology companies.

Entry point: `morocco/index.html`

## Run locally

```bash
git clone https://github.com/OmarTaheri/interactive-presentations.git
cd interactive-presentations
python -m http.server 8000
```

Open <http://localhost:8000>.

## Controls

The presentations use reveal.js:

- arrow keys or space: move through slides;
- `Esc`: slide overview;
- `F`: fullscreen;
- swipe: navigate on touch devices.

Some slides contain interactive controls such as sliders, scenario buttons, and embedded media.

## Structure

```text
.
├── index.html          presentation collection
├── therac-25.html      software-failure deck
├── therac-25/          deck media
└── morocco/
    ├── index.html      media-ownership deck
    └── ...             deck media
```

## Research and attribution

Each factual claim, statistic, quotation, photograph, logo, and video should be traceable to a source. Before presenting or republishing:

1. add slide-level citations;
2. add a `SOURCES.md` bibliography;
3. record image and video ownership/licensing;
4. distinguish fact, analysis, and opinion;
5. date statistics and explain uncertainty;
6. give sensitive political and safety claims an additional verification pass.

## Technical notes

- reveal.js 5
- static HTML, CSS, and JavaScript
- responsive/landscape presentation layout
- embedded video and interactive simulations

## License

No open-source license is currently declared. Third-party media remains subject to its original terms.
