# mrizvi analysis notes:
- "discriminator" is the column to exclude Reseller data, but this should/can be a clearer field
- one row in the CSV is one HubSpot contact ID, and a single company can have many contacts (figure out whether this matters in the analysis, I personally suspect it may have something to do with licenses that were just added on without any self-discovery from the user)
- check whether the following had an effect on conversion numbers/rates
"**Note on contact_source_type = 'Integration':** When a company purchases asubscription and assigns seats to employees, OT’s billing system automatically creates a HubSpot contact for each assigned user. These contacts did not independently choose to try the product. A product change (Account-BasedLicensing, released November 17, 2025) was intended to reduce this — whether it did is something you can test."
- check whether the following has an effect on conversion numbers/rates
"**Note on resellers:** When a reseller purchases on behalf of a customer, the HubSpot contact may represent the reseller’s employee or procurement team rather than an actual end user of the product."