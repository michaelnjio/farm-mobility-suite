# Farm Mobility Suite
### Built by Michael Njio - Eldoret, Kenya
> One ecosystem for smallholder farming + rural mobility

## 🌾 The 3 Apps

| App | Repo | Problem it Solves | Status |
|---|---|---|---|
| **Shambalens** | [Shambalens](../Shambalens) | Farmers can't identify crop disease early | MVP in progress |
| **ShambaHire** | [ShambaHire](../ShambaHire) | Can't find tractors during planting season | Idea validated |
| **6to6** | [6to6-Bike-Hire](../6to6-Bike-Hire) | No affordable hourly bike hire (6am-6pm) | Idea validated |

## Why Eldoret?
- Uasin Gishu = Kenya's bread basket
- 80% smallholder farmers
- Peak demand = planting season (Oct/Nov, Mar/Apr)
- Same customer can use all 3 apps

## Common Stack (reuse code)
- **Frontend:** Flutter
- **Backend:** Supabase / Firebase
- **Payments:** M-Pesa Daraja (STK Push)
- **Maps:** Google Maps + GPS pin
- **Storage:** Cloudinary for crop/bike photos

## How They Connect
Farmer uses Shambalens -> detects need for spraying -> books sprayer in ShambaHire -> rider delivers inputs using 6to6 bike

## Shared Database Schema
- Users (phone, location, ID)
- M-Pesa Transactions
- Locations (GPS pin)

## Roadmap
- [ ] Phase 1: Shambalens MVP (disease detection)
- [ ] Phase 2: ShambaHire launch for next planting season
- [ ] Phase 3: 6to6 pilot with 5 bikes in Eldoret CBD

## Contact
Michael - WhatsApp: +254...
Location: Eldoret, Rift Valley, KE

---
Built with AFFiNE + GitHub + Meta AI
