# College Noticeboard

## Overview
This project is a College Noticeboard web application built with Django and styled using Bootstrap 5. It provides full CRUD functionality, enabling users to create, read, update, and delete notices efficiently. The application addresses the need for a centralized, user-friendly platform for managing college announcements, improving communication and accessibility for students and staff.

## UX Design Process
- **Link to User Stories in GitHub Projects:**
  - [GitHub Projects Kanban Board](https://github.com/username/project/kanban)
- **Wireframes:**
  - [Wireframe Designs](https://linktowireframes.com)
  - Wireframes were designed to ensure clarity, intuitive navigation, and compatibility with assistive technologies. High-contrast colors and alt text for images were used to maximize accessibility.
- **Design Rationale:**
  - The layout emphasizes simplicity and readability, with Bootstrap 5 providing a responsive design. The color scheme adheres to WCAG guidelines for contrast, and the typography uses accessible fonts for clarity.
  - Accessibility considerations include keyboard navigation and screen reader support, ensuring usability for users with diverse needs.
- **Reasoning For Any Final Changes:**
  - Based on user feedback, adjustments were made to enhance usability, such as reordering navigation elements for better flow and refining accessibility features. These changes improve the inclusivity of the application.

## Key Features
- **Notice Management:** Create, view, update, and delete notices with ease.
- **User Authentication:** Secure login/logout functionality for managing user access.
- **Inclusivity Notes:** 
  - Features include ARIA labels for screen readers and logical tab order to support keyboard navigation.

## Deployment
- **Platform:** Heroku
- **High-Level Deployment Steps:** 
  1. Set up the Heroku environment with a PostgreSQL database.
  2. Configure environment variables for sensitive data (e.g., secret keys).
  3. Deploy using Heroku Git or GitHub integration.
- **Verification and Validation:**
  - Tested the deployed application against the development environment for consistent functionality and design.
  - Verified accessibility using tools such as Axe and manual testing.
- **Security Measures:**
  - Sensitive data is stored in environment variables.
  - DEBUG mode is disabled in the production environment to enhance security.

## AI Implementation and Orchestration

### Use Cases and Reflections:
  - **Code Creation:** 
    - Reflection: GitHub Copilot assisted in creating Django models, views, and templates, using reverse and multi-step prompts to refine the codebase.
    - Examples: Reverse prompts were instrumental in generating alternative solutions to CRUD operations.
  - **Debugging:** 
    - Reflection: Copilot identified logic errors, offering optimized and accessible solutions.
  - **Performance and UX Optimization:** 
    - Reflection: Copilot-assisted styling with Bootstrap 5 ensured responsive and accessible design with minimal manual adjustments.
  - **Automated Unit Testing:**
    - Reflection: Copilot generated unit tests for all CRUD operations, including edge cases to ensure functionality and accessibility.

- **Overall Impact:**
  - AI tools accelerated development, reduced repetitive tasks, and enhanced focus on key features.
  - Challenges with contextual adjustments to AI outputs were resolved effectively, improving overall code quality and accessibility.

## Testing Summary
- **Manual Testing:**
  - **Devices and Browsers Tested:** Windows 11 (Chrome, Edge), macOS (Safari), Android, iOS.
  - **Assistive Technologies:** Screen readers (NVDA, VoiceOver) and keyboard-only navigation.
  - **Features Tested:** CRUD operations, user authentication, responsive design, and accessibility features.
  - **Results:** All critical features, including accessibility checks, worked as expected.
- **Automated Testing:**
  - Tools Used: Django TestCase, GitHub Copilot.
  - Features Covered: CRUD operations, user authentication, and accessibility compliance.
  - Adjustments Made: Additional manual modifications to ensure comprehensive test coverage and inclusivity.

## Future Enhancements
- Add a notification feature for upcoming events and deadlines.
- Implement voice input for notice creation and navigation.
- Extend multilingual support for non-English-speaking users.
- Enhance analytics for tracking user engagement with notices.
