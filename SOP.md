# Automated Local Lead Gen Website Builder SOP

## Objective
Use a structured Google Sheet as the command center to automatically generate, deploy, connect, verify, optimize, and iteratively improve fully built local lead generation websites at scale.

## The System Must:
1. Read one row
2. Build a complete multi-page site
3. Deploy to GitHub Pages
4. Attach and validate the domain
5. Run SEO validation checklist
6. Reflect and log improvement insights
7. Move to the next row
8. Repeat until all rows are complete

The goal is continuous improvement in both quality and build speed, without sacrificing page count, SEO strength, or uniqueness.

## Google Sheet Structure

**Required columns:**
- Niche
- Domain Name
- City
- State
- Phone Number
- Notes (AI-generated post-build reflection and improvement log)

Each row represents one fully independent business website.

## Token Efficiency Strategy

**Template-Based Generation:**
- Create a base HTML template with placeholders: {{niche}}, {{city}}, {{state}}, {{phone}}, {{domain}}
- Use find/replace for variables (minimal tokens)
- Add unique content variations by:
  - Changing service descriptions slightly per niche
  - Varying testimonials/staff names
  - Adjusting brand tone (friendly vs professional vs urgent)
  - Different headline variations
  - Unique value propositions per site

This keeps sites unique while being token-efficient.

## Execution Flow (Per Row)

### 1. Read Input Data
- Extract: Niche (primary service), Domain, Target City, State, Phone Number
- Treat this as a standalone business build
- Each site must look like it is a completely separate company

### 2. Pre-Build Setup
- Create GitHub repo BEFORE generating content
- Prepare token in advance
- Set up repo with GitHub Pages enabled
- Select appropriate Unsplash images for the niche

### 3. Website Creation (Full Multi-Page Build)

**Core Pages:**

**Home Page**
- Primary H1: [Niche] in [City], [State]
- Hero section with background image (from Unsplash based on niche)
- Target keyword must: Be the full H1, Be the first words in the meta title
- Strong conversion structure with clear CTAs
- Include provided phone number prominently
- Link to all major internal pages
- 1800-2500 words minimum
- Add schema.org LocalBusiness markup

**ALL pages should have:**
- Hero section with image
- Consistent header/navigation
- LocalBusiness schema

**10 Service Pages (Dropdown in Header)**
Each niche must have 10 distinct service pages.

**Requirements:**
- Hero section with relevant image on EACH service page
- Unique H1 per service page: [Specific Service] in [City], [State]
- 800-1200 words minimum per service page
- Internal linking structure consistent
- Dropdown navigation from header

**Residential Page**
- Hero section with residential-focused image
- Focused on residential service offering
- H1 must still contain main target structure

**Commercial Page**
- Hero section with commercial-focused image
- Focused on business/industrial customers

**About Us Page**
- Hero section
- Generic but location-specific
- Discuss commitment to service in that city

**Locations Dropdown (6 Neighboring Cities)**
- Hero section for each location page
- 300-500 words minimum

**Blog Section**
- Hero section on blog index and each post
- Minimum 2 blog posts

### 4. Technical Requirements

**URL Structure:**
- Use clean URLs: /ant-control/ not ant-control.html
- Configure GitHub Pages redirect rules

**SEO Files (MUST HAVE):**
- robots.txt - Allow all, sitemap reference
- sitemap.xml - List all pages with priorities
- Meta descriptions on EVERY page (150-160 characters)
- Open Graph tags for social sharing
- Schema.org LocalBusiness JSON-LD markup

**Images:**
- Use Unsplash images appropriate to niche
- Hero image on EVERY page type
- Descriptive alt tags

### 5. Deploy to GitHub Pages
- Push code to repo
- Enable GitHub Pages from Settings
- Get live URL

### 6. Domain Connection (Optional)
- Add custom domain in GitHub Settings
- Configure CNAME record

### 7. SEO Validation Checklist
- [ ] All pages load without errors
- [ ] H1 tags present and correct on each page
- [ ] Meta descriptions on every page
- [ ] Internal links working
- [ ] Mobile responsive
- [ ] Page speed reasonable
- [ ] robots.txt present
- [ ] sitemap.xml present
- [ ] Schema markup validated
- [ ] Hero images on all page types

### 8. Reflection & Log (CRITICAL)
After each build, reflect on:
1. Should we make any changes to the SOP to make things more efficient without sacrificing quality?
2. Is there a way to do this while using less AI tokens?
3. What small system improvements could make the next site faster?
4. What internal linking model refinements could be standardized?
5. What template refinements would reduce friction?
6. How can we make this more optimized for search engines?
7. Is there opportunities for conversion rate optimization?
8. How was the design - is there a better look we can do?

Write findings to the Notes column in the Google Sheet.

## Known Issues / Lessons Learned

- URLs ending in .html are not ideal - use clean URL structure
- Pages need 1800-2500 words for home, 800-1200 for service pages (minimum)
- Generic design needs improvement - use better templates
- Add robots.txt and sitemap.xml to every build
- Design needs: better hero on ALL pages, real photos, more visual hierarchy
- Add more CTAs throughout pages for conversion
- Consider trust badges and testimonials section
- Each site needs unique content variations, not exact duplicates
- Hero sections required on ALL pages, not just homepage
