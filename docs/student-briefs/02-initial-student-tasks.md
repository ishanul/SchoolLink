# Initial Student Tasks

These tasks are for one student group of five members.

The product name is intentionally open. The group must propose a suitable name as part of the discovery work.

## Suggested Team Split

- Student 1: Problem research and user pain points
- Student 2: User roles, permissions, and user stories
- Student 3: Functional and non-functional requirements
- Student 4: Data model and user journeys
- Student 5: Wireframes, presentation, and product naming

Students should still review each other's work. The final submission should feel like one coherent product proposal, not five disconnected documents.

## Task 1: Understand the Problem

Each group must study the problem before proposing a solution.

Prepare a short write-up covering:

- How schools currently communicate with parents in Sri Lanka
- Problems with WhatsApp groups, paper notices, phone calls, and manual registers
- Problems faced by parents
- Problems faced by teachers
- Problems faced by school administrators
- Problems faced by students

Expected output:

- 1-2 pages
- At least 5 key pain points
- At least 3 real-world examples or scenarios

## Task 2: Propose a Product Name

The project does not have a final name yet.

Propose 3 possible names and select 1 recommended name.

For each name, explain:

- Meaning
- Target audience fit
- Sri Lankan context fit
- Whether it sounds suitable for schools
- Any possible weakness or confusion

Expected output:

- 3 name options
- 1 recommended name
- Short justification

Avoid choosing a name only because it sounds modern. The name should make sense to schools, teachers, parents, and students.

## Task 3: Define the MVP

Decide what the first version of the platform should include.

Your MVP must be realistic for a student team to build.

Consider:

- Announcements
- Assignment tracking
- Digital consent forms
- Smart notifications
- Dashboards
- Calendar/events
- Student access
- Multilingual support

Expected output:

- MVP feature list
- Out-of-scope feature list
- Short reason for each decision

## Task 4: Identify User Roles and Permissions

Define what each user can and cannot do.

Required roles:

- School administrator
- Teacher
- Parent or guardian
- Student, optional

Expected output:

- Role descriptions
- Permission matrix
- At least 5 permissions per main role

Example questions:

- Can a teacher send school-wide announcements?
- Can a parent see another parent's information?
- Can a student submit assignment status?
- Can an admin edit all users?

## Task 5: Write User Stories

Write user stories for the main workflows.

Required minimum:

- 5 parent user stories
- 5 teacher user stories
- 5 admin user stories
- 3 student user stories, if student access is included

Use this format:

```text
As a [user role],
I want to [perform an action],
so that [benefit or reason].
```

Example:

```text
As a parent,
I want to see all upcoming assignments for my child,
so that I can remind them before the due date.
```

## Task 6: Create Main User Journeys

Draw or describe the key flows.

Required journeys:

- Parent views unread announcements
- Teacher creates a class announcement
- Teacher creates an assignment
- Parent responds to a consent form
- Admin creates a class and links students, parents, and teachers

Expected output:

- Flow diagrams or step-by-step descriptions
- Main screens involved in each journey
- Error or edge cases

## Task 7: Draft the Software Requirements Specification

Use `docs/srs/srs-template.md` as the starting template.

Expected output:

- 8-12 page SRS
- Functional requirements with IDs
- Non-functional requirements
- MVP acceptance criteria
- Risks and assumptions

Important:

Do not copy a complete specification from another source. Your goal is to think through the product and justify your design decisions.

## Task 8: Create Initial Data Model

Identify the main data entities and relationships.

Suggested entities:

- School
- User
- Role
- Teacher
- Parent
- Student
- Class
- Subject
- Announcement
- Assignment
- ConsentForm
- ConsentResponse
- Notification

Expected output:

- ER diagram or entity list
- Explanation of relationships
- Handling of multiple children per parent
- Handling of multiple guardians per student
- Handling of teachers assigned to multiple classes

## Task 9: Prepare Basic Wireframes

Create low-fidelity wireframes for the main screens.

Required screens:

- Login
- Parent dashboard
- Teacher dashboard
- Admin dashboard
- Announcement list
- Assignment details
- Consent form response

Expected output:

- Hand-drawn, Figma, Excalidraw, or any clear wireframe format
- Short explanation of each screen

## Task 10: Present and Defend

Each group must present their proposal.

Presentation should cover:

- Problem understanding
- Product name and reasoning
- MVP scope
- User roles
- Key workflows
- Requirements
- Data model
- Wireframes
- Risks and limitations

Be ready to answer:

- Why is this feature in the MVP?
- Why did you postpone certain features?
- How will the system avoid notification spam?
- How will it protect student and parent data?
- How will it support Sri Lankan school realities?

## Submission Checklist

- Problem analysis document
- Product name options and recommendation
- MVP and out-of-scope list
- Role-permission matrix
- User stories
- User journey diagrams
- Draft SRS
- ER diagram or data model
- Wireframes
- Presentation slides or document
