<p align="center"><img src="https://raw.githubusercontent.com/go-newsgroups/brand/main/social/go-newsgroups.png" alt="go-newsgroups" width="640"></p>

<h1 align="center">go-newsgroups</h1>
<p align="center">Pure-Go Usenet: NNTP, yEnc, NZB, Newznab search, PAR2 (AutoPAR).</p>
<p align="center">[![docs](https://img.shields.io/badge/docs-mkdocs--material-0A6E96?style=flat-square&logo=materialformkdocs&logoColor=white)](https://go-newsgroups.github.io/docs/) ![packages](https://img.shields.io/badge/packages-5-0079A8?style=flat-square) ![Go](https://img.shields.io/badge/Go-1.26.4-00ADD8?style=flat-square&logo=go&logoColor=white) ![CGO](https://img.shields.io/badge/CGO-0-22CCE2?style=flat-square) ![license](https://img.shields.io/badge/license-BSD--3--Clause-0A6E96?style=flat-square)</p>

---

## What is this?

go-newsgroups is a family of small, composable pure-Go modules for Usenet: an RFC 3977 NNTP read client, yEnc / uuencode codecs, an NZB parser with segment download and reassembly, a Newznab / NZBHydra2 search client, and a PAR2 verify / Reed-Solomon repair library (the format behind AutoPAR). Every module is CGO_ENABLED=0 and standard-library-first.

Everything is **pure Go** (`CGO_ENABLED=0`), standard-library-first, and
cross-compiles to every 64-bit Go target.

## Packages (5)

| Package | What it does | API |
|---|---|---|
| [`newznab`](https://github.com/go-newsgroups/newznab) | Client for the Newznab / NZBHydra2 indexer search API. | [reference](https://pkg.go.dev/github.com/go-newsgroups/newznab) |
| [`nntp`](https://github.com/go-newsgroups/nntp) | RFC 3977 NNTP (Usenet) read client — plaintext or implicit TLS. | [reference](https://pkg.go.dev/github.com/go-newsgroups/nntp) |
| [`nzb`](https://github.com/go-newsgroups/nzb) | NZB parser + segment download & reassembly over NNTP with yEnc. | [reference](https://pkg.go.dev/github.com/go-newsgroups/nzb) |
| [`par2`](https://github.com/go-newsgroups/par2) | PAR2 parse / verify (MD5+CRC32) / Reed-Solomon repair (AutoPAR). | [reference](https://pkg.go.dev/github.com/go-newsgroups/par2) |
| [`yenc`](https://github.com/go-newsgroups/yenc) | yEnc and uuencode decode / encode for Usenet binaries. | [reference](https://pkg.go.dev/github.com/go-newsgroups/yenc) |

> This list is generated from the repos that actually exist in the org.

## Links

- Docs — <https://go-newsgroups.github.io/docs/>
- Site — <https://go-newsgroups.github.io/>
- Brand assets — <https://github.com/go-newsgroups/brand>

---
<p align="center"><sub>Branding in <a href="https://github.com/go-newsgroups/brand">go-newsgroups/brand</a>. Licensed BSD-3-Clause.</sub></p>
