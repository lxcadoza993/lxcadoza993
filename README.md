## Lena Cardoza

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat&logo=openapiinitiative&logoColor=white)

Developer experience engineer at LynxFlow — I write the integration code, the docs
that explain it, and the workshops where people type it out themselves.

---

### What I work on

**Integration examples.**
Every endpoint we ship gets a runnable client in at least Python, JavaScript, and
plain `curl`. Not pseudocode, not a fragment in a code fence — a file you can
clone and execute. If an example goes stale, that is a bug and it gets a fix
like any other.

**Developer workshops.**
Two-to-three hour sessions built around a working environment and a sequence of
small exercises. Most of the effort goes into the setup script: a room where a
third of the people cannot install dependencies has already lost its first hour.

**Documentation.**
Reference material generated from OpenAPI descriptions, and the hand-written
guides around it — quickstarts, error catalogs, migration notes. I follow the
Diátaxis split (tutorial / how-to / reference / explanation) because mixing
those four modes in one page is how docs become unreadable.

**Error messages and status codes.**
An unhelpful 400 costs more support time than a missing page of docs. I spend a
surprising amount of my week arguing about response bodies.

---

### Selected projects

**[api-examples](https://github.com/lxcadoza993/api-examples)**
The same REST workflow — list, fetch, create — implemented three times: Python
with `requests`, Node with the built-in `fetch`, and a POSIX shell script over
`curl`. Runs against a public demo API, so there is no key to obtain first.

**[workshop-kit](https://github.com/lxcadoza993/workshop-kit)**
The template I start every workshop from: an agenda with realistic timings, a
preflight script that verifies the room's toolchain before anyone sits down, and
three exercise stubs that build on each other.

**[bookmarks](https://github.com/lxcadoza993/bookmarks)**
A reading list I actually maintain — the specs, books, and tools I keep sending
to people who ask where to start with API design, DX, or technical writing.

---

### Notes on how I work

- Examples are tested, or they are deleted. A broken sample teaches the wrong
  thing twice: once about the API, once about whether we can be trusted.
- I prefer the standard library where it is good enough. Node has `fetch` now;
  most quickstarts do not need a dependency tree.
- Workshop exercises get written backwards, from the thing I want people to be
  able to do at the end.
- Docs bugs are filed in the same tracker as code bugs, with the same triage.

---

### Elsewhere

Reachable through GitHub — issues and discussions on any of the repositories
above, or the profile inbox. That is the only channel I check reliably, so it is
the only one listed here.

---

<sub>Opinions here are my own. Code in these repositories is MIT licensed unless a
repository states otherwise.</sub>
