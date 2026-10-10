# Data Engineering Portfolio Website Plan

## 1. Goal

Create a professional portfolio website for Mashood Ogunbiyi that presents his data engineering skills, selected projects, relevant experience, and engineering background to recruiters and hiring managers.

The site should make these points clear within the first few seconds:

- Mashood is a data engineer based in Manchester, UK.
- He builds reliable cloud data pipelines and analytics platforms.
- His main tools include Python, SQL, AWS, Airflow, PySpark, Docker, Terraform, and Power BI.
- Visitors can quickly inspect his projects, download his CV, and contact him.

## 2. Target Audience

- Recruiters hiring junior or early-career data engineers
- Engineering managers and technical interviewers
- Potential collaborators and clients

## 3. Core Message

Suggested headline:

> Data Engineer building reliable cloud pipelines and analytics platforms.

Suggested introduction:

> I am a Manchester-based data engineer with experience building ETL pipelines, working with Python and SQL, and using AWS services to organise, process, and validate data. My engineering background brings structured problem-solving and systems thinking to every project.

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
- Links for GitHub and LinkedIn once supplied

Use a subtle data-themed visual, such as connected pipeline nodes or a simple flow from source to transformation to warehouse. It should support the content without distracting from it.

### About

Write a short professional summary that connects:

- Data engineering experience at DreamSolutionX
- Practical work with pipelines, SQL, Python, validation, and relational databases
- MSc Aerospace Engineering from the University of Salford
- BEng Aeronautical and Astronautical Engineering from Kwara State University
- Current IT teaching experience and ability to explain technical ideas clearly

Keep this section to two short paragraphs.

### Skills

Group skills instead of displaying one long list:

- Languages and databases: Python, SQL, MySQL, PostgreSQL
- Data engineering: ETL/ELT, data modelling, data warehousing, data quality, PySpark, Apache Airflow
- Cloud and infrastructure: AWS S3, Glue, Lambda, Redshift, IAM, Terraform, Docker
- Delivery and visualisation: Git, GitHub Actions, GitLab CI, Power BI
- Security and governance: access control, encryption, anonymisation, validation, auditing

Avoid skill percentages or self-rated progress bars. Use clear labels or compact cards.

### Featured Projects

Feature these three projects prominently.

#### Biomedical Data Lake and Research Query Platform

- Problem: Organise structured and semi-structured biomedical data for research analysis.
- Approach: AWS S3, Glue, Redshift, Python ETL, SQL models, validation, and FastAPI.
- Emphasis: Scalable architecture, consistent data, and accessible analytics queries.
- Add later: Architecture diagram, repository link, screenshots, sample API response, and measurable results.

#### Secure Healthcare Data Pipeline with Governance and Auditing

- Problem: Process sensitive healthcare data while protecting access and integrity.
- Approach: AWS S3, Lambda, SQL, IAM controls, encryption, validation, monitoring, and anonymisation.
- Emphasis: Security, governance, reliability, and audit visibility.
- Add later: Security-flow diagram, repository link, sample audit log, and test results.

#### Real-Time Data Streaming Pipeline

- Problem: Process and visualise a continuous stream of simulated health data.
- Approach: Kafka or Kinesis concepts, event-driven transformations, S3/database storage, and Power BI or Streamlit.
- Emphasis: Streaming design, aggregation, performance, and live insights.
- Add later: Pipeline diagram, repository link, dashboard screenshot, event volume, and latency measurements.

Each project card should show the problem, solution, technology stack, outcome, and links. Create a dedicated project-detail view later if the case studies become too long for the home page.

### Experience

Use a simple timeline and prioritise transferable or technical achievements:

- Customer Service Advisor, Hinduja Global Solutions - October 2025 to present
- IT Educator (Volunteer), Sovereign House GH - November 2024 to present
- Cover Supervisor, Connex Education Academy - February 2025 to October 2025
- Data Engineer, DreamSolutionX - January 2023 to January 2024

Give the Data Engineer role the most detail. Summarise the other roles around problem-solving, communication, accurate records, technical support, teaching, and responsibility.

### Education

- MSc Aerospace Engineering, University of Salford - 2025
- BEng Aeronautical and Astronautical Engineering, Kwara State University - 2022

Briefly connect the degrees to analytical thinking, computation, complex systems, and engineering design.

### Contact

Include:

- A short invitation to discuss data engineering opportunities
- Professional email address
- GitHub and LinkedIn links once supplied
- Optional contact form with name, email, and message fields

Do not publish the full home address or telephone number by default. List the location as Manchester, UK.

## 5. Design Direction

- Style: Modern, technical, and uncluttered
- Layout: Generous spacing, clear hierarchy, and readable project cards
- Colour palette: Dark navy or charcoal with a restrained blue, cyan, or green accent
- Typography: Accessible sans-serif body text with a strong display heading
- Visual language: Subtle pipeline, database, cloud, and data-flow motifs
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
- Public GitHub profile URL
- LinkedIn profile URL
- Public-safe copy of the CV for download
- Repository URLs for the three featured projects
- Project screenshots or architecture diagrams
- Measurable project results where available, such as rows processed, pipeline duration, validation coverage, or streaming latency

Never expose credentials, private datasets, AWS account details, API keys, personal addresses, or sensitive healthcare information.

## 8. Implementation Phases

### Phase 1 - Foundation

- Select the stack and initialise the application
- Define colours, typography, spacing, and responsive breakpoints
- Create the page shell, navigation, footer, and reusable section layout
- Add basic metadata, favicon, and page title

### Phase 2 - Core Content

- Build the hero and About sections
- Add grouped skills
- Create reusable project cards for the three featured projects
- Add the experience timeline and education section
- Add contact links and the CV download

### Phase 3 - Project Evidence

- Add repository links and screenshots
- Create architecture diagrams for each project
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
- The three data engineering projects are easy to find and understand.
- The site includes working GitHub, LinkedIn, email, and CV links.
- No private or sensitive information is exposed.
- Navigation works with a keyboard and the page has good colour contrast.
- The site has no broken links or obvious layout issues.
- The deployed version loads quickly and works on current mobile and desktop browsers.

## 10. Immediate Next Steps

1. Confirm the implementation stack.
2. Supply GitHub and LinkedIn profile links.
3. Decide whether to use a profile photo or a text-and-data visual in the hero.
4. Prepare public repositories and screenshots for the three featured projects.
5. Create a privacy-safe downloadable CV.
6. Build the Phase 1 foundation, then add the core content.
