# PROOFLENS 2.0
### Prove Your Potential.

**An evidence-based project evaluation platform for the next generation of innovators.**

**GAMBIT Hackathon 2026** | HackHub  
**Case:** Talent to University (Талант до вуза)  
**Challenge Focus:** Comparability of Student Achievements  
**Status:** Functional Hackathon MVP

**[Live Demo](https://ailin88.github.io/proflens-2/)**

---

## 1. The Problem

**How can we evaluate student potential beyond certificates and traditional academic indicators?**

Students participate in Olympiads, hackathons, research competitions and startup challenges. However, their achievements are diverse, and evaluating projects consistently can be challenging.

Traditional indicators do not always provide a complete picture of a student's abilities, contribution or project quality.

Three challenges motivated our research:

- Different projects may be evaluated using inconsistent criteria.
- Students may not understand what evidence is needed to demonstrate their work.
- Evaluation results may lack sufficiently detailed feedback.

**Our hypothesis:** A transparent, evidence-oriented evaluation system can make project assessment easier to understand and more consistent.

This hypothesis requires further validation with educational organizations.

## 2. Research & Problem Validation

We conducted exploratory research to understand how students manage their achievements and how educators evaluate applicants.

### Student Survey

**24 anonymous responses**, including **18 students from grades 8–11**, our target age group.

Among those 18 students:

| Finding | Respondents | Percentage |
|---|---:|---:|
| Difficulty finding certificates | 10/18 | 55.6% |
| Difficulty organizing achievements | 8/18 | 44.4% |
| Lost certificates | 7/18 | 38.9% |
| Had to verify achievement authenticity at least once | 11/18 | 61.1% |
| Reported difficulties with additional verification | 4/18 | 22.2% |

*Multiple responses were allowed for the question about difficulties.*

### Educator Interviews

We conducted two exploratory interviews.

**Interview 1 — Achievement Verification**

The educator described reviewing certificates and checking competition results using available verification methods, including QR codes and identifiers.

Significant verification difficulties were not reported.

**Interview 2 — Student Potential Assessment**

The educator explained that tests and certificates alone do not always reflect a student's full potential.

The interview highlighted interest in:

- Preliminary project evaluation before competitions.
- Consistent assessment criteria.
- Transparent feedback for participants.
- Tools that support educators and judges.

### What We Learned

Our initial concept focused on certificate authenticity verification.

However, interviews did not strongly confirm that verification was a major problem for our respondents.

We therefore revised our product hypothesis toward **transparent evaluation and comparison of student projects**.

The student survey primarily supports the need for better achievement organization and presentation. It does not independently prove demand for comparative evaluation.

**Research limitations:** The sample is small and non-random, the interviews are exploratory, and willingness to pay has not yet been established.

## 3. Our Solution

**PROOFLENS 2.0** is a lightweight web application that helps students prepare project submissions and helps experts evaluate them using a shared assessment rubric.

The platform connects three elements:

**Project Evidence → Expert Evaluation → Explainable Results**

Instead of displaying only a final score, PROOFLENS provides a breakdown of the criteria used and allows experts to document their reasoning.

### Key Features

**Student Submission**

Students enter a project title, problem statement, proposed solution and supporting evidence.

**Project Readiness**

The application checks whether required sections are completed and identifies missing information.

**Weighted Expert Evaluation**

Experts manually assign scores while the system calculates weighted totals.

**Evaluation Breakdown**

Each criterion's contribution to the final score is displayed.

**Saved Projects**

Project information, expert scores and comments are saved in the browser.

**Project Comparison**

Two saved projects can be compared using the same evaluation rubric.

**Expert Comments**

Experts provide explanations that are stored and displayed alongside assessment results.

**Project Management**

Users can remove saved projects they no longer need.

## 4. Evaluation Methodology

The current MVP uses the following demonstration rubric:

| Evaluation Criterion | Weight |
|---|---:|
| Problem Relevance | 20% |
| Innovation | 25% |
| Feasibility | 25% |
| Evidence & Results | 30% |
| **Total** | **100%** |

Experts assign scores from 0 to 10.

The final score is calculated using weighted arithmetic:

**Final Score = Σ (Criterion Score ÷ 10 × Criterion Weight)**

### Example

| Criterion | Project A | Project B |
|---|---:|---:|
| Problem Relevance | 8 | 9 |
| Innovation | 7 | 8 |
| Feasibility | 6 | 7 |
| Evidence & Results | 9 | 6 |
| **Total** | **75.5/100** | **73.5/100** |

**Difference: 2.0 points**

The comparison makes it possible to identify which assessment criteria contributed to the difference.

These are illustrative expert scores, not AI-generated assessments or official GAMBIT jury scores.

## 5. Technology & Architecture

### Technology Stack

- **HTML5** — application structure.
- **CSS3** — visual interface and layout.
- **JavaScript** — interaction, validation, calculations and comparison.
- **localStorage** — browser-based project persistence.
- **GitHub** — source code and version history.
- **GitHub Pages** — static website hosting.

### Application Workflow

1. Student enters project information.
2. The application checks required fields.
3. An expert reviews the submission.
4. The expert assigns criterion scores and writes feedback.
5. JavaScript calculates the weighted result.
6. The project and evaluation can be saved locally.
7. Two saved projects can be compared using the same rubric.

### Architecture

The MVP is implemented as a client-side web application.

No backend, external database, payment integration or AI scoring API is required.

This architecture was selected to deliver a functional prototype within hackathon constraints.

## 6. Try the Live MVP

**Live Website:**  
https://ailin88.github.io/proflens-2/

### Demo Instructions

1. Open the live website.
2. Enter a demonstration project in **Student Submission**.
3. Click **Отправить проект**.
4. Review the **Project Readiness** result.
5. Assign scores in **Expert Evaluation**.
6. Click **Рассчитать оценку** to see the weighted breakdown.
7. Write an **Expert Comment**.
8. Save the project using **Сохранить проект**.
9. Repeat with a second demonstration project.
10. Open **Project Comparison** to compare results and expert comments.

To run locally, download the repository and open `index.html` in a modern web browser.

No installation is required.

**Note:** The live site opens with an empty project list for new visitors. Saved projects are specific to each browser.

## 7. Target Users & Business Model

### Primary Users

Students in grades 8–11 preparing projects for educational programs, competitions and innovation challenges.

### Potential Paying Customers

- Educational competition organizers.
- Scholarship and grant programs.
- Organizations that evaluate student projects.
- Educational institutions running project-based selection processes.

### Proposed Revenue Model

**B2B — Business-to-Business**

Basic student-facing features could remain free.

Organizations could pay for access to structured evaluation workflows, project comparison and feedback tools.

**Initial pricing hypothesis:** 20,000 KZT per small evaluation campaign.

This price has not been validated through sales or confirmed customer commitments.

### Value Proposition

For students: clearer expectations and more understandable feedback.

For organizers: a structured workflow for comparing projects using consistent criteria.

For experts: transparent calculations and documented assessment comments.

## 8. Market Positioning

Existing alternatives include manual evaluation through spreadsheets and forms, as well as established competition management platforms such as Evalato and Award Force.

Our proposed differentiation is a focused, lightweight experience for school-level project assessment, preparation and explanatory feedback.

This positioning is a hypothesis to validate through competitor analysis and customer testing. We do not claim that these features are unavailable elsewhere.

## 9. Go-to-Market Strategy

### Initial Goal: 100 Student Users

A proposed acquisition plan:

| Channel | Target |
|---|---:|
| First partner school | 30 students |
| Second partner school | 30 students |
| Partner project competition | 40 students |
| **Total target** | **100 students** |

These numbers are acquisition targets, not existing partnerships or registered users.

### First 30 Days

**Week 1:** Conduct a usability pilot with students and collect feedback.

**Week 2:** Test evaluation workflows with educators or competition organizers.

**Week 3:** Improve the MVP based on testing and investigate pilot pricing.

**Week 4:** Approach potential institutional customers and evaluate readiness for a paid pilot.

The key business milestone is obtaining a genuine pilot commitment, rather than assuming demand.

## 10. Responsible Evaluation & Limitations

PROOFLENS is a decision-support prototype, not an autonomous judge of student talent.

Current limitations include:

- Scores are assigned by humans, not AI.
- The system checks field completion but does not authenticate project claims or documents.
- Submitted evidence is not automatically validated.
- localStorage does not synchronize information between devices.
- No secure authentication or server-side access controls are implemented.
- A common rubric does not automatically eliminate subjective bias.
- Evaluation consistency and commercial demand have not yet been validated.

**Privacy:** The MVP should be demonstrated using fictional projects and test data, not sensitive student information.

The current version is not suitable for confidential or high-stakes real-world admissions decisions.

## 11. Development Roadmap

Potential next steps:

- Configurable rubrics for different competition types.
- Criterion-specific feedback linked to supporting evidence.
- Blind review options to reduce exposure to identifying details.
- Secure accounts and organization-controlled access.
- Shared database and multi-user collaboration.
- Usability testing and evaluation consistency studies.
- Optional AI-assisted feedback, subject to careful validation and human oversight.

These are **planned improvements**, not features already implemented in the MVP.

## 12. AI Tools Disclosure

**ChatGPT (OpenAI)** assisted with:

- Product brainstorming and concept development.
- Code drafting and JavaScript debugging.
- Technical explanations and development guidance.
- README documentation.
- Research synthesis and business-model structuring.

The team is responsible for reviewing the outputs, testing the functionality and accurately describing the implementation.

No autonomous AI scoring model is currently integrated.

## 13. Team & Contributions

**GAMBIT Hackathon 2026 — Team of Four**

Add each participant's real name and actual contribution before final submission.

- Product coordination and research — [Name / confirmed contribution]
- MVP development — [Name / confirmed contribution]
- Business analysis — [Name / confirmed contribution]
- Presentation and testing — [Name / confirmed contribution]

## 14. Project Vision

Our long-term vision is to make student project evaluation more transparent, explainable and accessible, especially for students seeking educational opportunities beyond their immediate communities.

**PROOFLENS — Prove Your Potential.**

*Built as a functional MVP for GAMBIT Hackathon 2026.*
