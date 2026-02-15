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

## Execution Flow (Per Row)

### 1. Read Input Data
- Extract: Niche (primary service), Domain, Target City, State, Phone Number
- Treat this as a standalone business build
- Each site must look like it is a completely separate company

### 2. Pre-Build Setup
- Create GitHub repo BEFORE generating content (saves time)
- Prepare token in advance
- Set up repo with GitHub Pages enabled

### 3. Website Creation (Full Multi-Page Build)

**Core Pages:**

**Home Page**
- Primary H1: [Niche] in [City], [State]
- Target keyword must: Be the full H1, Be the first words in the meta title
- Strong conversion structure with clear CTAs
- Include provided phone number prominently
- Link to all major internal pages
- 1800-2500 words minimum
- Add schema.org LocalBusiness markup

**10 Service Pages (Dropdown in Header)**
Each niche must have 10 distinct service pages.

Example for Pest Control:
- Ant Control
- Termite Control
- Rodent Control
- Bed Bug Treatment
- Cockroach Control
- Spider Control
- Flea Control
- Wasp & Bee Control
- Mosquito Control
- Wildlife Removal

**Requirements:**
- Unique H1 per service page: [Specific Service] in [City], [State]
- 800-1200 words minimum per service page
- Internal linking structure consistent
- Dropdown navigation from header

**Residential Page**
- Focused on residential service offering
- H1 must still contain main target structure
- Unique content vs commercial page

**Commercial Page**
- Focused on business/industrial customers
- Distinct tone and positioning
- Unique structure and content

**About Us Page**
- Generic but location-specific
- Discuss commitment to service in that city
- No references to other sites or broader networks
- Must read like a local independent company

**Locations Dropdown (6 Neighboring Cities)**
Create 6 nearby city pages.

Each page must:
- Have unique content (300-500 words minimum)
- Target that city name
- Still reinforce main service authority
- Include variation of main keyword in structured way
- These pages should feel geographically relevant and localized

**Blog Section**
Minimum 2 blog posts per site:
1. "Best 7 [Niche] Companies in [City]"
   - Our company listed as #1
   - Other 6 competitors described neutrally with less emphasis
   - Structured and SEO optimized
2. "How Much Does [Niche] Cost in [City]?"
   - Informational but conversion-friendly
3. (Optional) "How Often Should You Schedule [Niche] in [City]?"

### 4. Technical Requirements

**URL Structure:**
- Use clean URLs: /ant-control/ not ant-control.html
- Configure GitHub Pages with proper redirect rules

**SEO Files (MUST HAVE):**
- robots.txt - Allow all, sitemap reference
- sitemap.xml - List all pages with priorities
- meta descriptions on EVERY page (150-160 characters)
- Open Graph tags for social sharing
- Schema.org LocalBusiness JSON-LD markup

**Images:**
- Add placeholder images for hero sections
- Use descriptive alt tags

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
- Design needs: better hero, real photos, more visual hierarchy
- Add more CTAs throughout pages for conversion
- Consider trust badges and testimonials section
