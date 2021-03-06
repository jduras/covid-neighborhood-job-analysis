# Changelog

## 5/8/20 Update

As planned, made the following updates:

- Used BLS CES data for national net job change estimates
- Changed the method of using advanced state-level claims to modify state-by-industry level job loss estimates file so that estimates were accurate for new data
- No longer using any state industry level estimates
- Update (but don't use) Washington and New York unemployment data

## 4/23/20 Update

Due to great user feedback, made the following updates:

- Updated data with new NY and WA state data, BLS advance state-level claims
- Added NY data to the processing pipeline, calculating weighted average of WA and NY for industry-level estimates, leave estimates for NY and WA as is
- Added BLS advance state-level claims and created a state by industry level job loss estimates file
- Use state by industry job loss estimates and apply to LODES data on low-income jobs by industry to produce more realistic estimates

## 4/16/20 Initial Release