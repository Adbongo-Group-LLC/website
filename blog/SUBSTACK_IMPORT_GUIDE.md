# Substack Import Guide

## 📚 Legacy Blog Archive (2010-2012)

This folder contains 23 blog posts salvaged from the old Adbongo WordPress site, cleaned up and ready for publishing to Substack.

### ✅ What's Been Done

1. **Emails Updated**: All references to `jbush@adbongo.com` updated to `baba@adbongo.io`
2. **Links Cleaned**: Removed broken tracking pixels and dead WiseStamp links
3. **Format Optimized**: Converted to Substack-friendly markdown format
4. **Metadata Preserved**: Each post includes title and original publication date

### 📁 Folder Structure

```
blog/
├── README.md                  # Index of all posts
├── SUBSTACK_IMPORT_GUIDE.md   # This file
├── posts/                     # Cleaned markdown files
└── substack-ready/            # Identical copy, ready for Substack import
```

### 📝 How to Import to Substack

#### Option 1: Manual Import (Recommended for Legacy Archives)

1. Log into your Substack dashboard
2. For each post in `substack-ready/`:
   - Click "New Post"
   - Copy the title from the frontmatter
   - Copy the body content (everything after `---`)
   - Paste into Substack editor
   - Set publication date to match the original date
   - Add tag: "Legacy Archive" or "From the Archives"
   - Mark as "Legacy content from 2010-2012"
   - Publish or save as draft

#### Option 2: Bulk Import via API

If you have a lot of posts and want to automate:

```bash
# Example using Substack's API (if available)
# Note: Check Substack docs for current API access
```

#### Option 3: Email Import

Substack allows importing via email:
1. Set up email posting in Substack settings
2. Send each post as an email to your Substack posting address
3. Use the original date in the subject line

### 📋 Post Checklist

When importing each post:
- [ ] Title matches original
- [ ] Date set to original publication date (2010-2012)
- [ ] Add "Legacy Archive" tag
- [ ] Add intro note: "Originally published on [date] on the Adbongo WordPress blog"
- [ ] Check that images load (some may be on WordPress.com CDN)
- [ ] Review external links still work
- [ ] Set appropriate SEO settings

### 📊 Content Overview

**23 Posts covering:**
- Company origin story & branding
- Sustainable business consulting
- Organic business development
- Permaculture principles in business
- Social enterprise vision
- "New economy" philosophy
- Services offered 2010-2012

**Time period:** February 2010 - October 2012

**Primary themes:**
- Sustainability & regeneration
- Alternative business models
- Community & social enterprise
- Marketing & branding philosophy

### 🔗 External Links Note

Most image links point to `adbongo.files.wordpress.com` - these should still work as WordPress.com keeps legacy files. If any images are broken, you may want to:

1. Download and re-host images locally
2. Upload to Substack's media library
3. Or remove broken image references

### 💡 Publishing Strategy Suggestions

**As Legacy Archive:**
- Publish with "[From the Archives]" prefix in title
- Add dates to titles: "What the *#$% does Adbongo mean? (2010)"
- Create a "Legacy Content" section on Substack
- Consider publishing weekly as "Throwback Thursday" content

**As Refreshed Content:**
- Update examples and references to 2026
- Add editorial notes about what's changed
- Compare 2010 vision to 2026 reality
- Use as launching point for new commentary

### 📧 Contact in Posts

All email references updated to: **baba@adbongo.io**

### 🗄️ Archive in Git

The original, cleaned markdown files remain in this repo at:
- `blog/posts/` - Main archive
- `blog/README.md` - Searchable index

This serves as your canonical archive regardless of where posts are published externally.

---

*Last updated: 2026-08-24*
*Extracted from: adbongogroupllcsocialenterprise.wordpress.2022-11-19.000.xml*
