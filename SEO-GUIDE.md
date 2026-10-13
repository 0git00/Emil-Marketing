# SEO Guide — https://0git00.github.io/Emil-Marketing/

## 1. Files upload karo (GitHub repo ke root me)
index.html, 404.html, robots.txt, sitemap.xml, site.webmanifest, assets/ (poora folder)

## 2. Google Search Console (sabse zaroori)
1. https://search.google.com/search-console -> Add property -> **URL prefix** -> `https://0git00.github.io/Emil-Marketing/`
2. Verify: "HTML tag" method -> jo `<meta name="google-site-verification" ...>` mile use index.html ke `<head>` me paste karo -> push -> Verify.
3. Sitemaps -> `sitemap.xml` submit karo.
4. URL Inspection -> apna URL daalo -> "Request indexing".

## 3. robots.txt ka note
Google sirf host ke root ka robots.txt padhta hai (`0git00.github.io/robots.txt`), project folder wala nahi. Isliye indexing ke liye Search Console + sitemap submit karna kafi hai. Agar chaho to `0git00.github.io` naam ki repo bana kar wahan robots.txt rakh sakte ho.

## 4. Ranking ke liye (first page)
- Custom domain lo (e.g. muhammadharisafzal.com) — GitHub Pages ke subpath se rank karna mushkil hota hai. Domain lagao to canonical/sitemap/OG URLs update karo.
- Backlinks: LinkedIn, Fiverr, Instagram bio me website link; Behance/Medium/GitHub profile me link.
- Google Business/profile pages me same naam "Email Marketing Expirt" use karo.
- Content: har service ke liye alag section/page, case studies, blog (e.g. "Klaviyo flows guide").
- Speed: images WebP me compress karo; page abhi base64 images ki wajah se ~575KB hai.
- Index hone me 1-4 hafte lag sakte hain.
