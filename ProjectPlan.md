○ Overview: Describe the overall goal of your project and your planned approach to
achieve it. Explain what you aim to accomplish and outline the main steps or methods
you will use to execute the project (max 250 words).

template: The goal of this project is to [investigate/understand/compare] [topic] in order to [purpose or decision it supports]. To do this, we will integrate three complementary datasets: [type of data A], [type of data B], and [type of data C], which can be linked through shared attributes such as [geographic codes / time periods / entity IDs].

Our approach follows the [name of lifecycle model] and emphasizes the full data curation chain. We will (1) programmatically acquire the datasets and verify their integrity with SHA-256 checksums; (2) assess data quality before integration across accuracy, completeness, timeliness, and consistency; (3) clean the data to address the issues identified; (4) integrate the datasets using [Python/Pandas or SQL]; (5) reassess quality after integration to confirm the join succeeded; and (6) perform an analysis and visualization to answer our research questions. The entire workflow will be automated with [Snakemake / a run-all script] using separate single-purpose scripts, documented with a data dictionary and standards-based metadata, and managed in GitHub so that anyone can reproduce it from a clean clone.



○ Team: Clearly define team member roles and planned responsibilities.
-Eman worked on Overview and Business Questions

○ Research or Business Question(s): What is/are the question(s) you intend to address?
These could be research questions, business questions, or analytical questions you want
to answer through data analysis.

Type	Generic template
Relationship: Is there a relationship between [variable from A] and [variable from B] across [geographic unit]?
Trend over time: How has [measure] changed from [year] to [year], and does it differ by [group/region]?
Comparison: How do [regions/groups] differ in [outcome] after accounting for [factor from dataset C]?
Influencing factors: Which of [factor X, Y, Z] is most associated with [outcome]?
Hotspots/disparities: Which [areas/entities] have the highest [outcome] relative to [context variable]?
Impact of an event: Did [event, policy, or season] coincide with a change in [outcome]?
Business framing: Where should [an organization] focus resources to improve [outcome], given [conditions]?
