# Muted Messages

TV commercials, reviewed with the sound off.

Plenty of viewers watch ads on mute or while scrolling their phones, so a commercial has to work visually. Muted Messages is an ongoing series of op-ads on [Substack](https://uyiuwadiae.substack.com) rating how well an ad's message survives without audio. This repo holds the dataset behind the series and the rubric I use.

## Rating scale

| Rating | Score | Meaning |
|---|---|---|
| Loud and Clear | 2 | Strong without audio |
| Muffled | 1 | Room for improvement |
| Muted | 0 | Message is lost without sound |

## What I look for

Visuals should let viewers understand the message without sound, stop them mid-break, and hold the attention of someone scrolling their phone. In practice I ask:

1. **Hook:** Does something in the first seconds make a viewer look up?
2. **Clarity:** Can you tell what the product is and who it's from?
3. **Reason to choose:** Is there a "why this brand" without audio?
4. **Text:** Do on-screen text and captions carry the message?
5. **Proof:** Does the visual show the product working (demos, side-by-sides)?
6. **Relevance:** Is the moment relatable, or off-putting?
7. **Next step:** Is there a price, offer, or QR code to act on?

## Dataset

`muted_messages_ads.csv` has 50 ads from Issues 1-5.

| Column | Description |
|---|---|
| id | Row number |
| issue | Issue number |
| brand | Advertiser |
| ad_title | Spot name, as listed on iSpot or YouTube |
| featured | Person credited in the spot title, if any |
| category | Industry grouping assigned when compiling the data |
| rating | Loud and Clear, Muffled, or Muted |
| score | 2, 1, or 0 |
| url | Link to the spot |

## At a glance

- 23 Loud and Clear, 13 Muffled, 14 Muted
- Household & Home: 5 of 5 Loud and Clear. Food, Drink & Dining: 7 of 10.
- Technology & Telecom: 3 of 10. Financial Services: 0 of 5.
- Ads crediting a featured person: 3 of 10 Loud and Clear, vs. 20 of 40 without.

One reviewer and small samples, so treat these as descriptive, not conclusive.

## Notes

- Ratings are my judgment of the version I saw on TV. Ad versions vary.
- Categories are my own grouping and open to debate.
- Ads belong to their advertisers. This repo links to spots rather than hosting them.

## Contributing

Open an issue to suggest an ad or challenge a rating.