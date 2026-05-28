---
title: Asset Management
layout: default
parent: Engine Room
nav_order: 9
---

# Asset Management

Asset Management defines how files, drafts, exports, and system outputs are stored, organized, versioned, and retrieved within the Revona orchestration system.  
A clean asset system ensures scalability, prevents duplication, and supports multi-agent AI collaboration.

## Purpose of Asset Management
The asset system exists to:
- maintain a clear, predictable file structure  
- ensure assets are easy to find and reference  
- support versioning and archival  
- prevent drift and duplication  
- enable AI agents to reliably access context and materials  

Assets are the raw materials of the studio — they must be managed intentionally.

## Asset Categories
Assets fall into several categories:

- **Creative Assets** — drafts, scripts, outlines, storyboards  
- **Media Assets** — audio, video, thumbnails, images  
- **Documentation Assets** — notes, logs, research, references  
- **System Assets** — templates, workflow outputs, system artifacts  
- **Portfolio Assets** — case studies, screenshots, exports  

Each category has its own folder and naming conventions.

## Folder Structure
All assets follow a predictable folder hierarchy:
/assets
/creative
/media
/documentation
/systems
/portfolio
/archive

Each subfolder may contain additional structure depending on the asset type.

## Naming Standards
All assets use:
- lowercase  
- hyphens for spaces  
- descriptive, stable names  
- version tags when relevant  

Examples:
rainstorm-script-v1.md
thunderstorm-thumbnail-v2.png
case-study-screenshot-01.png
workflow-output-youtube-v3.json

## Versioning Rules
Assets are versioned when:
- content changes meaningfully  
- a new iteration is created  
- a workflow or system produces an updated output  

Version tags follow this pattern:
v1, v2, v3...

Old versions are moved to `/archive`.

## Retrieval Standards
When referencing an asset:
- link directly to the file  
- include version number  
- include context for usage  

Example:
See: /assets/media/thunderstorm-thumbnail-v2.png

## Asset Lifecycle
Assets follow a clear lifecycle:

1. **Creation** — produced by a workflow, system, or manual work  
2. **Usage** — referenced in workflows, playbooks, or portfolio  
3. **Versioning** — updated when changes occur  
4. **Archival** — moved to `/archive` when superseded  
5. **Retirement** — removed only when explicitly deprecated  

## AI Collaboration Considerations
AI agents must always receive:
- the correct asset version  
- relevant context  
- clear instructions for usage  
- links to related assets  

AI agents never guess — they operate on explicit references.

## Living Asset System
The asset management system evolves as the studio grows.  
New asset types, categories, or workflows may require updates to this page.

This page ensures that the studio remains organized, scalable, and future-proof.
