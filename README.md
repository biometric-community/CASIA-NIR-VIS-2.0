# CASIA NIR-VIS 2.0

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FCASIA--NIR--VIS--2.0-181717?logo=github)](https://github.com/biometric-community/CASIA-NIR-VIS-2.0)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://www.cbsr.ia.ac.cn/english/NIR-VIS-2.0-Database.html)

**CASIA NIR-VIS 2.0** — tbiom catalog packaging for `casia-nir-vis` (cross-spectral; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/CASIA-NIR-VIS-2.0
- **Upstream source**: http://www.cbsr.ia.ac.cn/english/NIR-VIS-2.0-Database.html
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `casia-nir-vis` |
| Category | `cross-spectral` |
| Access | `register` |
| Upstream homepage | http://www.cbsr.ia.ac.cn/english/NIR-VIS-2.0-Database.html |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: CASIA NIR-VIS 2.0 heterogeneous face.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/CASIA-NIR-VIS-2.0.git
cd CASIA-NIR-VIS-2.0
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_casia_nir_vis.sh
```

Place licensed archives under `projects/datasets/casia-nir-vis/` (gitignored).

## Dataset structure

```text
CASIA-NIR-VIS-2.0/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://www.cbsr.ia.ac.cn/english/NIR-VIS-2.0-Database.html
- Packaging: https://github.com/biometric-community/CASIA-NIR-VIS-2.0/issues
