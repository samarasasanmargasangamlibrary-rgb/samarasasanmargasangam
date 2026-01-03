# Samarasa Sanmarga Sangam Library & Charitable Trust
Official website for the first library of Thiruvannamalai & Vellore districts, established in 1914.

## ✍️ Project Author
**Designed, Developed, and Maintained by:** Ganeshram Madhavan

## 🏗 Website Architecture
This website is built using a modern, high-performance static architecture to ensure 100% uptime at zero cost to the Trust.

[Image of GitHub Pages architecture with Cloudflare DNS proxy]

1. **Domain Registrar:** HostingRaja (Primary domain holder)
2. **DNS & Security Layer:** Cloudflare (SSL & DDoS Protection)
3. **Hosting Provider:** GitHub Pages (File storage and delivery)
4. **Frontend:** HTML5 / Bootstrap 5.3 (Mobile Responsive)

## 📁 File Structure
- `index.html`: Home page (History, Hero Section, Quick Stats)
- `about.html`: Trust Details (Founder History, Trustee roles)
- `collection.html`: Library Catalog (Book categories)
- `gallery.html`: Photo Gallery
- `events.html`: Announcements & Digitization Updates
- `cover.png`: Main hero image of the library
- `CNAME`: Domain routing configuration

## 🔑 Administrative Access & Renewals
*To ensure the website stays online, the following accounts must be maintained.*

### 1. Domain Renewal (HostingRaja)
- **Domain:** `samarasasanmargasangam.org.in`
- **Username:** samarasasanmargasangamlibrary@gmail.com
- **Renewal Task:** Must be renewed annually to prevent loss of the domain name.

### 2. DNS Management (Cloudflare)
- **Account Username:** samarasasanmargasangamlibrary@gmail.com
- **Purpose:** Manages the link between the domain and the website files.

### 3. Website Files (GitHub)
- **GitHub Username:** samarasasanmargasangamlibrary@gmail.com
- **Repository:** samarasasanmargasangam
- **Status:** Hosting is free; accounts should be kept active for updates.

## ⚙️ DNS Configuration Reference
The following records are configured in Cloudflare to route traffic to GitHub:

| Type | Name | Value | Proxy Status |
| :--- | :--- | :--- | :--- |
| A | @ | 185.199.108.153 | Proxied |
| A | @ | 185.199.109.153 | Proxied |
| A | @ | 185.199.110.153 | Proxied |
| A | @ | 185.199.111.153 | Proxied |
| CNAME | www | samarasasanmargasangam.org.in | Proxied |

## Cloudflare Nameservers
- barbara.ns.cloudflare.com
- eugene.ns.cloudflare.com
