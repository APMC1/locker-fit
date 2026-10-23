# Awin — publisher application, then DavPack and Parcel2Go

Join Awin first: https://ui.awin.com/publisher-signup/en/awin  
Publisher how-to: https://success.awin.com/s/article/How-do-I-join-Awin-as-a-Publisher

DavPack asks for a checkable imprint. The public site does not list a home address or personal email. Use a dedicated publisher email and, if they insist on a postal address, a PO Box or virtual mailbox. Put those only on Awin’s private application, never on the live pages.

## Awin network form

**Primary region:** United Kingdom  
**Promotional type:** Content / editorial (not cashback, not voucher-only, not PPC)

**Promotional space URL**  
`https://apmc1.github.io/locker-fit/`

**Description of the promotional space**

> Locker Fit is a UK content site for Vinted and other secondhand sellers. Pages cover courier choice (InPost locker vs Evri vs Royal Mail), packing to locker size caps, and measuring garments. Traffic plan is organic search for operational queries. I will promote packaging supplies (boxes, mailers, tape) and, where a seller outgrows Vinted’s integrated labels, courier comparison. No coupon scraping, no cashback, no brand-bidding.

**Sectors:** Retail, Home & Garden, Consumer Goods (packaging). Add “Travel” only if you later cover Parcel2Go international; skip it for now.

## DavPack UK (Awin advertiser 29981)

Programme page: https://ui.awin.com/merchant-profile/29981  
Commission listed: from 2% by publisher type. Cookie listed: 30 days.  
Free delivery on their site currently starts at a £100 order — mention bulk boxes, not one mailer.

**Application message**

> I run Locker Fit, a UK guide for Vinted sellers who pack clothing to InPost / Evri / Royal Mail size caps. The courier page already points readers to cardboard boxes when a coat or bundle will not fit a poly mailer. I want to replace that homepage link with a tracked DavPack link to boxes and mailers. Site is original editorial, has an imprint, and will not run SEM on your brand or unapproved voucher codes.

After approval, swap the DavPack homepage URL in `site/courier-choice.html` for the Awin tracking link.

## Parcel2Go (Awin advertiser 18733)

Programme page: https://ui.awin.com/merchant-profile/18733  
Commission listed: 10% new-customer sales, 1% existing-customer sales (ex VAT). Cookie listed: 30 days.  
Voucher codes that are not exclusive to the programme are declined.

**Application message**

> I publish UK Vinted seller ops notes. Integrated Vinted labels cover most clothing. I only recommend an off-platform label when the packed item is over every Vinted carrier cap and the seller uses custom shipping. Parcel2Go is the comparison step for that edge case, not a replacement for InPost lockers. Content site, no brand PPC, no non-exclusive voucher dumping.

Use Parcel2Go links only on pages that discuss custom shipping or oversized parcels. Do not put them on every clothing page.

## Order of operations

1. Public URL is live. Imprint stays without a home address.
2. Awin publisher account
3. Apply to DavPack
4. Apply to Parcel2Go
5. Replace placeholder URLs
6. Do not email merchant AMs with a different story than the live pages
