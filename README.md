<!-- TEMPLATE-ONLY: remove everything above the PROJECT README marker after initialization. -->
# Using this template

A minimal template for research and clinical quality-improvement projects, based on [Good Enough Practices in Scientific Computing](https://carpentries-lab.github.io/good-enough-practices/index.html).

1. Copy the template into a named project folder.
2. Replace the examples below with project details and setup instructions. Keep only guidance that applies.
3. Update `CITATION` and the copyright placeholders in `LICENSE`. Check that the rights holders agree to the licenses and that institutional, funder, and publication rules allow them. Record exceptions there.
4. Remove this template section, the boundary marker below, and the setup note in `LICENSE`.

<!-- PROJECT README: keep and adapt everything below. Remove this marker after initialization. -->
# Name <!-- Replace with the project name. -->

> Example: Improving discharge follow-up

## Description

<!-- Short description of the project and its aim. -->

This repository describes a randomized clinical trial of different combinations of Index-Generating Electroencephalograph Software and targeted controlled infusion modes on outcomes in patients under general anaesthesia for surgical procedures in Sweden. This project is in an early planning stage. Potential outcomes include hemondynamic stability, mortality, complications including brain, heart, lungs and kidney. Explore long term effects on cognition including dementia onset and cancer reoccurrence. 

## Team and contact

<!-- Names, roles, and contact person. -->

Martin Gerdin Wärnberg (principal investigator, martin.gerdin@ki.se, martin.gerdin-warnberg@regionstockholm.se)

## Related research

This targeted literature overview was prepared by an AI-agent on 2026-10-17. It is not a systematic review. The studies address different questions: comparisons of TCI pharmacokinetic models, EEG guidance versus routine care, anaesthetic-depth targets, and automated versus manually adjusted infusion.

### TCI models and induction strategies

- **Marsh versus Schnider in elective cardiac surgery (2012).** Randomised trial of 90 patients comparing effect-site propofol TCI models, titrated until BIS <50. No statistically significant differences in propofol dose, blood-pressure reduction, or vasopressor use were demonstrated. Induction time and predicted effect-site concentrations differed. Relevant to comparing TCI models while holding EEG guidance constant. [Publication](https://pubmed.ncbi.nlm.nih.gov/22935955/)

- **Modified Marsh versus Schnider during induction and intubation (2015).** Randomised trial of 280 patients; both groups titrated to BIS 35–55. No haemodynamic difference was demonstrated. Hypotensive events occurred in 17.3% versus 12.8%, respectively. Relevant to model comparisons and induction outcomes. [Publication](https://pubmed.ncbi.nlm.nih.gov/25600619/)

- **PROTECT protocol (2026).** Multicentre, expertise-based randomised trial in patients aged ≥55 undergoing noncardiac surgery, comparing titrated versus conventional induction using Schnider propofol TCI. This is a protocol, not outcome evidence. Relevant to induction rate, target increments, and haemodynamic stability. [Protocol](https://pmc.ncbi.nlm.nih.gov/articles/PMC12853554/) · [Registration: NCT06980688](https://clinicaltrials.gov/study/NCT06980688)

### EEG guidance and EEG–TCI combinations

- **Liu et al. (2006).** Multicentre randomised trial of 164 patients comparing BIS-guided closed-loop propofol TCI with manually adjusted propofol TCI; remifentanil TCI was adjusted manually in both groups. Establishes a precedent for EEG feedback controlling TCI during induction and maintenance. The intervention is automation rather than a comparison of EEG-index algorithms. [Publication](https://pubmed.ncbi.nlm.nih.gov/16571963/)

- **Liu et al. (2011).** Multicentre randomised comparison of BIS-guided closed-loop coadministration of propofol and remifentanil with manual TCI. Relevant to combined hypnotic–opioid control and to separating the effects of automation from those of the monitor or pharmacokinetic model. [Publication](https://pubmed.ncbi.nlm.nih.gov/21233500/)

- **POCD-ELA: Mahr et al. (2021).** Randomised comparison of closed-loop versus manual BIS-guided propofol/remifentanil TCI in 204 patients aged >50 undergoing major noncardiac surgery. Closed-loop control improved BIS target control and reduced propofol consumption, but no reduction in early postoperative neurocognitive disorders was demonstrated: 13% versus 16%; RR 0.77 (95% CI 0.38–1.57). A close precedent linking EEG–TCI management to cognitive outcomes. [Publication](https://pubmed.ncbi.nlm.nih.gov/33181558/)

- **M-Entropy guidance versus standard practice (2007).** Randomised comparison during propofol–remifentanil anaesthesia. Entropy guidance reduced propofol use, increased remifentanil use, and reduced unwanted patient responses. No significant haemodynamic differences or clinical recovery advantage were demonstrated. [Publication](https://pubmed.ncbi.nlm.nih.gov/17991257/)

- **Entropy versus BIS multicentre study (2012).** Study of 280 patients at seven centres comparing index responses around propofol TCI induction, neuromuscular blockade, and intubation. Relevant to differences between EEG indices and their responses to interference and stimulation; it does not establish comparative effectiveness on major postoperative outcomes. [Publication](https://pubmed.ncbi.nlm.nih.gov/22613640/)

### Anaesthetic depth and postoperative outcomes

- **CODA (2013).** Randomised trial of 921 older patients undergoing major noncardiac surgery, comparing BIS-guided anaesthesia with routine care. BIS guidance reduced delirium incidence (15.6% versus 24.1%) and cognitive dysfunction at three months (10.2% versus 14.7%). [Publication](https://pubmed.ncbi.nlm.nih.gov/23027226/)

- **ENGAGES (2019).** Randomised trial of 1,232 adults aged ≥60 undergoing major surgery, comparing EEG-guided anaesthetic administration with usual care. EEG guidance reduced anaesthetic exposure and EEG suppression, but did not demonstrate a reduction in delirium (26% versus 23%). [Publication](https://pubmed.ncbi.nlm.nih.gov/30721296/)

- **ENGAGES-Canada (2024).** Randomised trial of 1,140 adults aged ≥60 undergoing cardiac surgery, comparing EEG guidance to minimise suppression with usual care. Delirium incidence was essentially identical (18.15% versus 18.10%), despite reduced anaesthetic exposure and EEG suppression. [Publication](https://jamanetwork.com/journals/jama/fullarticle/2819715)

- **BALANCED (2019).** Randomised trial of 6,644 patients comparing light versus deep anaesthesia, targeting BIS 50 versus 35. One-year mortality was 6.5% versus 7.2%; HR 0.88 (95% CI 0.73–1.07). No statistically significant mortality benefit was established. [Publication](https://pubmed.ncbi.nlm.nih.gov/31645286/)

- **BALANCED delirium substudy (2021).** Comparison of BIS targets 50 versus 35, with postoperative delirium assessment and cognitive follow-up. Delirium incidence was lower with the lighter target (19% versus 28%), with less cognitive impairment at one year. This is a substudy of BALANCED, not an independent trial. [Publication](https://pubmed.ncbi.nlm.nih.gov/34465469/)


## Data and approvals

<!-- Sources, approved access/storage, and relevant permissions. No sensitive information or credentials. -->

> Example: Encounter and follow-up records are stored in approved institutional storage. Access is restricted to authorized team members. Ethics and data-access decisions are recorded in `doc/approvals/`. Patient-level data are kept out of version control.

## Setup and workflow

<!-- Specify required software/packages, environment setup, and commands to run the analysis and render manuscripts. -->

> Example: Install R, Quarto, and the dependencies listed in `src/DESCRIPTION`. Once the project scripts and manuscript exist, run `Rscript src/run_analysis.R`, then `quarto render doc/manuscripts/report.qmd`.

## Project layout

| Location | Contents |
| --- | --- |
| `data/` | Non-sensitive metadata: data dictionaries, code lists, and schemas. |
| `doc/notebook.md` | Dated decisions, methods, and analysis notes. |
| `doc/project-planning/` | Concept notes and proposals. |
| `doc/approvals/` | Ethics, consent, data-access, and other permissions. |
| `doc/protocols/` | Protocols, analysis plans, and procedures. |
| `doc/manuscripts/` | Manuscript drafts and submission materials. |
| `results/` | Generated data, tables, and figures that are safe to store here. |
| `src/` | Data-access, cleaning, and analysis code. |
| `CITATION`, `LICENSE` | Citation instructions and reuse terms. |

Use document subfolders only when needed. Small projects can keep documents directly in `doc/`. Keep folder guidance in this README rather than separate folder READMEs.

## Reusable R functions

For functions shared across analyses or Quarto manuscripts, use a local R package in `src/`: metadata and dependencies in `src/DESCRIPTION`, functions in `src/R/`. Give the package a unique project-specific name. It need not be called `src` or published to CRAN.

From the repository root, load functions during development:

```r
pkgload::load_all("src")
```

In a Quarto setup chunk, use `pkgload::load_all("../../src")` for a document in `doc/manuscripts/` with Quarto’s default document-relative working directory. If Quarto is configured to execute from the project root, use `"src"` instead.

For installed use, run `devtools::install("src")`, then `library(yourPackageName)`. Add tests in `src/tests/testthat/` as needed. For a few one-off helpers, use `source()` with the path to the file.

## Working practices

- Keep raw data unchanged in approved storage. Record where the data came from, how to access them, and how they were changed.
- Never commit sensitive data or credentials. Avoid committing large or easily regenerated outputs.
- Use descriptive filenames and `YYYY-MM-DD` dates. Make analyses scriptable and test important steps.
- Track changes in version control and back up through approved locations.

## Licensing

See [`LICENSE`](LICENSE) for the terms. MIT applies to code and project documentation. CC BY 4.0 applies to manuscript/publication prose and original figures, excluding executable code. Datasets are excluded. Third-party terms remain unchanged. Record exceptions and approved data-sharing terms there, and identify publication figures stored in `results/` if they should use CC BY. An open license does not give permission to share sensitive data.
