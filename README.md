# NetInfra MonoRepo

---

This monorepo contains several sub-projects related to the overall NetInfra project. NetInfra is a method of defining networks as code in a structured yaml file. This structure was created to be authoritative, flexible, and extendable. It is intended to be a single source of truth that configuration management software can ingest to deploy networks. This project was originally published in the proceedings of the [Practice & Experience in Advanced Research Computing 2022](https://pearc.acm.org/pearc22/) conference.

---

## Publication
<p align="center">
  <img src="https://pearc.acm.org/pearc22/wp-content/uploads/2021/09/cropped-PEARC22-LOGOwIcon-TransparentBKG.png" alt="Pearc 22 Logo" />
</p>
The concept of NetInfra was first created and published as an academic paper in the [PEARC '22 Conference Proceedings](https://dl.acm.org/doi/proceedings/10.1145/3491418). The conference was held in Boston, MA from July 10 to July 14, 2022.

### Authors
  - [Erick Joel McGhee](https://dl.acm.org/profile/99660512443)
  - [Tom Krobatsch](https://dl.acm.org/profile/99660514432)
  - [Stephen Milton](https://dl.acm.org/profile/99660512500)

### Read Online
The original paper is available to be read for free via Open Access on the [ACM Digital Library](https://dl.acm.org/).

- DOI.org link to paper: https://doi.org/10.1145/3491418.3530762

### Presentation
The authors gave a presentation of the paper at the conference. The presentation slides can be found in this repo in various formats.

- Original PowerPoint Presentation: [PEARC22-NETINFRA.pptx](./presentation/PEARC22-NETINFRA.pptx)
- Slides PDF: [PEARC22-NETINFRA.pdf](./presentation/PEARC22-NETINFRA.pdf)

---

## Example
An example NetInfra file can be found in the [ansible directory](./ansible/group_vars/NetInfra.yml).

---

## Ansible
Ansible is the original target configuration management platform for NetInfra. Included are several roles designed to work with NetInfra.

### bind9

### kea


