:

Room Changes: 18.5% of bookings

Impact on Cancellation Rate:

No Change: 36% cancellation

Room Changed: 28% cancellation

Insight: Upgrades reduce cancellations!

Impact on Guest Satisfaction (indirect):

Unexpected changes negatively affect reviews

Upgrades positively affect future bookings

6. Lead Time Category (Refined)
python
# Categorizes booking patterns for risk assessment
# Same Day: Impulse bookings (high variance, low volume)
# 1-30 days: Standard advance bookings (highest volume)
# 31-90 days: Medium-term planners (balanced)
# 91-180 days: Business/group bookings
# >1 year: Corporate contracts (high cancellation risk)
📈 Key Findings
1️⃣ Cancellation Patterns
Overall Cancellation Rate: ~37%

City Hotels: Higher absolute cancellations (~60% of all cancellations)

Resort Hotels: Lower cancellation rate but more price-sensitive

Cancellation Drivers (in order of impact):

Lead Time (Strongest Predictor)

Same Day: 8% cancellation

0-30 days: ~15% cancellation

1 year: ~53% cancellation

Insight: Longer lead times = higher cancellation risk (r = 0.34)

Deposit Type

No Deposit: ~40% cancellation

Refundable Deposit: ~13% cancellation

Insight: Requiring deposits significantly reduces cancellations (r = -0.45)

Special Requests & Engagement

0 requests: ~42% cancellation

≥1 request: ~14% cancellation

Insight: Engaged guests rarely cancel (r = -0.32)

Room Changes

No Room Change: 36% cancellation

Room Changed: 28% cancellation

Insight: Room upgrades reduce cancellations by 8 percentage points

Market Segment

Online Travel Agents: ~42% cancellations

Direct Bookings: ~19% cancellations

Insight: Direct bookings are more committed

2️⃣ Revenue Insights
Peak Season ADR (Average Daily Rate):

Highest: €124-130 (July-August)

Lowest: €75-85 (December-February)

Variance: 55% price elasticity across seasons

Revenue Optimization:

City Hotels: Avg €105/night | Resort Hotels: Avg €96/night

Summer months: 45% higher rates than winter

Weekend rates: ~8% premium over weekdays

Revenue by Lead Time Category:

Same Day: €267 avg revenue (high-margin, low-volume)

1-30 days: €289 avg revenue (sweet spot)

1 year: €378 avg revenue (high-value but cancellation risk)

Guest Composition Revenue Impact:

1 guest: Lower revenue but highest completion rate

2-3 guests: Optimal revenue + completion balance

4+ guests: High revenue but more cancellations

3️⃣ Guest Segmentation
Market Segments Distribution:

Online Travel Agencies: ~47% (most volume, highest cancellations)

Direct Bookings: ~20%

Corporate: ~19%

Complementary: ~7%

Aviation: ~4%

Repeat Guest Analysis:

Repeat guests: ~3.3% of total bookings

Repeat guest cancellation rate: 11% vs 38% for new guests

Repeat guests: 2.5x higher special request rate

Insight: Loyalty programs highly effective

Room Change Impact by Guest Type:

New guests with room changes: 26% cancellation

Repeat guests with room changes: 9% cancellation

Insight: Repeat guests more forgiving of changes

4️⃣ Seasonal Trends
Peak Months (Highest Bookings & Revenue):

August: 13,877 bookings | €1.8M revenue

July: 12,417 bookings | €1.7M revenue

May: 11,547 bookings | €1.3M revenue

Off-Season (Lowest Bookings):

December-February: 40% reduction in bookings

September-October: Transition period

Opportunity: Off-season promotions can recover 20-30%

Stay Duration Patterns:

Average stay: 3.4 nights

Peak months: Longer stays (4-5 nights)

Off-season: Shorter stays (2-3 nights)

Weekend bookings: Slightly longer (3.6 vs 3.2 nights)

5️⃣ Room Management Insights
Room Change Statistics:

Total Room Changes: 18.5% of bookings

Room Changes by Hotel Type:

City Hotels: 19.2% (higher turnover/availability issues)

Resort Hotels: 17.1%

Room Changes by Lead Time:

Same Day: 25% (unavoidable)

1-30 days: 16% (mostly upgrade opportunities)

1 year: 14% (planned assignments)

Operational Implications:

Room changes often represent upgrades (cost-neutral)

Impact on cancellation: 8% reduction when changed

Impact on future bookings: Positive correlation with repeats

Recommendation: Use strategic upgrades as retention tool

6️⃣ Data Quality Summary
Cleaning Operations Performed:

Duplicates Removed: 488 records

Invalid ADR Values: 1 negative value (removed)

Missing Values Handled:

Country: Filled with mode (PRT - Portugal): 488

Children: Rows dropped: 4

Other NAs: Rows dropped: ~300

Outliers Removed:

ADR: Capped at 3x IQR (extreme prices)

Adults: Limited to 1-10 (removed implausible groups)

Stay Duration: Limited to 0-30 nights

Columns Dropped: 4 (company, agent, arrival_date_week_number, reservation_status_date)

Columns Added: 6 (engineered features)

Final Clean Dataset:

Records after cleaning: ~110,000

Duplicate rate: 0.41%

Data quality score: 96.5%

Ready for analysis and modeling

📊
