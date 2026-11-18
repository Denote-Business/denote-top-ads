# Denote Top Ads

Find winning ad creatives to study before your next campaign. Denote tracks **10 million+ ads** and refreshes its rankings every week. Ask your agent for game or app ads and get three shortlists from the latest completed week, with up to 10 creatives on each. [Explore Denote Top Ads](https://denote.net/top-ads).

| Free chart | When to use it |
| --- | --- |
| Trending Ads | See which creatives drew the most attention last week. Bring a few references to your next creative review. |
| Rising Ads | Spot ads with the biggest week-over-week gain in popularity. Find a creative direction while it is picking up speed. |
| New Ads | Discover newly spotted creatives ranked by early popularity. Bring fresh examples to your next brainstorm. |

## Get your first three charts

1. Install the skill. In an OpenClaw workspace, run `git clone https://github.com/Denote-Business/denote-top-ads.git skills/denote-top-ads`. The client uses Python 3.
2. Start a new agent session and say **“Open Denote Top Ads.”** The skill introduces the three charts and walks you through connecting your account.
3. [Register for a free Denote account](https://denote.net/user/register), or sign in if you already have one. Create a Denote API Key with the `top_ads:read` permission, or add that permission to an existing key.
4. Save the key in your agent host's secret settings as `DENOTE_API_KEY`. Tell your agent **“My key is ready. Show me last week's winning app ads.”**

Your free account gets all three charts. Each result includes the rank and available title, advertiser, format, platforms and preview. The first report defaults to games if you leave the category open. For a closer look, ask “Open number two on Rising Ads.” Ranked creative details, including available performance and audience data, require Top Ads Pro or Business.
