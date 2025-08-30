# GovConnect: Empowering Community Engagement in Government Projects

GovConnect is a platform designed to bridge the gap between government and community members on public projects. It aims to increase transparency, foster meaningful feedback, and empower citizens to have a genuine voice in the development of their communities.

## Core Features

### For the Government

- **Project Management Dashboard:** A centralized interface to upload, manage, and display project data.
- **AI-Powered Feedback Analysis:**
    - Automatically summarize and categorize community feedback from various sources (comments, polls, suggestions).
    - Generate concise, easy-to-understand reports highlighting key concerns, positive sentiments, and emerging themes.
- **Document Summarization:**
    - Use AI to create user-friendly summaries of complex government documents (e.g., environmental impact statements, budget proposals).
    - Make critical information accessible to a wider audience.
- **Sustainability and Social Impact Reporting:**
    - Visualize key sustainability metrics (e.g., carbon footprint, water usage, waste reduction) for each project.
    - Show how these metrics will influence different demographic groups (e.g., employment opportunities for youth, impact on local businesses).

### For the Community Member

- **Interactive Project Map:**
    - An intuitive map-based interface to discover projects based on location.
    - Filter projects by status (proposed, in development, completed) and category (transport, housing, green spaces).
- **Direct Feedback and Voting:**
    - Enable users to vote on project proposals, providing a direct measure of public support.
    - A dedicated section for structured feedback and open comments.
- **Sustainability and Opportunity Cost:**
    - Clear and accessible display of project sustainability metrics.
    - Visualizations and explanations of the opportunity cost, such as what other projects or initiatives the funds could have supported.
- **Project Suggestions:**
    - A dedicated form for community members to propose new projects and ideas.
    - Allow other users to "upvote" these suggestions, helping to surface popular ideas.

## To run
1. Make sure you have python (>v3.12) and npm (>v22) installed
2. Activate the virtual environment and navigate to the correct directory
```
cd react-with-flask
cd api
source venv/bin/activate
```
3. Install python dependencies
```
pip install -r requirements.txt
cd ..
```
3. Run the backend
`npm run api`
4. Run the frontend
`npm run dev`
5. Go to `http:localhost:5173`