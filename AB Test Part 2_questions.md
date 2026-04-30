# TLAB #3 – Stakeholder Questions
**Analyst:** Mina  
**Project:** Intro to TLAB #3 – Part 2  

---

## Section 1: Context Setting
## Establish what was already done before this A/B test. What are some questions you can ask to get more information on what has already been measured, analyzed, or attempted? List them below...

1. **What data has already been collected or analyzed related to this topic?**  
   Understanding prior analyses to prevent duplicate work and it helps me build on existing findings rather than starting from scratch.

2. **Who originally collected this dataset, and for what purpose?**  
   Knowing the original intent of the data helps me assess whether it's appropriate for the questions we're now trying to answer.

3. **Are there known quality issues or limitations with this dataset (e.g., missing values, inconsistent formatting, sampling bias)?**  
   Being aware of these upfront shapes how I clean the data and how much I should qualify my conclusions.

4. **Have any previous attempts been made to answer similar questions, and if so, what were the findings or roadblocks?**  
   This prevents me from repeating failed approaches and helps me understand which directions are worth pursuing.

5. **Who are the other stakeholders or teams affected by this analysis, and do they have their own existing metrics or benchmarks?**  
   If another team is already tracking related outcomes, aligning my analysis with their frameworks will make findings more actionable.

---

## Section 2: Goal Alignment
## Align with stakeholders on what success means before interpreting any numbers.

1. **What specific question or decision should this analysis help answer?**  
   Without a clear decision to support, it's easy to generate findings that are interesting but not useful.

2. **What does improvement look like in this context — and how will we measure it?**  
   Defining "better" before analyzing helps ensure the metrics I choose actually reflect the outcome the stakeholder cares about.

3. **Is there a target value, threshold, or benchmark we are trying to reach or exceed?**  
   A concrete target gives the analysis direction and makes it possible to evaluate whether a result is meaningful or not.
   Without a defined target, it's hard to say whether the treatment "worked." For example, if the benchmark for engaged users is 15+ minutes, and the treatment group clusters there, that's meaningful. If no benchmark exists, one needs to be established before conclusions are drawn.



## Section 3: Define Over-performance
## Consider what it would mean if the treatment dramatically exceeded expectations.
   
   If viewing time increases by 50% or more, first check for data quality issues like tracking duplication or mislabeled groups.

   Consider whether the treatment created a novelty effect that will wear off after users get used to it.

   Look at whether the huge increase came from a small subset of users, such as those with very low prior engagement.


## Section 4: Data Sourcing
## Reflect on what other data sources you can use to answer your stakeholders exploratory goals.

   Use session-level event data to see exactly when users paused, skipped, replayed, or exited during their viewing session.

   Pull user metadata like account age, subscription tier, device type, and operating system to run segment analyses.

   Combine with survey responses, ratings, and feedback