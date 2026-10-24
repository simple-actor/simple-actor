<picture><source media="(prefers-color-scheme: dark)" srcset="header-dark.png"><img src="header-light.png" alt="Simple Actor: web scrapers I build, run and fix in production" width="100%"></picture>

I build web scrapers, publish them on Apify, and keep them running when the sites change underneath them. Each one reads a site the way it serves itself to a logged-out visitor and returns one clean row per thing you asked for. When it can't read something, the row says so and says why, rather than handing you an empty file.

The repos here are working examples: the problem, a Node and a Python script, and real output from a real run. The write-ups are on **[simple-actor.github.io](https://simple-actor.github.io)**.

## Latest write-up

<a href="https://simple-actor.github.io/email-every-dentist-miami-google-maps/"><img src="posts/email-every-dentist-miami-google-maps.png" alt="Every dentist in Miami, with an email address" width="100%"></a>

**[How to get the email of every dentist in Miami from Google Maps](https://simple-actor.github.io/email-every-dentist-miami-google-maps/)**: 182 practices, 81 email addresses, 31 cents, and where it falls short. Code: [google-maps-email-scraper](https://github.com/simple-actor/google-maps-email-scraper)

## Use them without writing code

<p>
<a href="https://github.com/simple-actor/n8n-claude-lead-generation/tree/main/n8n"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/n8n-workflows-dark.png"><img src="cards/n8n-workflows-light.png" alt="n8n workflows: Four tested workflows: Maps leads to Sheets, competitor ads digest, job alerts, CRM enrichment" width="400"></picture></a>
<a href="https://github.com/simple-actor/n8n-claude-lead-generation/tree/main/claude"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/claude-guides-dark.png"><img src="cards/claude-guides-light.png" alt="Claude guides: Ask Claude for leads in plain words; it runs the scrapers through Apify&#x27;s MCP server" width="400"></picture></a>
</p>

## The scrapers

### Leads and local businesses

<p>
<a href="https://apify.com/simple.actor/google-maps-leads"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/google-maps-leads-dark.png"><img src="cards/google-maps-leads-light.png" alt="Google Maps Leads: Every business Maps lists for a search, plus the emails, phones and socials on its website" width="400"></picture></a>
<a href="https://apify.com/simple.actor/google-maps"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/google-maps-dark.png"><img src="cards/google-maps-light.png" alt="Google Maps: Places with rating, reviews, address, phone, website, hours and Place ID" width="400"></picture></a>
<a href="https://apify.com/simple.actor/website-contacts"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/website-contacts-dark.png"><img src="cards/website-contacts-light.png" alt="Website Contacts: Emails, phones, socials, address and contact form from a list of websites" width="400"></picture></a>
<a href="https://apify.com/simple.actor/business-profile"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/business-profile-dark.png"><img src="cards/business-profile-light.png" alt="Business Profile: One business from a name and a town: its Google record, website contacts and socials" width="400"></picture></a>
</p>

### Search and ads

<p>
<a href="https://apify.com/simple.actor/google-search"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/google-search-dark.png"><img src="cards/google-search-light.png" alt="Google Search: Web results, or Google News stories with links to the publisher" width="400"></picture></a>
<a href="https://apify.com/simple.actor/google-images"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/google-images-dark.png"><img src="cards/google-images-light.png" alt="Google Images: Full-size image URLs, sizes and source pages for any search" width="400"></picture></a>
<a href="https://apify.com/simple.actor/google-short-videos"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/google-short-videos-dark.png"><img src="cards/google-short-videos-light.png" alt="Google Short Videos: The Short videos tab across YouTube, TikTok, Instagram and more" width="400"></picture></a>
<a href="https://apify.com/simple.actor/google-ads-transparency"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/google-ads-transparency-dark.png"><img src="cards/google-ads-transparency-light.png" alt="Google Ads Transparency: Every ad an advertiser runs, found by name or website" width="400"></picture></a>
</p>

### Social profiles and jobs

<p>
<a href="https://apify.com/simple.actor/facebook-page-posts"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/facebook-page-posts-dark.png"><img src="cards/facebook-page-posts-light.png" alt="Facebook Page: A public page&#x27;s latest posts with reactions, comments and shares" width="400"></picture></a>
<a href="https://apify.com/simple.actor/instagram-profile-posts"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/instagram-profile-posts-dark.png"><img src="cards/instagram-profile-posts-light.png" alt="Instagram Profile: A public profile&#x27;s latest posts and its follower count" width="400"></picture></a>
<a href="https://apify.com/simple.actor/tiktok-profile-posts"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/tiktok-profile-posts-dark.png"><img src="cards/tiktok-profile-posts-light.png" alt="TikTok Profile: A public profile&#x27;s latest posts with views and followers" width="400"></picture></a>
<a href="https://apify.com/simple.actor/x-profile-posts"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/x-profile-posts-dark.png"><img src="cards/x-profile-posts-light.png" alt="X Profile: A public profile&#x27;s latest posts and stats" width="400"></picture></a>
<a href="https://apify.com/simple.actor/youtube-channel-videos"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/youtube-channel-videos-dark.png"><img src="cards/youtube-channel-videos-light.png" alt="YouTube Channel: A channel&#x27;s latest videos with views and likes" width="400"></picture></a>
<a href="https://apify.com/simple.actor/linkedin-company-posts"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/linkedin-company-posts-dark.png"><img src="cards/linkedin-company-posts-light.png" alt="LinkedIn Company: A company page and its latest posts with engagement" width="400"></picture></a>
<a href="https://apify.com/simple.actor/linkedin-jobs"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/linkedin-jobs-dark.png"><img src="cards/linkedin-jobs-light.png" alt="LinkedIn Jobs: Public job postings for a keyword and a place" width="400"></picture></a>
</p>

### Travel, restaurants and the open web

<p>
<a href="https://apify.com/simple.actor/booking-hotels"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/booking-hotels-dark.png"><img src="cards/booking-hotels-light.png" alt="Booking.com Hotels: Hotels for a destination with prices and reviews" width="400"></picture></a>
<a href="https://apify.com/simple.actor/opentable-restaurants"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/opentable-restaurants-dark.png"><img src="cards/opentable-restaurants-light.png" alt="OpenTable: Restaurants with ratings and their recent booking count" width="400"></picture></a>
<a href="https://apify.com/simple.actor/resy-availability"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/resy-availability-dark.png"><img src="cards/resy-availability-light.png" alt="Resy: Restaurants and the reservation slots they have open" width="400"></picture></a>
<a href="https://apify.com/simple.actor/page-text-reader"><picture><source media="(prefers-color-scheme: dark)" srcset="cards/page-text-reader-dark.png"><img src="cards/page-text-reader-light.png" alt="Web Page Text: Any web page as clean text, plus its links" width="400"></picture></a>
</p>

All of them, with prices: **[apify.com/simple.actor](https://apify.com/simple.actor)**
