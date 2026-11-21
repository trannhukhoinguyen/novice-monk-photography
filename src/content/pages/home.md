---
pageTitle: "Alex Mercer — Principal Cloud & Platform Architect"
description: "Alex Mercer — Principal Cloud & Platform Architect. Multi-region AWS infrastructure, Terraform automation, Astro static architecture, and photography."
# Powers the 2-column classic hero (`hero.style: 'classic'` in `src/theme.config.ts`)
# and serves as fallback copy when `hero.style: 'metrics'` omits optional fields.
intro:
  eyebrow: "Vạn pháp quy nhất, nhất quy hà xứ?"
  heading: "Sa di chăm chỉ - Sa di thôi nghĩ"
  leftColumn: "Chỉ vật truyền tâm, nhân bất hội xứ"
  rightColumn: "Huyền nhai tán thủ, tự khẳng thừa đương, tuyệt hậu tái tô, khi quân bất đắc"
  ctaLabel: "Explore background & living CV"
  ctaHref: "/about/"
setupGuide:
  # Set `enabled: false` (or remove this block) once you finish customizing your site to hide the 3-step setup banner on `/`
  enabled: true
  eyebrow: "Start Here · 3-Part Setup & Deployment Flow"
  heading: "Customize & Deploy This Theme in 3 Steps"
  subtitle: "Everything is data-driven. Start with Part 1 to configure your identity and content, then choose between zero-config static hosting (Part 3) or the optional multi-region AWS Terraform stack (Part 2)."
  steps:
    - step: "Step 1"
      badge: "Required · ~10 min"
      title: "Part 1 — Customize Identity, Theme & Content"
      description: "Configure your profile in src/site.config.ts, UI mechanics & Formspree/Umami in src/theme.config.ts, page narratives in src/content/pages/, and career/acronym datasets in src/data/."
      href: "/blog/2026-11-03-part-1-customizing-this-astro-theme/"
      ctaLabel: "Read Part 1 Guide"
    - step: "Step 2"
      badge: "Optional · AWS Stack"
      title: "Part 2 — Multi-Region AWS S3 MRAP + CloudFront"
      description: "Provision globally replicated S3 buckets, a Multi-Region Access Point (MRAP), native CloudFront SigV4a OAC, ACM TLS, and Route 53 DNS with Terraform 1.10+ (GitLab CI, GitHub Actions, or CLI)."
      href: "/blog/2026-11-03-part-2-provisioning-aws-mrap-cloudfront-terraform-gitlab-ci/"
      ctaLabel: "Read Part 2 Guide"
    - step: "Step 3"
      badge: "CI/CD & Static Hosts"
      title: "Part 3 — CI/CD Dry-Run Pipelines & Static Hosting"
      description: "Deploy ./dist/ in 60 seconds to Vercel, Netlify, or Cloudflare Pages—or learn how .gitlab-ci.yml and .github/workflows/deploy.yml switch from 5s Dry-Run Mode to ETag delta sync."
      href: "/blog/2026-11-03-part-3-ci-cd-pipelines-dry-run-mode-and-static-hosting/"
      ctaLabel: "Read Part 3 Guide"
blogSection:
  heading: "From the Blog — Setup Guides & Architecture"
  subtitle: "Complete 3-part setup & deployment guides, Markdown kitchen-sink component showcase, and edge architecture notes."
  linkLabel: "View all articles"
  footerLinkLabel: "View all blog posts"
photosSection:
  heading: ""
  subtitle: ""
  linkLabel: "Browse full gallery"
  footerLinkLabel: "Browse full gallery"
logSection:
  heading: "From the Log"
  subtitle: "Chronological stream of operational field notes, release changelogs, and gallery additions."
  linkLabel: "Browse the full log stream"
  footerLinkLabel: "View all log entries"
---
