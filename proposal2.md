---
geometry: margin=2cm
---

**Project 3 Proposal: Knowledge Garden – A Smarter Way to Share Academic Resources**

## 1. Description of the Use Case

### Problem Statement:

Students and faculty members often face difficulties in accessing and sharing academic resources effectively. The current process is fragmented across various channels—WhatsApp groups, email chains, and cloud storage links—leading to disorganization, redundant content, and accessibility challenges. Moreover, many existing platforms lack the advanced interactive tools needed to foster an engaging academic community.

### Target Users:

- **Students**: Seeking a centralized, interactive repository for study materials, past exam papers, and academic discussions.
- **Faculty Members**: Requiring efficient methods to share, annotate, and verify educational resources.
- **Educational Institutions**: Needing a structured, secure system for knowledge management and collaborative academic engagement.

### Significance:

Knowledge Garden will unify scattered resources into one platform that not only stores and categorizes academic content but also enhances interactivity and collaboration. By integrating real-time tools, intelligent search, and community-driven features, the platform will improve learning outcomes and streamline academic workflows.

## 2. Key Functionalities

### Core Functional Requirements:

1. **Smart Search & Filtering**

   - **Enhanced Search**: AI-powered search that understands natural language queries and auto-suggests relevant keywords.
   - **Advanced Filtering**: Multi-criteria filtering including subject, difficulty level, date added, and user ratings.

2. **Tagging & Categorization System**

   - **Dynamic Tagging**: Auto-tagging of resources using machine learning to suggest subject areas and topics.
   - **Custom Collections**: Allow users to create personal collections and share them with peers.

3. **Interactive Discussion Forums & Real-Time Collaboration**

   - **Community Forums**: Threaded discussions for academic debates and Q&A.
   - **Real-Time Chat & Collaboration**: Live chat rooms and co-annotation features for group study sessions.

4. **Rating & Reviews**

   - **User Feedback**: Ratings and reviews for each resource to ensure quality control.

5. **Resource Annotation & Sharing**

   - **In-Document Annotation**: Tools for highlighting, commenting, and collaborative annotations directly on documents.
   - **Easy Sharing Interface**: Direct sharing options via email, social media, or integration with institutional platforms.

6. **Advanced Analytics & Insights**

   - **Usage Dashboards**: Analytics for tracking resource popularity, user engagement, and study trends.

7. **Accessibility & Mobile Responsiveness**

   - **Responsive Design**: Optimized experience for mobile, tablet, and desktop devices.
   - **Accessibility Features**: Built-in support for screen readers, keyboard shortcuts, and high-contrast themes.

8. **Blue Tick for credibility**
   - **Faculty Verification**: Special badges for faculty-endorsed content, ensuring credibility and reliability.

### Non-Functional Requirements:

1. **Performance**:

   - Capable of handling up to **500 concurrent users** with resource retrieval latency under 2 seconds.
   - Optimized load times even with extensive multimedia content.

2. **Availability & Scalability**:

   - Target **95% uptime**, leveraging cloud infrastructure for fault tolerance.
   - Scalable architecture to manage at least **5,000+ documents** with room for growth.

3. **Security & Data Privacy**:

   - Role-based authentication ensuring that only authorized faculty members can verify resources.
   - End-to-end encryption (TLS 1.2 or higher) for data in transit and secure storage practices.

4. **Usability**:
   - Intuitive UI with a maximum of 3 clicks to access any major feature.
   - Consistent design language throughout with a modular component library for seamless updates.

### Architectural Tactics & Design Patterns:

- **Component-Based Architecture**:
  Leveraging the existing React/TypeScript codebase with dedicated components (e.g., NotificationCenter, AnnotationToolbar, SharingInterface) for reusability and modularity.

- **MVC (Model-View-Controller)**:
  Clean separation of business logic, presentation, and data handling.

- **Singleton Pattern**:
  For managing session and authentication states.

- **Observer Pattern**:
  Facilitates real-time updates in discussion forums and notifications.

- **Factory & Criteria Patterns**:
  Handling multiple resource types (e.g., PDFs, images, videos) and dynamic filtering based on tags and metadata.

- **Microservices Integration**:
  Utilize a microservices architecture for scalability.

## 3. Expected Time to Build a Prototype

| **Phase**               | **Duration (Days)** | **Key Tasks**                                                                                                                                  |
| ----------------------- | ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Research & Planning     | 4                   | Expanded market research, stakeholder interviews, and feasibility studies focusing on real-time collaboration and analytics.                   |
| Design                  | 4                   | Detailed UI/UX design, advanced system architecture (including API design for real-time features), and comprehensive database schema planning. |
| Development             | 12                  | Implementation of core features, integration of AI-based search and tagging, real-time chat, annotation tools, and cloud services.             |
| Testing                 | 3                   | Comprehensive unit, integration, performance, and user acceptance testing with focus on concurrency and security.                              |
| Refinement & Deployment | 3                   | Iterative refinements, security audits, final adjustments based on beta feedback, and deployment to cloud infrastructure.                      |

## 4. Domain

**Education & Collaborative Learning**

Knowledge Garden targets the academic sector by not only organizing educational resources but also by fostering a collaborative learning environment. With features like real-time discussions, live annotations, and advanced analytics, the platform aims to transform the traditional static repository into a dynamic, interactive knowledge hub. This transformation will benefit students, educators, and institutions by streamlining academic resource management and facilitating a richer, more connected learning experience.
