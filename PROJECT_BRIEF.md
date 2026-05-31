# Project Brief: Levi Premer Personal Website

## Purpose

Build a modern personal academic/professional website for Levi Premer, a final-year PhD candidate in Mechanical Engineering at Purdue University. The website should present Levi as a strong candidate for industry research, deep-tech/startup, national lab, and academic/postdoctoral roles.

The site should go beyond a traditional academic CV page. It should clearly communicate technical expertise, real-world impact, publications, projects, and professional direction in a polished and accessible way.

## Primary Audience

The website should appeal to:

- Industry R&D hiring managers
- Deep-tech and climate-tech startup founders
- National lab researchers
- Academic faculty and postdoctoral search committees
- Conference/workshop organizers
- Potential collaborators

## Desired Impression

The site should make Levi appear:

- Technically rigorous
- Practical and impact-oriented
- Strong in control systems, energy systems, and buildings
- Comfortable translating research into deployable systems
- Entrepreneurial and capable of working across academia, industry, and startups

## Core Identity

Levi Premer is a PhD candidate in Mechanical Engineering at Purdue University, affiliated with Ray W. Herrick Laboratories.

His work focuses on practical energy management systems for cost-effective and grid-flexible residential electrification.

Primary technical areas include:

- Model predictive control
- Supervisory control
- Data-driven control
- Residential electrification
- Grid-interactive efficient buildings
- Heat pump water heaters
- HVAC systems
- Electric vehicles
- Home energy management systems
- Whole-home current limiting
- Demand response and load flexibility

## Suggested Tagline Options

Use or adapt one of these:

1. Practical control systems for grid-flexible residential electrification.
2. Building energy systems that make electrification cheaper, smarter, and more grid-responsive.
3. Control, optimization, and field deployment for the next generation of electrified homes.
4. Turning residential electrification into a controllable, grid-flexible resource.

## Website Goals

The website should:

1. Explain Levi’s research in a clear and compelling way.
2. Highlight field-tested and practically relevant projects.
3. Show technical depth without overwhelming non-specialists.
4. Make publications, CV, and contact information easy to find.
5. Support future additions such as interactive demos, project visualizations, and downloadable research summaries.
6. Be easy to maintain and deploy through GitHub Pages.

## Design Direction

The website should feel:

- Modern
- Professional
- Clean
- Technically polished
- Credible but not overly academic
- More like a research engineer / startup technical founder profile than a generic university webpage

Avoid:

- Overly plain academic templates
- Excessive text density
- Generic stock imagery
- Flashy design that distracts from credibility
- Overuse of buzzwords

Use:

- Clear section hierarchy
- Concise project summaries
- Strong visual spacing
- Cards for projects
- Simple icons or diagrams where helpful
- Mobile-responsive layout
- A polished homepage hero section
- Easy navigation

## Recommended Site Structure

### Home

Include:

- Name: Levi Premer
- Title: PhD Candidate in Mechanical Engineering, Purdue University
- Short tagline
- Brief research identity statement
- Primary call-to-action buttons:
  - View Projects
  - View CV
  - Contact

Potential hero text:

> I develop practical control and optimization methods for electrified homes, with a focus on reducing infrastructure costs, improving grid flexibility, and maintaining occupant comfort.

### About

Summarize Levi’s background:

- PhD candidate in Mechanical Engineering at Purdue University
- Researcher at Ray W. Herrick Laboratories
- Works on supervisory control and optimization for residential electrification
- Interested in translating research into practical systems for homes, utilities, and energy technology companies

Mention that his work combines:

- Modeling
- Optimization
- Experimental deployment
- Field data
- Building systems
- Grid-interactive control

### Research

Organize around 3–5 research themes:

#### 1. Cost-Effective Residential Electrification

Focus on avoiding unnecessary electrical service and panel upgrades through intelligent load coordination.

Key ideas:

- Whole-home current limiting
- Coordination of HVAC, water heating, EV charging, and flexible loads
- Maintaining comfort and service quality while respecting current constraints

#### 2. Predictive Control for Heat Pump Water Heaters

Focus on MPC and minimal-sensing control for HPWHs.

Key ideas:

- Energy and cost savings
- Time-varying electricity prices
- Hot water comfort constraints
- Field testing
- Minimal sensing and practical deployment

#### 3. Supervisory HVAC Control

Focus on comfort-aware and grid-aware HVAC supervisory control.

Key ideas:

- Zone comfort
- Occupancy-aware control
- Data-driven models
- Model predictive control
- Field demonstrations

#### 4. Grid-Flexible Homes

Focus on enabling homes to respond to utility needs and dynamic grid conditions.

Key ideas:

- Demand response
- Dynamic power limits
- Home energy management
- EVs, batteries, PV, and water heating as controllable resources

#### 5. DC Nanogrids and Vehicle-to-Home Systems

Focus on experimental infrastructure and future home energy architectures.

Key ideas:

- DC nanogrid research
- EV integration
- Vehicle-to-home power
- Hardware-in-the-loop and field testing

### Projects

Create project cards for the following:

#### Heat Pump Water Heater Predictive Control

Short description:

> Developed and field-tested model predictive control strategies for heat pump water heaters to reduce energy cost while maintaining hot water availability.

Emphasize:

- MPC
- Field testing
- Minimal sensing
- Energy/cost savings
- Practical deployment

#### Whole-Home Current Limiting

Short description:

> Designed supervisory control strategies that coordinate major residential electric loads to keep total home current below panel limits, helping avoid costly electrical service upgrades.

Emphasize:

- Residential electrification
- Panel upgrade avoidance
- Current constraints
- HVAC, HPWH, EV, and appliance coordination

#### Supervisory HVAC Control

Short description:

> Developed comfort-aware HVAC supervisory control methods that use predictive models and occupant preferences to coordinate energy use and comfort.

Emphasize:

- MPC
- Occupant comfort
- Zone control
- Weather and occupancy effects

#### DC Nanogrid and EV Integration

Short description:

> Contributed to experimental home energy infrastructure involving DC nanogrids, EV charging, vehicle-to-home systems, and controllable residential loads.

Emphasize:

- Hardware integration
- EVs
- DC systems
- Grid-flexibility

#### Data-Driven Control and Robustness

Short description:

> Studied data-driven predictive control methods and robustness challenges for building energy systems under limited data and uncertain model quality.

Emphasize:

- Data-driven control
- Robustness
- Monte Carlo analysis
- Predictor comparison

### Publications

Create a publications page or section with a clean list format.

Each publication should include:

- Title
- Authors
- Venue
- Year
- Links, if available:
  - PDF
  - DOI
  - Code
  - Project page

Use placeholder entries until final publication data is added.

### CV

Include a dedicated CV page or section with:

- Education
- Research experience
- Publications
- Awards
- Teaching/mentoring
- Conference presentations
- Technical skills
- Service/reviewing

Include a button to download a PDF CV.

### Contact

Include:

- Email
- Google Scholar
- LinkedIn
- GitHub
- Purdue profile, if applicable

Use placeholders where needed.

## Technical Requirements

The website should be:

- GitHub Pages compatible
- Static
- Easy to edit
- Mobile responsive
- Fast loading
- Accessible
- Search-engine friendly

Preferred implementation options:

1. Simple HTML/CSS/JavaScript
2. Jekyll-compatible static site
3. React/Vite static export, only if deployment remains simple

Avoid unnecessary complexity unless it clearly improves maintainability or presentation.

## Initial Build Request for Codex

Use this prompt after adding this file:

> Read PROJECT_BRIEF.md and build the first version of my personal academic/professional website. Make it GitHub Pages compatible, mobile responsive, and easy to maintain. Start with a clean homepage, research section, project cards, publications placeholder, CV placeholder, and contact section. Use professional styling suitable for a final-year PhD candidate targeting industry research, deep-tech startups, national labs, and academia.

## Content Tone

The writing should be:

- Clear
- Confident
- Professional
- Concise
- Technically credible
- Accessible to non-specialists

Avoid phrases that sound exaggerated, vague, or overly promotional.

Prefer:

> I develop practical control and optimization methods for electrified residential energy systems.

Instead of:

> I am revolutionizing the future of smart homes through cutting-edge AI-powered energy innovation.

## Future Enhancements

Leave room for future additions such as:

- Interactive demos
- Project-specific pages
- Simulation visualizations
- Downloadable research summaries
- Embedded publication figures
- Code repositories
- Blog or technical notes
- Media/news section