📅 Date Completed:
April 30, 2025

🔧 1. GitHub Repository Setup
Created a new public GitHub repository:
land-conservation-association
Added a basic index.html file with placeholder “Coming Soon” content.
Committed the file directly to the main branch.

🛠️ 2. GitHub Pages Configuration
Went to Settings > Pages
Set Source to:
Branch: main
Folder: / (root)
Saved changes
GitHub published the site at: https://ianschelly.github.io/land-conservation-association/

🌐 3. Custom Domain Configuration (Namecheap → GitHub)
DNS Setup:
In Namecheap > Domain List > Manage > Advanced DNS, created:
A CNAME Record:
Host: www
Value: ianschelly.github.io
TTL: Automatic
A URL Redirect Record (to forward root domain to www):
Host: @
Value: https://www.landconservationassociation.org
Redirect Type: 301 (Permanent)
GitHub Pages Custom Domain:
In GitHub Settings > Pages, entered:
www.landconservationassociation.org
GitHub created a CNAME file automatically in the repo.

🔐 4. HTTPS Configuration
GitHub showed “DNS Check in Progress” for ~45 minutes.
Once DNS verified:
TLS certificate was automatically provisioned
HTTPS was enabled for the site
✅ Final Result:
https://www.landconservationassociation.org
Now live with secure connection.

💬 5. SEO Basics Added
Added <title>Land Conservation Association | Sustainable Land Use and <meta name="description">"The Land Conservation Association promotes sustainable land use in commodity production landscapes worldwide through actionable science and policy." tags to index.html for basic search engine optimization. 
