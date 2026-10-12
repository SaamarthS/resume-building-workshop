# Google AI Studio: Live Demonstration Examples

> **Facilitator Resource:** Use these side-by-side examples during Minutes 48–53 to illustrate how rough student project notes are converted into high-impact, honest bullets.

---

## Example 1: Full-Stack Web / Backend (Official Workshop Example)

### Raw Student Input
```text
Project: College Event Management System
I worked on the backend.
Used Node.js, Express and MongoDB.
Built registration APIs.
Added an admin dashboard.
Worked with two teammates.
No real performance metric.
Target role: Software Engineering / Backend Intern
```

### Generated Output

#### Version A (Concise)
* Developed RESTful backend APIs in Node.js and Express for an event management system, handling participant registration and administrative dashboards.

#### Version B (Technical)
* Engineered modular REST endpoints using Express and MongoDB schemas to process user registrations, role-based admin access, and event status updates.

#### Version C (Impact-focused)
* Built and deployed a collaborative event management platform with a 3-member team, replacing manual spreadsheet tracking with automated registration APIs.

#### Missing Information Identified by AI
* *“What authentication mechanism was used (e.g., JWT, sessions)? How were errors handled or inputs validated?”*

---

## Example 2: Machine Learning / Python Project (John Doe Flaw Remedy)

### Raw Student Input
```text
Project: Disease Prediction Model
Used Python, Scikit-learn, Pandas.
Dataset: Public Kaggle diabetes dataset (768 records).
Trained Logistic Regression and Random Forest models.
Evaluated using 5-fold cross-validation, reached 78% accuracy.
Saved model pipeline using Joblib.
Personal project, no live deployment.
Target role: Machine Learning / Data Science Intern
```

### Generated Output

#### Version A (Concise)
* Built a diabetes prediction pipeline in Python using Scikit-learn, achieving 78% classification accuracy across cross-validated clinical metrics.

#### Version B (Technical)
* Preprocessed and analyzed clinical tabular data using Pandas; benchmarked Logistic Regression and Random Forest classifiers using 5-fold cross-validation.

#### Version C (Outcome-focused)
* Developed an end-to-end classification pipeline for disease risk screening, persisting trained estimator artifacts with Joblib for local inference.

#### Missing Information Identified by AI
* *“Did you perform feature scaling or handle class imbalance? Which metric was prioritized: recall, precision, or F1-score?”*

---

## Facilitator Teaching Points

1. **Highlight the Contrast:** Point out that neither output claims *"predicted disease for 5,000 hospital patients"* because that would be a lie. Instead, it highlights real engineering decisions (cross-validation, preprocessing, API design).
2. **Encourage Iteration:** The "Missing information" feedback prompt teaches students to reflect on what technical depth they omitted.
