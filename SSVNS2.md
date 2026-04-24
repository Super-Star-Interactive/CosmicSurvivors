# SSVNS 2 — Super Star Version Numbering System 2

Super Star Interactive uses **SSVNS 2**, a clear and powerful versioning structure designed to track development progress and release stability.

## What is SSVNS 2?
SSVNS 2 stands for **Super Star Version Numbering System 2**, created by **MitchStar**.  
It is a flexible, developer‑friendly versioning system that expands on the classic **MAJOR.MINOR.PATCH** format with advanced pre‑release stages.

If you want to use SSVNS 2 for your own games, feel free to copy this document and replace the company name at the top.  
Please **do not edit the copyright notice** at the bottom.

## Format
Standard versions follow:

**MAJOR.MINOR.PATCH**  
or  
**MAJOR.MINOR.PATCH-PRE-RELEASE**

Examples:
- `1.3.2`
- `1.4.0-beta1`

## MAJOR
Increases when:
- Significant updates are released  
- Core gameplay systems change  
- Old versions become incompatible  
- Large features or systems are added  
- New platforms or devices are supported  

## MINOR
Increases when:
- New features are added without breaking compatibility  
- Visual improvements or content updates are released  
- Gameplay tuning or new options are introduced  

## PATCH
Increases when:
- Small fixes are made  
- Minor improvements are added  
- Bugs are resolved without structural changes  

## Pre‑Release Tags
Pre‑release tags indicate development stages:

- **`pre-alpha`** — core systems are being implemented (no MAJOR.MINOR.PATCH)  
- **`alpha`** — early development; uses its own `ALPHA-MAJOR.MINOR.PATCH`  
- **`pre-beta`** — preparation for beta  
- **`beta`** — feature‑complete but still being polished  
- **`pre-release`** — complete and mostly polished  
- **`rc`** — release candidate; final polishing stage  

Examples:
- `pre-alpha1`  
- `alpha-1.0.0`  
- `alpha-1.0.0-beta1`  
- `2.4.0-pre-beta`  
- `1.0.0-beta1`  
- `2.5.0-pre-release`  
- `1.2.0-rc1`  

## Example Workflow

### 1. Development begins
`pre-alpha1`

### 2. Entering the alpha phase
Alpha uses its own numbering:  
`alpha-1.0.0`

Beta versions of alpha builds are possible:  
`alpha-1.0.0-beta1`

### 3. Entering pre-beta and beta
`1.0.0-pre-beta`  
`1.0.0-beta1`

0.x.x versions are allowed **only with pre-release tags**:  
`0.1.0-beta4`

### 4. Pre-release stage
Features are complete but not fully polished:  
`1.0.0-pre-release`

Pre-release versions cannot be used with 0.x.x.

### 5. Release Candidate
Final polishing stage:  
`1.0.0-rc1`

RCs cannot be used with 0.x.x.

## Notes
- All GitHub Releases must follow this format.  
- Internal unbuilt versions may use additional tags like `dev`.  
- Version numbers must always increase — never roll back.  
- This system applies to all games produced by Super Star Interactive.

---

© Super Star Interactive, 2026. All rights reserved.  
All rights of SSVNS 2 belong to Super Star Interactive.  
The MAJOR.MINOR.PATCH concept is not developed by us; SSVNS is a template for how to use version numbering.
