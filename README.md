# LAADAN-AC Project Website

Official project-page repository for **LAADAN-AC: Beyond Survival in Admissible Offline Treatment-Policy Learning**, by **Riya Basak** and **Manal Helal**.

**Accepted to ICaTAS 2026.**

- Project website: https://annyab.github.io/laadan-ac-website/
- Research code, results, and checkpoints: https://github.com/AnnyaB/laadan-ac


## Website

This repository contains the static academic project page for LAADAN-AC. The page presents the method, fixed-schedule evaluation, paired training-vs-post-hoc comparison, component ablations, cross-source portability study, and diagnostic visualizations using frozen research assets from the LAADAN-AC release.

```text
.
├── .nojekyll
├── index.html
├── README.md
├── LICENSE.md
└── static/
    ├── css/
    ├── js/
    └── images/
```

## Local Preview

From the repository root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/` in a browser.

## Acknowledgments

This project page adapts the open-source **Academic Project Page Template** by Eliahu Horwitz and follows the presentation structure used by the **Dreamweaver: Learning Compositional World Models from Pixels** project page by Junyeob Baek, Yi-Fu Wu, Gautam Singh, and Sungjin Ahn. The Academic Project Page Template itself adopts components from the **Nerfies** project page.

We thank the authors of these open project-page resources for making their website code publicly available.

- Dreamweaver project page repository: https://github.com/dion-jy/dreamweaver-website
- Academic Project Page Template: https://github.com/eliahuhorwitz/Academic-project-page-template
- Nerfies project page: https://nerfies.github.io/

## Website License

Template-derived website code and adaptations are provided under the **Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)**, consistent with the upstream project-page template.

The LAADAN-AC research code is maintained separately under the license stated in the research repository. Scientific figures, results, manuscript material, and publication metadata remain subject to their respective research-repository and publication terms.
