ShopSync visual rebuild

Upload index.html to the root of your GitHub Pages repository, replacing the existing file.

Features: email/password auth, lists, add items, mobile barcode camera (where browser supports BarcodeDetector), manual barcode fallback, shelf-price entry, realtime substitution requests and approvals.

Limitations: no verified ASDA catalogue; product names and shelf prices are manually confirmed. For barcode matches, the user selects a list item and enters its exact name. Product photos require a URL. Shopper linking uses Supabase account UUID from Profile.

Requires existing ShopSync Supabase tables and migration for substitution_requests.
