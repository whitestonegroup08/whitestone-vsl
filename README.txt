WHITE STONE GROUP - FINAL FULL PACKAGE

Main landing page: dist/index.html

The website has ONE copy in dist. Original assets from earlier designs are included for completeness; unused assets are not loaded by the current page. content contains editable policy sources and scripts contains the policy generator, not another website copy.

All WhiteStone domain and email references use whitestonegroup.in and support@whitestonegroup.in.

GITHUB: Extract ZIP, open whitestone-final-full, then upload its contents (dist, content, scripts, README.txt) to your existing repository root. Do not upload an extra enclosing folder. Commit changes.

EXISTING DIGITALOCEAN SETTINGS: Source directory dist; Output directory Auto; Build command empty.

EDIT: dist/config.js for text/links. Keep index.html fallback text aligned. Policies: edit content files and run python3 scripts/build-policies.py.

LOCAL PREVIEW: python3 -m http.server 8000 --directory dist
Then open http://localhost:8000.

Wistia streams the video; video bytes are not bundled. Razorpay booking links are preserved. Your DigitalOcean website updates after GitHub upload and deployment.
