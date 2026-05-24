=== News Aggregator ===
Contributors: webzlo
Tags: rss, rss feed, news aggregator, news portal, rss importer, feed reader, auto post, news plugin, cnn, bbc, reuters
Requires at least: 6.0
Tested up to: 6.8
Requires PHP: 7.4
Stable tag: 1.8.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Automatically fetch, store, and publish RSS/news content into WordPress with category mapping, Elementor widgets, view tracking, layouts, cron automation, and news portal features.

== Description ==

News Aggregator is a powerful WordPress news portal plugin that automatically fetches RSS feeds and category-based news sources, stores content in your database, and creates real WordPress posts.

Perfect for building:

- News websites
- Magazine portals
- RSS aggregators
- Blog networks
- Breaking news portals
- Multi-source content portals

Instead of displaying temporary RSS feeds only, this plugin saves news permanently into WordPress and automatically updates new items using WP-Cron.

= Main Features =

✔ RSS Feed Importer  
✔ Category URL Fallback Fetcher  
✔ Automatic WordPress Post Creation  
✔ Auto Featured Image Detection  
✔ Duplicate Protection  
✔ WP-Cron Auto Fetching  
✔ Elementor Widget Support  
✔ News Grid & List Layouts  
✔ Sidebar News Widgets  
✔ Category Filtering  
✔ Total Views Tracking  
✔ Top Posts Dashboard  
✔ Responsive Mobile Layouts  
✔ News Portal Design  
✔ Auto Category Mapping  
✔ Source Tracking  
✔ News Storage in Database  
✔ Manual Fetch Now Button  
✔ Cron Repair Tool  
✔ Shortcode Support

= Admin Dashboard =

The plugin includes a complete admin panel:

- Dashboard
- Sources
- Add New Source
- News Items
- Settings
- Logs
- Help Page

Manage all RSS sources and news feeds from one clean interface.

= Source Types =

Supports:

1. RSS Feed Source
2. Category URL Fallback

Add:

- Source Name
- Website URL
- RSS URL
- Category
- Update Frequency
- Max Items
- Status

= Auto Post Creation =

Every fetched news item can automatically create a real WordPress post.

Includes:

- Post Title
- Excerpt
- Content
- Featured Image
- Category Assignment
- Source Meta
- Original URL Meta

= Duplicate Protection =

Duplicate news prevention using:

- GUID
- Original URL Hash
- Link Comparison

No duplicate news posts.

= Featured Image Detection Priority =

1. media:content
2. media:thumbnail
3. enclosure image
4. image inside description
5. og:image
6. fallback image

= Excerpt Detection Priority =

1. RSS description
2. content:encoded
3. meta description
4. first paragraph
5. fallback text

= Title Detection Priority =

1. RSS title
2. og:title
3. page title
4. article h1

= Elementor Widgets =

Includes Elementor widget support.

Available layouts:

- Grid Layout
- List Layout
- Featured Layout
- 1 Large + 3 Small Cards

Widget controls:

- Columns
- Category Filter
- Source Filter
- Number of Posts
- Styling Controls
- Typography
- Colors
- Card Design

= Shortcodes =

Display news anywhere.

Basic:

[news_portal]

Source:

[news_portal source="CNN"]

Category:

[news_portal category="Politics"]

Limit:

[news_portal limit="12"]

Layout:

[news_portal layout="grid"]

Sidebar list:

[news_portal_sidebar limit="10"]

= Settings =

Customize:

- Auto Publish
- Draft/Publish Status
- Default Items Per Source
- Cache Duration
- Open Links New Tab
- Nofollow External Links
- Fallback Image
- Show/Hide Source
- Show/Hide Date
- Show/Hide Excerpt
- Auto Delete Old News
- Max Stored Items

= Analytics =

Track:

- Total Views
- Top Posts
- Most Viewed Articles
- Category-Based Posts

= Cron Automation =

Automatically fetches new items.

Supports:

- Hourly
- Twice Daily
- Daily

Includes:

- Fetch Now Button
- Repair Cron Runner
- Last Run Time
- Next Scheduled Run
- Last Fetch Status

= Security =

Built with WordPress coding standards.

Includes:

- Nonces
- Capability Checks
- Sanitization
- Escaping
- Prepared SQL Queries
- Safe Remote Requests
- No Eval
- No Unsafe Code

== Installation ==

1. Upload the plugin zip file
2. Activate the plugin
3. Go to News Aggregator
4. Add RSS feed sources
5. Configure settings
6. Start fetching news

== Frequently Asked Questions ==

= Does this create WordPress posts? =

Yes. The plugin can automatically create WordPress posts from fetched news items.

= Does it support Elementor? =

Yes. Includes Elementor widgets and style controls.

= Can I fetch RSS feeds? =

Yes.

= Can I use category URLs instead of RSS? =

Yes.

= Does it prevent duplicates? =

Yes. Duplicate detection uses URL hash, GUID, and link comparison.

= Can I show news in Elementor? =

Yes. Use Elementor widgets or shortcodes.

= Is it mobile responsive? =

Yes.

== Screenshots ==

1. Dashboard
2. Sources
3. Add Source
4. News Grid
5. Elementor Widget
6. Top Posts Dashboard
7. Settings
8. Logs

== Changelog ==

= 1.8.0 =
* Added title cleanup fixes
* Improved CNN parser
* Added Elementor layouts
* Added top posts dashboard
* Added total views
* Added category filtering
* Improved cron runner
* Fixed duplicate handling
* Improved frontend layouts

== Upgrade Notice ==

= 1.8.0 =
Recommended update for improved title parsing and Elementor layouts.
