# Data Engineering and Analytics Portfolio Website Plan

## 1. Goal

Create a professional portfolio website for Mashood Ogunbiyi that positions him primarily as a data engineer while also showing his ability to work as a data analyst. The site should connect his technical portfolio with his aerospace engineering background and experience communicating technical information.

The site should make these points clear within the first few seconds:

- Mashood is a Manchester-based data engineer.
- He builds automated data pipelines, cloud data platforms, and analytics solutions.
- He can also clean, analyse, and visualise data as a data analyst.
- His main tools include Python, SQL, PySpark, Databricks, Microsoft Azure, AWS, Power BI, and Tableau.
- Visitors can quickly inspect his projects, download his CV, and contact him.

## 2. Target Audience

- Recruiters hiring junior or early-career data engineers
- Recruiters hiring data analysts with strong engineering skills
- Engineering managers and technical interviewers
- Potential collaborators and clients

## 3. Core Message

Suggested headline:

> Data Engineer building reliable cloud pipelines and analytics solutions.

Suggested introduction:

> I am a Manchester-based data engineer with experience building automated ETL pipelines, validating complex datasets, and creating analytics solutions with Python, SQL, Microsoft Azure, AWS, and business intelligence tools. I can also work as a data analyst, turning operational data into clear reports, dashboards, and practical insights.

## 4. Website Structure

Build a responsive single-page website with the following sections.

### Navigation

- Home
- About
- Skills
- Projects
- Experience
- Contact
- Download CV button

Keep the navigation visible while scrolling and collapse it into a mobile menu on smaller screens.

### Hero

Include:

- Name: Mashood Ogunbiyi
- Role: Data Engineer
- Short value statement
- Primary button: View Projects
- Secondary button: Download CV
- GitHub: github.com/mashoodogunbiyi
- LinkedIn: linkedin.com/in/ogunbiyi-mashood

Use a subtle technical visual that connects data sources, ingestion, transformation, storage, validation, and reporting. It should support the content without distracting from it.

### About

Write a short professional summary that connects:

- Data engineering experience at Dream Solution Xtra
- Data analysis experience at the Nigeria Civil Aviation Authority
- Practical work with ETL pipelines, SQL, Python, data validation, cloud platforms, and business intelligence
- MSc Aerospace Engineering from the University of Salford
- BEng Aeronautical and Astronautical Engineering from Kwara State University
- Current IT support and mentoring experience and the ability to explain technical ideas clearly

Keep this section to two short paragraphs.

### Skills

Group skills instead of displaying one long list:

- Programming and databases: Python, Pandas, NumPy, SQL, MySQL, PostgreSQL, data cleaning, transformation, validation, and data modelling
- Data engineering and cloud: ETL/ELT pipelines, PySpark, Databricks, Apache Airflow, Azure Data Factory, Azure Synapse Analytics, Azure Data Lake Storage, AWS S3, Glue, Lambda, Redshift, and IAM
- Infrastructure and delivery: Docker, Terraform, Git, GitHub, GitHub Actions, and GitLab CI
- Analytics and development: Power BI, DAX, Tableau, Excel, HTML, CSS, and JavaScript
- Professional: technical documentation, stakeholder communication, requirements gathering, root-cause analysis, training, mentoring, prioritisation, and cross-functional collaboration

Avoid skill percentages or self-rated progress bars. Use clear labels or compact cards.

### Featured Projects

Feature these three projects prominently.

#### Biomedical Data Lake and Research Query Platform

- Problem: Organise structured and semi-structured biomedical data for research analysis.
- Approach: AWS S3, Glue, Redshift, Python ETL, SQL data models, validation, and FastAPI.
- Emphasis: Scalable architecture, consistent data, and accessible analytics queries.
- Add later: Architecture diagram, repository link, screenshots, sample API response, pipeline tests, and measurable results.

#### Secure Healthcare Data Pipeline with Governance and Auditing

- Problem: Process sensitive data while protecting access, integrity, and traceability.
- Approach: AWS S3, Lambda, SQL, IAM controls, encryption, validation, monitoring, and anonymisation.
- Emphasis: Security, governance, pipeline reliability, and audit visibility.
- Add later: Security-flow diagram, repository link, synthetic sample data, audit-log example, and test results.

#### SQL Data Cleaning and Exploratory Data Analysis

- Dataset: Layoffs dataset from Kaggle.
- Problem: Convert inconsistent raw records into an analysis-ready dataset and identify workforce-reduction patterns.
- Approach: MySQL staging tables, common table expressions, `ROW_NUMBER()`, joins, aggregations, window functions, `DENSE_RANK()`, and rolling totals.
- Emphasis: Preserving source data, removing duplicates, standardising values, validating transformations, and producing reproducible analysis.
- Add later: GitHub repository link, data-cleaning flow, before-and-after examples, key queries, visual findings, and a clear data-source citation.

Each project card should show the problem, solution, technology stack, outcome, and links. Give the data engineering projects the most visual prominence, while the SQL project demonstrates complementary data analysis capability. Create a dedicated project-detail view later if the case studies become too long for the home page.

### Experience

Use a simple timeline and prioritise transferable or technical achievements:

- Customer Service Advisor, Hinduja Global Solutions - October 2025 to present
- IT Support and Mentor, Sovereign House GH - November 2024 to present
- Data Engineer, Dream Solution Xtra - August 2023 to August 2024
- Data Analyst, Nigeria Civil Aviation Authority - January 2023 to January 2024

Give the Data Engineer and Data Analyst roles the most detail. Highlight Azure ETL pipelines, Python and SQL automation, data-quality checks, Power BI and DAX, aviation data analysis, KPI reporting, stakeholder requirements, and technical documentation. Summarise the current roles around technical troubleshooting, accurate records, GDPR-aware service, communication, training, and mentoring.

### Education

- MSc Aerospace Engineering, University of Salford - 2025
- BEng Aeronautical and Astronautical Engineering, Kwara State University - 2022

Briefly connect the degrees to analytical thinking, computation, complex systems, and engineering design.

### Contact

Include:

- A short invitation to discuss data engineering or data analytics opportunities
- Email: Mashoodogunbiyi@gmail.com
- GitHub: github.com/mashoodogunbiyi
- LinkedIn: linkedin.com/in/ogunbiyi-mashood
- Optional contact form with name, email, and message fields

Do not publish the full home address or telephone number by default. List the location as Manchester, UK.

## 5. Design Direction

- Style: Modern, technical, and uncluttered
- Layout: Generous spacing, clear hierarchy, and readable project cards
- Colour palette: Dark navy or charcoal with a restrained blue, cyan, or green accent
- Typography: Accessible sans-serif body text with a strong display heading
- Visual language: Subtle pipeline, database, cloud, warehouse, and data-flow motifs
- Accessibility: Keyboard navigation, visible focus states, semantic HTML, sufficient contrast, useful alt text, and reduced-motion support
- Responsive behaviour: Design for mobile, tablet, and desktop

## 6. Recommended Technical Approach

Start with a small, maintainable stack:

- React with Vite for the interface
- CSS modules or plain CSS for styling
- Reusable data-driven components for projects, skills, and experience
- Static deployment on GitHub Pages, Netlify, or Vercel
- GitHub Actions for automated checks and deployment

If a framework is unnecessary for the first version, semantic HTML, CSS, and JavaScript are also sufficient. Choose one approach before implementation and document it in the README.

## 7. Content and Assets Needed

- Professional profile photo or a deliberate text-only hero
- Public-safe copy of the CV for download
- Repository URLs for the three featured projects
- Project screenshots, data-flow diagrams, architecture diagrams, SQL examples, and dashboard images
- Measurable project results where available, such as dataset size, rows processed, records cleaned, validation coverage, pipeline duration, query performance, or dashboard outcomes

Never expose credentials, private or confidential datasets, cloud account details, API keys, personal addresses, government-service records, or identifiable operational data.

## 8. Implementation Phases

### Phase 1 - Foundation

- Select the stack and initialise the application
- Define colours, typography, spacing, and responsive breakpoints
- Create the page shell, navigation, footer, and reusable section layout
- Add basic metadata, favicon, and page title

### Phase 2 - Core Content

- Build the hero and About sections
- Add grouped data engineering, cloud, analytics, development, and professional skills
- Create reusable project cards for the three featured projects
- Add the experience timeline and education section
- Add contact links and the CV download

### Phase 3 - Project Evidence

- Add repository links and screenshots
- Create workflow or architecture diagrams for each project
- Rewrite each project as a short case study: problem, decisions, implementation, challenges, and outcome
- Add measurable results and testing evidence

### Phase 4 - Quality and Launch

- Test on mobile, tablet, and desktop
- Test keyboard navigation and screen-reader structure
- Optimise images and page-loading performance
- Check every external link and contact action
- Add Open Graph metadata and a social preview image
- Run accessibility, performance, and SEO checks
- Deploy and verify the production site

## 9. Definition of Done

The first release is complete when:

- All planned sections are present and responsive.
- The three data engineering and analytics projects are easy to find and understand.
- The site includes working GitHub, LinkedIn, email, and CV links.
- No private or sensitive information is exposed.
- Navigation works with a keyboard and the page has good colour contrast.
- The site has no broken links or obvious layout issues.
- The deployed version loads quickly and works on current mobile and desktop browsers.

## 10. Immediate Next Steps

1. Confirm the implementation stack.
2. Decide whether to use a profile photo or a technical visual in the hero.
3. Use Data Engineer as the primary job title in the hero, page title, metadata, and downloadable CV.
4. Prepare public repositories, screenshots, diagrams, datasets, and measurable results for the three featured projects.
5. Create a privacy-safe downloadable CV focused on data engineering and analytics, without a public telephone number unless it is intentionally included.
6. Build the Phase 1 foundation, then add the core content.
