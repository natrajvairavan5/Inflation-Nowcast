# Inflation-Nowcast

The BLS publishes the percent change in CPI for the month previous to our current month, usually after the 10th day in. This makes it difficult for policymakers to act on inflation as they do not have current estimates of it, potentially leading to effectiveness lag. As a result, I try to use economic sentiment data published by the SF Federal Reserve to construct estimates of current CPI change. I utilize sentiment data as newspapers, media, etc. react quickly to changes in expectations of market/economy behavior.

I wrote this code on June 15th, 2023 and the CPI estimate for June 2023 was published on July 12th, 2023. I used data from January, 2000 to June 10th, 2023 to build my estimate. Using a VAR model, I predicted that the CPI change for June would be roughly +0.2%, which is exactly what the BLS published in mid-July!

This code is a work-in-progress, as I'm trying to create a function/dashboard that can produce nowcasts for every month and rather than just June 2023.
