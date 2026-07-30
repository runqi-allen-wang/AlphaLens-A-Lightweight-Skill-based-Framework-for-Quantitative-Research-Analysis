# [AlphaLens Skill](https://github.com/runqi-allen-wang/AlphaLens-A-Lightweight-Skill-based-Framework-for-Quantitative-Research-Analysis)
------------------------------------------------------------------------

## I. Overall Task

From the perspective of a senior quantitative researcher, deeply read the user-provided research reports on financial engineering, quantitative investment, asset management, Agent, or market analysis, and compile them into GitHub-compilable Markdown study notes.

The notes adopt a dual-layer structure of **"brief summary + detailed exposition"**:

- The opening concisely summarises the research problem, main method, core conclusions, and primary value.
- The main body expands in detail on the report's methodology, evidence, results, difficulties, innovations, limitations, and transferable value.
- Do not compress the entire note into a bullet‑point outline merely because a “brief recap” is requested.

------------------------------------------------------------------------

## II. General Analytical Requirements

Each research report must address at least the following questions:

1. What problem does the report try to solve?
2. Why is this problem important?
3. What methods, data, or evidence does the author use?
4. What are the main conclusions?
5. What are the research difficulties?
6. What are the innovations?
7. What are the strengths and weaknesses of the method, argument, or system?
8. Under which conditions do the conclusions hold?
9. Which results are transferable?
10. Can the findings be distilled into Alpha in terms of return, risk control, information processing, research efficiency, or organisational capability?

------------------------------------------------------------------------

## III. Research Report Type Identification and Template Routing

Before writing, you must identify the report type. Do not assume all reports are factor, model, or trading strategy studies.

The current type taxonomy includes:

1. Factor and Signal Research
2. Strategy and Portfolio Research
3. Agent and AI Investment Research
4. Market Review and Industry Outlook
5. Macroeconomics, Asset Allocation, and Risk Management
6. Fund Products and Asset Management Industry Research
7. Data Engineering and Research Infrastructure
8. Policy, Event, and Thematic Investment

Identification process:

1. Identify the primary research object.
2. Identify the final output.
3. Identify the main type of evidence.
4. Determine the core value created by the research.
5. Select one primary template.
6. Add an auxiliary template if necessary.

Typical mapping between final output and priority type:

| Final Output                              | Priority Type                |
| ----------------------------------------- | ---------------------------- |
| Stock, sector, or asset ranking values    | Factor and Signal            |
| Positions, weights, trading rules, portfolio NAV | Strategy and Portfolio      |
| Automated research workflows               | Agent and AI Investment      |
| Market regime judgments and future outlook | Market Review               |
| Macro states or risk early‑warning signals | Macro and Risk Management   |
| Fund, manager, or institution evaluations | Fund and Asset Management    |
| Data, computing, or research systems       | Research Infrastructure     |
| Event impact and lists of beneficiary assets | Policy and Thematic Investment |

The note structure should be dynamically adjusted according to the primary type; not every report must discuss model parameters, factor IC, or trading Alpha.

------------------------------------------------------------------------

## IV. Analytical Focus by Research Report Type

### 4.1 Factor and Signal Research

Focus on:

- Factor prediction target
- Factor definition and economic rationale
- Data sources and point‑in‑time
- Factor transformations, windows, and thresholds
- IC, Rank IC, ICIR, and portfolio returns by group
- Exposures to style, industry, size, and liquidity
- Factor correlations and incremental independence
- Factor turnover and decay
- Out‑of‑sample stability
- Transaction costs and capacity

Alpha focus:

- Information under‑reaction
- Risk premium
- Behavioural biases
- Microstructure
- Non‑linear interactions
- State‑conditioned signals

------------------------------------------------------------------------

### 4.2 Strategy and Portfolio Research

Focus on:

- How signals are converted into positions
- Portfolio construction methodology
- Risk budget and constraints
- Rebalancing frequency
- Leverage and cash management
- Transaction costs
- Benchmark for backtesting
- Performance attribution
- Sources of drawdown
- Real‑world capacity and execution

Distinguish among:

- Signal Alpha
- Portfolio construction Alpha
- Risk management Alpha
- Position mapping Alpha
- Execution Alpha

------------------------------------------------------------------------

### 4.3 Agent and AI Investment Research

Focus on:

1. Which research workflow the Agent automates.
2. The boundary of automation.
3. Agent roles and division of labour.
4. Workflow, states, loops, and termination conditions.
5. Interactions among data, tools, knowledge bases, and models.
6. Intermediate result verification.
7. The review logic of an Evidence Reviewer or Judge.
8. Failure recovery, rollback, and version management.
9. Output interpretability.
10. Output auditability and reproducibility.
11. Incremental value over single‑Agent, fixed‑program, and manual processes.
12. Hallucinations, prompt sensitivity, model drift, and information leakage.
13. Token, model call, human review, and maintenance costs.

Alpha for Agent‑type reports includes:

- Research Process Alpha
- Information Processing Alpha
- Decision Consistency Alpha
- Organisational Alpha

Do not force Agent value to be expressed as a traditional stock‑selection factor.

------------------------------------------------------------------------

### 4.4 Market Review and Industry Outlook

Strictly distinguish among:

1. Observed market facts.
2. The author’s interpretation of those facts.
3. The author’s forecasts for the future.
4. Allocation recommendations derived from those forecasts.

Market performance should be decomposed along:

- Asset and sector returns
- Earnings expectations
- Valuation expansion or contraction
- Liquidity
- Fund flows
- Trading congestion
- Risk appetite
- Size, value, and growth styles
- Policy environment
- Overseas interest rates, exchange rates, and risk assets

Extract key elements:

- Market regime identification
- Style rotation signals
- Fund flow signals
- Congestion and reversal risks
- Scenario trigger conditions
- Asset allocation implications

Do not forcibly seek factor Alpha.

------------------------------------------------------------------------

### 4.5 Macroeconomics, Asset Allocation, and Risk Management

Focus on:

- Transmission mechanisms from macro variables to asset prices
- Whether indicators are leading, coincident, or lagging
- Macro data release dates and revisions
- Alignment of data at different frequencies
- Market regime definition
- Asset sensitivity to regimes
- Portfolio defensive structures
- Adequacy of crisis samples
- False positives and false negatives
- Structural breaks and regime changes
- Whether performance improvement mainly comes from drawdown control

Alpha focus:

- Regime Alpha
- Risk Management Alpha
- Cross‑asset relative value
- State‑dependent allocation
- Risk signal propagation order
- Tail protection

------------------------------------------------------------------------

### 4.6 Fund Products and Asset Management Industry

Focus on:

- Fund performance
- Risk and maximum drawdown
- Share class changes
- A/C class shares
- Investor behaviour
- Fund manager skill
- Style drift
- Institutional holdings
- Distribution capability
- Fee structures
- Fund size and strategy capacity
- Team stability
- Institutional organisational capability

Alpha focus:

- Fund selection Alpha
- Lagged fund flow Alpha
- Persistence of low drawdown
- Manager changes
- Product congestion and capacity
- Organisational quality

------------------------------------------------------------------------

### 4.7 Data Engineering and Research Infrastructure

Focus on:

- The research bottleneck the system addresses
- Data sources and data structure
- Point‑in‑time
- Version management
- Data quality control
- Caching and parallelism
- GPU and computing resources
- Scalability
- Auditability
- Failure modes
- Maintenance costs
- Whether engineering optimisations affect statistical conclusions

Alpha includes:

- Data Quality Alpha
- PIT Alpha
- Research Speed Alpha
- Reproducibility Alpha
- Infrastructure Alpha

------------------------------------------------------------------------

### 4.8 Policy, Event, and Thematic Investment

Focus on:

- Event content
- Market expectation gap
- Transmission chain of the policy or event
- Beneficiary and affected industries
- Industry chain mapping
- Concept purity
- Order and earnings validation
- Extent to which the market has priced in
- Thematic life cycle
- Congestion and realisation risks
- Falsification conditions

Alpha includes:

- Policy expectation gap
- Event under‑reaction
- Industry chain diffusion
- Concept purity
- Thematic life cycle
- Congestion reversal

------------------------------------------------------------------------

## V. Extended Definition of Alpha

Alpha is not limited to factors that predict future returns.

Depending on the report type, Alpha can be distilled as:

| Alpha Type | Meaning |
|------------|---------|
| Prediction Alpha | Improves return prediction accuracy |
| Risk Management Alpha | Reduces drawdown, volatility, or tail risk |
| Research Process Alpha | Increases research speed and experimental efficiency |
| Information Processing Alpha | Enhances the ability to process unstructured information |
| Decision Consistency Alpha | Reduces decision volatility and subjective bias |
| Data Quality Alpha | Leverages more accurate and timely data |
| Infrastructure Alpha | Improves research through systems and computing platforms |
| Organisational Alpha | Enhances knowledge accumulation and team collaboration |

For each Alpha, specify as much as possible:

1. Core logic
2. Signal, mechanism, or method
3. Source of value
4. Applicable scenarios
5. Failure risks
6. Directions for future improvement

------------------------------------------------------------------------

## VI. Note Structure

All notes adopt the following structure:

### First Layer: Quick Summary

Usually includes:

1. One‑sentence summary
2. Research report type
3. Core problem
4. Core framework
5. Main conclusions
6. Most notable innovation and value

Example:

``` markdown
# [Report Title](link): Study Notes

> Original: ...
> Primary template: ...
> Auxiliary template: ...
> This note focuses on ...
> For research and study purposes only; not investment advice.
```

### Second Layer: Detailed Exposition

Dynamically expands based on the primary template:

1. Research background
2. Problem definition
3. Method or system structure
4. Data and evidence
5. Empirical or case studies
6. Interpretation of results
7. Applicable scenarios
8. Innovations
9. Research difficulties
10. Strengths
11. Weaknesses
12. Alpha
13. Replication and improvement
14. Core assessment

The word “brief” applies only to the first layer; do not compress the detailed exposition.

------------------------------------------------------------------------

## VII. General Checks for Models and Empirical Work

Only when the report contains models, predictions, backtests, or statistical tests, analyse:

- Objective and assumptions
- Inputs and prediction target
- Separation of training, validation, and test sets
- Look‑ahead bias
- Parameter selection
- Multiple testing
- Benchmark models
- Backtest length
- Different market regimes
- Transaction costs
- Market impact costs
- Capacity
- Style exposures
- Beta
- Out‑of‑sample stability
- Cross‑market transferability

This section is not mandatory for all reports.

------------------------------------------------------------------------

## VIII. Markdown and LaTeX Standards

1. Output must be Markdown that renders correctly on GitHub.
2. All mathematical formulas must not have line breaks inside the source code.
3. Inline formulas must be written entirely on the same source line.
4. Display‑style formula bodies must be entirely on the same source line.
5. Use appropriate spaces between characters.
6. Break multi‑step derivations into separate formulas.
7. Do not use `\operatorname{...}`.
8. Use `\mathrm{...}` uniformly for ordinary mathematical operators or text.
9. Check formula formatting before final output.

Correct example:

``` markdown
$$
a = b
$$
```

Incorrect:

``` markdown
$$
a
=
b
$$
```

------------------------------------------------------------------------

## IX. README Synchronisation Rules

After completing each report, add:

New entry:

No. Topic Report Main Idea Time Recommendation ----- ------- -------- ----------- ------ ----------------

Example:
[01](https://github.com/runqi-allen-wang/Quant-Research-Report-Notes/blob/main/report_01_ts_cta_methodology/notes.md)
\| Time-Series CTA \| Huatai Research, "Time‑Series CTA Methodology Overview: Market Regimes, Entry Signals, and Exit Mechanisms" \| Decomposes CTA returns from three dimensions – market regime identification, trend signals, and exit mechanisms – to build a systematic trend‑following research framework \| 2026-06-10 \| 🧩 \|

Topic requirement: 2‑3 English words

------------------------------------------------------------------------

### 9.1 README Main Idea Specification

For each report, a single Chinese Main Idea sentence is required.

Requirements:

- Write only one sentence.
- Concise and accurate.
- Summarise the core research logic, main method, and primary value or Alpha.
- Do not pile up backtest statistics.
- Suitable for direct inclusion in the README.
- Recommended length: 30‑70 Chinese characters.

------------------------------------------------------------------------

### 9.2 Recommendation Emoji Specification

Recommendation uses three independent dimensions:

- 🚀: Industry leading‑edge
- 🧩: Framework completeness
- 🔁: Strong reproducibility

Criteria:

#### 🚀 Industry Leading‑edge

The method, system, research perspective, or application is at the frontier of the industry and offers clear incremental value.

#### 🧩 Framework Completeness

The report provides a clear problem definition, methodology system, validation process, and implementation path.

#### 🔁 Strong Reproducibility

The report provides sufficient data, parameters, steps, formulas, or implementation details to allow a third party to replicate it substantially.

Example combinations:

- `🚀🧩🔁`
- `🚀🧩`
- `🧩🔁`
- `🔁`
- Fill with `-` if none of the three apply.
