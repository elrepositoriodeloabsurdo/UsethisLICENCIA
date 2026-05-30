# License Reference Guide

Quick reference for all licenses LicenseAgent can recommend.

## Permissive licenses

### MIT
**Best for:** Libraries, utilities, tools you want maximum adoption of.  
**Key terms:** Do anything, keep copyright notice.  
**Used by:** React, Rails, .NET, jQuery, Bootstrap.  
**Copyleft:** None. **Patent grant:** No.

### Apache 2.0
**Best for:** Enterprise software, projects with multiple contributors, AI/ML models.  
**Key terms:** Do anything, keep notice, state changes, patent grant included.  
**Used by:** Android, Kubernetes, TensorFlow, many Apache Foundation projects.  
**Copyleft:** None. **Patent grant:** Yes (explicit).

### BSD-2-Clause
**Best for:** Simple libraries, academic software.  
**Key terms:** Keep copyright and license notice in source and binary.  
**Copyleft:** None. **Patent grant:** No.

### BSD-3-Clause
**Best for:** Same as BSD-2, plus prevents use of project name for endorsement.  
**Copyleft:** None. **Patent grant:** No.

### ISC
**Best for:** Very small utilities. Functionally equivalent to MIT.  
**Used by:** OpenBSD, many npm packages.

### Unlicense / WTFPL
**Best for:** When you want to waive all rights (public domain dedication).  
**Copyleft:** None. **Patent grant:** No.

---

## Copyleft licenses

### GPL-3.0
**Best for:** Software you want to remain forever open source.  
**Key terms:** Derivatives must use GPL-3.0. Must distribute source.  
**Used by:** Linux kernel (GPL-2.0), Bash, Ansible, uBlock Origin.  
**Copyleft:** Strong. **Patent grant:** Yes.

### GPL-2.0
**Best for:** Legacy compatibility with GPL-2.0 ecosystem.  
**Note:** Incompatible with GPL-3.0 unless "or later" clause included.

### LGPL-3.0 / LGPL-2.1
**Best for:** Libraries you want open but allow use in proprietary software.  
**Key terms:** Linking is OK; modifications to the library itself must be LGPL.  
**Used by:** GNU C Library, Qt (dual licensed).  
**Copyleft:** Weak (library boundary).

### AGPL-3.0
**Best for:** SaaS and web services — closes the "ASP loophole" in GPL.  
**Key terms:** Network use counts as distribution. Source must be available to users.  
**Used by:** MongoDB (older), Nextcloud, Mastodon.  
**Copyleft:** Strong + network. **Patent grant:** Yes.

### MPL-2.0
**Best for:** Projects wanting file-level copyleft (not project-wide).  
**Key terms:** Modified MPL files must remain MPL. Can be combined with proprietary.  
**Used by:** Firefox, Thunderbird.  
**Copyleft:** Weak (file boundary).

---

## Business Source License

### BSL-1.1
**Best for:** Companies wanting a "delayed open source" model.  
**Key terms:** Proprietary for N years (usually 4), then converts to open source license.  
**Used by:** MariaDB, HashiCorp (before relicensing controversy).  
**Note:** Not OSI-approved open source.

### SSPL-1.0
**Best for:** Database/infrastructure vendors protecting against cloud provider exploitation.  
**Key terms:** If you offer the software as a service, you must open source your entire service stack.  
**Used by:** MongoDB (current), Elasticsearch (before fork).  
**Note:** Not OSI-approved. Controversial in cloud deployments.

---

## Creative Commons (for content and data, not software)

### CC0-1.0
**Best for:** Datasets, research outputs, documentation — maximum reuse.

### CC-BY-4.0
**Best for:** Research, datasets — attribution required.

### CC-BY-SA-4.0
**Best for:** Wikipedia-style content — share-alike required.

---

## AI-specific licenses

### RAIL (Responsible AI License)
**Best for:** ML models where you want to restrict harmful use cases.  
**Key terms:** Permissive use with explicit prohibited use list (weapons, surveillance, discrimination, etc.).  
**Used by:** BigScience BLOOM, some Stability AI models.  
**Note:** Not OSI-approved. Growing adoption in AI/ML community.

---

## Compatibility matrix (simplified)

| Your license | Can use MIT? | Can use Apache 2.0? | Can use GPL-3.0? | Can use AGPL-3.0? |
|---|:---:|:---:|:---:|:---:|
| MIT | ✅ | ✅ | ⚠️ | ⚠️ |
| Apache 2.0 | ✅ | ✅ | ⚠️ | ⚠️ |
| GPL-3.0 | ✅ | ✅ | ✅ | ⚠️ |
| AGPL-3.0 | ✅ | ✅ | ✅ | ✅ |
| Proprietary | ✅ | ✅ | ❌ | ❌ |

⚠️ = Entire project may need to adopt copyleft license

---

*This guide is for informational purposes only. For legal advice specific to your project, consult a qualified attorney. LicenseAgent and VibeCodingChile SpA are not law firms.*
