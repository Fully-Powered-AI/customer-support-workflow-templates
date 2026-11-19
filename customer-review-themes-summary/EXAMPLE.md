# Customer review themes summary: an example

*Illustrative example with sample data.* Bakery A is an illustrative bakery and café with two shops, the North shop and the South shop. Its reviews appear on two public review sites, called Site A and Site B here. The reviewers, the staff, the reviews and every number below are illustrative. On Tuesday 3 November 2026 the marketing lead runs the workflow template on October's reviews.

The inputs come first, in full, so the workflow template can be run on them. The summary follows.

## The inputs

### The settings

```
Period: 1 October 2026 to 31 October 2026. Prepared: 3 November 2026.
Report reader: marketing lead.
Replies to reviews: customer service lead.
Named person for reviews set apart: owner.
Manager's note goes to: general manager.
Theme minimum: the default. Column mapping: none; the export uses the
default headers.
```

### Our theme list

```
Queue and wait time
Bread and pastry quality
Coffee
Staff friendliness
Prices
```

### Last period's summary (September 2026)

```
Site A: 9 reviews, average 4.1
Site B: 6 reviews, average 4.5
All sites: 15 reviews, average 4.3
Themes (reviews): Bread and pastry quality 6; Coffee 3; Queue and wait
time 2; Staff friendliness 2; Seating 2
```

### The reviews export from your reviews and reputation platform

One row per review, with the default columns: review ID, date, site, rating, reviewer name, text, replied (yes or no), reply date, and location or product.

```
review_id,date,site,rating,reviewer_name,text,replied,reply_date,location_or_product
R-201,2026-09-30,Site A,5,Dana Whitlow,"Best sourdough in town.",yes,2026-10-01,North shop
R-202,2026-10-02,Site A,2,Marcus Ode,"Waited twenty minutes in the queue on Saturday morning for two coffees. Pastries were good once we got them.",no,,North shop
R-203,2026-10-03,Site B,5,Priya Lomas,"The almond croissant is the best I've had anywhere. Flaky and not too sweet.",yes,2026-10-05,South shop
R-204,2026-10-04,Site A,4,Tom Brennick,"Lovely bread, but the queue went out the door and only one till was open.",yes,2026-10-06,North shop
R-205,2026-10-06,Site B,1,Helen Q.,"My son has a nut allergy. We asked twice and were told the muffin had no nuts. He reacted within minutes and we had to use his pen. Nobody should go through that.",no,,South shop
R-206,2026-10-08,Site A,5,Sam Ferro,"Ellie at the counter remembered my order from last week. Coffee was perfect.",yes,2026-10-09,North shop
R-207,2026-10-09,Site A,3,Grace Allard,"Coffee was lukewarm and the flat white tasted burnt. Asked Josh to remake it and he just shrugged.",no,,North shop
R-208,2026-10-11,Site B,4,Owen Tasker,"Great rye loaf. A bit pricey for the size though.",yes,2026-10-12,South shop
R-209,2026-10-12,Site A,2,Lena Marsh,"Forty minutes for a table and nobody told us how long it would be.",no,,North shop
R-210,2026-10-14,Site B,5,Rafael Dunn,"Friendly team, warm welcome every time.",no,,North shop
R-211,2026-10-15,Site A,1,Corinne Vale,"The staff member at the till refused to serve my friend because of her headscarf and laughed about it. I will be taking this further.",no,,North shop
R-212,2026-10-17,Site B,3,Jon Petrakis,"Nearly five for a slice of cake is too much. Croissant was great though.",yes,2026-10-18,South shop
R-213,2026-10-19,Site A,4,Ama Kesh,"Great pastries. Coffee was cold by the time it reached the table.",yes,,North shop
R-214,2026-10-21,Site B,3,Ben Hollis,"Parking near the shop is impossible on weekdays.",no,,South shop
R-215,2026-10-23,Site A,1,Nadia Fenn,"Ate the chicken sandwich at lunch and was sick all night. Two of us had it and both were ill.",no,,North shop
R-216,2026-10-25,Site B,5,Ivo Brandt,"Sourdough and a cortado every Sunday. Never disappoints.",yes,2026-10-26,North shop
R-217,2026-10-27,Site A,2,Kit Morrow,"Queue was so long we gave up and left.",no,,North shop
R-218,2026-10-28,Site B,4,Mei Laurent,"Pricey, but the cinnamon bun is worth it.",no,,South shop
R-219,2026-10-30,Site A,5,,"Lovely staff and the best croissants around.",yes,2026-10-31,North shop
R-220,2026-10-31,Site B,1,Paul Grieve,"Charged twice for one order. If my refund isn't sorted this week you'll be hearing from my lawyer.",no,,South shop
```

## The output

The summary is plain text, exactly as the workflow template sets it out. The manager's note follows the closing line, so the marketing lead can cut it off and pass it to the general manager alone.

```
CUSTOMER REVIEW THEMES SUMMARY: 1 October 2026 to 31 October 2026

For: marketing lead. Prepared 3 November 2026. Period 1 October 2026 to 31 October 2026.
Rows in the export: 20. Outside the period, left out: 1 (R-201).
Reviews in the period: 19. Set apart: 4. In at least one theme: 14. Not in a theme: 1.
Theme list: supplied. Last period: September 2026.

COUNTS BY SITE AND RATING

Site A | 5 stars 2 | 4 stars 2 | 3 stars 1 | 2 stars 3 | 1 star 2 | No rating 0 | Total 10 | Average 2.9
Site B | 5 stars 3 | 4 stars 2 | 3 stars 2 | 2 stars 0 | 1 star 2 | No rating 0 | Total 9 | Average 3.4
All sites | 5 stars 5 | 4 stars 4 | 3 stars 3 | 2 stars 3 | 1 star 4 | No rating 0 | Total 19 | Average 3.2
Check: 1 + 19 = 20. Site totals 10 + 9 = 19. Ratings 5 + 4 + 3 + 3 + 4 + no rating 0 = 19. Set apart 4 + in a theme 14 + not in a theme 1 = 19.

SET APART FOR OWNER

R-205 (Site B, 2026-10-06, 1 of 5): says a child with a nut allergy reacted within minutes after the family was told a muffin had no nuts.
- Matter: safety
- Replied: no

R-211 (Site A, 2026-10-15, 1 of 5): says a member of staff at the till refused to serve the reviewer's friend because of her headscarf.
- Matter: discrimination
- Replied: no

R-215 (Site A, 2026-10-23, 1 of 5): says two people were ill overnight after eating the chicken sandwich.
- Matter: illness
- Replied: no

R-220 (Site B, 2026-10-31, 1 of 5): says the reviewer was charged twice for one order and mentions a lawyer if the refund is not sorted.
- Matter: legal threat
- Replied: no

THEMES

1. Bread and pastry quality | Praised | Reviews 9: R-202, R-203, R-204, R-208, R-212, R-213, R-216, R-218, R-219 | Last period: 6
- Locations: North shop 5, South shop 4
- In their words: "Pastries were good once we got them." (R-202, Site A, 2 of 5)

2. Queue and wait time | Criticised | Reviews 4: R-202, R-204, R-209, R-217 | Last period: 2
- Locations: North shop 4
- In their words: "Waited twenty minutes in the queue on Saturday morning for two coffees." (R-202, Site A, 2 of 5)

3. Coffee | Mixed | Reviews 4: R-206, R-207, R-213, R-216 | Last period: 3
- Locations: North shop 4
- In their words: "Coffee was lukewarm and the flat white tasted burnt." (R-207, Site A, 3 of 5)

4. Staff friendliness | Mixed | Reviews 4: R-206, R-207, R-210, R-219 | Last period: 2
- Locations: North shop 4
- In their words: "[staff member] at the counter remembered my order from last week." (R-206, Site A, 5 of 5)

5. Prices | Criticised | Reviews 3: R-208, R-212, R-218 | Last period: new
- Locations: South shop 3
- In their words: "A bit pricey for the size though." (R-208, Site B, 4 of 5)

Themes on your list with no review this period: None.
Last period's themes not seen this period: Seating (2 last period).

NOT IN A THEME

R-214

WHAT CHANGED SINCE LAST PERIOD

Site A: reviews 10 (last period 9); average 2.9 (last period 4.1).
Site B: reviews 9 (last period 6); average 3.4 (last period 4.5).
All sites: reviews 19 (last period 15); average 3.2 (last period 4.3).

NO REPLY YET, OLDEST FIRST (for customer service lead)

R-202 | 2026-10-02 | Site A | 2 of 5 | M.O. | waiting 32 days
R-205 | 2026-10-06 | Site B | 1 of 5 | H.Q. | waiting 28 days | set apart: reply waits for owner
R-207 | 2026-10-09 | Site A | 3 of 5 | G.A. | waiting 25 days
R-209 | 2026-10-12 | Site A | 2 of 5 | L.M. | waiting 22 days
R-210 | 2026-10-14 | Site B | 5 of 5 | R.D. | waiting 20 days
R-211 | 2026-10-15 | Site A | 1 of 5 | C.V. | waiting 19 days | set apart: reply waits for owner
R-214 | 2026-10-21 | Site B | 3 of 5 | B.H. | waiting 13 days
R-215 | 2026-10-23 | Site A | 1 of 5 | N.F. | waiting 11 days | set apart: reply waits for owner
R-217 | 2026-10-27 | Site A | 2 of 5 | K.M. | waiting 7 days
R-218 | 2026-10-28 | Site B | 4 of 5 | M.L. | waiting 6 days
R-220 | 2026-10-31 | Site B | 1 of 5 | P.G. | waiting 3 days | set apart: reply waits for owner

QUESTIONS

1. R-213 is marked as replied but has no reply date. Was the reply posted, and on what date?

Prepared for marketing lead. No reply has been drafted or posted, no review has been reported, and nothing has been changed.

MANAGER'S NOTE: STAFF NAMED IN REVIEWS (for general manager only; not part of the summary)

R-206 (Site A, 2026-10-08): names "Ellie".
R-207 (Site A, 2026-10-09): names "Josh".
```

How the figures add up: the export holds 20 rows; R-201 is dated 30 September and is left out, leaving 19 reviews, 10 on Site A and 9 on Site B. Site A's ratings add to 29 over 10 reviews, an average of 2.9; Site B's add to 31 over 9, which is 3.44 and shows as 3.4; all sites add to 60 over 19, which is 3.16 and shows as 3.2. Four reviews are set apart and sit in no theme, R-214 is the only review about parking and so falls below the theme minimum of two, and the other 14 sit in at least one theme. The five themes hold 24 places because ten reviews each speak about two things and sit in two themes (R-202, R-204, R-206, R-207, R-208, R-212, R-213, R-216, R-218 and R-219), while R-203, R-209, R-210 and R-217 sit in one each: 20 + 4 = 24. Coffee is Mixed with two reviews praising it (R-206, R-216) and two criticising it (R-207, R-213), so its line comes from the earliest criticising review. Days waiting are counted from each review's date to 3 November 2026. No reply was drafted, and no review was reported to either site.
