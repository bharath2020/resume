# 👨‍💻 Bharath Booshan Lakshmi Narayanan
**Senior Software Engineer | Product Engineer**

📧 bharath2020@gmail.com  &nbsp; | &nbsp; 📱 +1 408-334-6543 &nbsp;|&nbsp; 📍 Santa Clara, CA, USA  &nbsp;| &nbsp; 🌐 [LinkedIn: www.linkedin.com/in/bharathbooshan](https://www.linkedin.com/in/bharathbooshan)

## 📝 About Me

- Senior iOS Developer with **19 years** of experience delivering high-quality mobile applications across diverse domains, including productivity, location-based services, collaboration, enterprise, social networking, finance, and developer tools.
- Proven expertise in building both consumer apps and internal platform tools for iOS, macOS, and cross-platform environments.
- User-focused, data-driven, and committed to technical excellence and continuous improvement.
- Deep expertise in modern architectures and technologies (MVVM, SwiftUI, Combine, etc.).
- Collaborative team player, working closely with designers, product managers, and backend engineers to deliver impactful solutions.
- Empower teams by developing reusable components, robust APIs, and internal tools that enhance productivity and developer experience.
- Proven leadership: mentor peers, lead technical initiatives, and foster a culture of learning and innovation.
- Dedicated to performance, reliability, and building complex, high-quality applications used by millions of users worldwide.
- At my personal time, I build applications that solve problems I encounter. I recently launched [Captulate](https://apps.apple.com/in/app/captulate/id6749521528?mt=12) that does quick math right from your screen without any copy paste. 


## 💼 Professional Experience

### Senior Software Engineer - Confluence | Atlassian
**Jan 2020 - Present**

### 🌟 Key Highlights
- Created intuitive developer tools that make it easy to build, track, and access Confluence behavioral and observability metrics, empowering teams to move faster with confidence.
- Drove a notable surge (~20%) in weekly usage of Confluence’s search feature and streamlined quick access to spaces, directly boosting user productivity and satisfaction.
- Revamped the feed experience, helping users stay effortlessly connected with their teams and the wider organization—strengthening collaboration and engagement.
- Fostered a culture of data-driven development by championing observability tools, enabling the team to proactively surface and resolve issues before they impact users.
- Engineered a resilient caching system to guarantee data consistency and smooth, reliable access across all screens and features—old and new.
- Elevated reliability and maintainability by building type-safe libraries for network data access, eliminating repetitive data transformations and making observability seamless across the product.
- Spearheaded the development of a robust Analytics and Authentication library, now the backbone for analytics in 6+ Atlassian apps and trusted by millions of users worldwide.


#### 🌟 Project Highlights

> **Note:** Projects were initially native iOS and migrated to React Native as an engineering initiative, with some features and experiments developed in React Native.

#### 🔍 **Search and Spaces Experience Redesign**
- Lead developer for end-to-end search and Confluence spaces experience overhaul.
- Collaborated with designers and product managers to reimagine the search journey, leveraging rapid prototyping and data-driven insights to address user pain points.
- Implemented pre-search suggestions, post-search results, quick actions (e.g., copy), and advanced filters (author, space, time, content type) while maintaining a simple and intuitive interface.
- Improved user recommendations, increasing top 3 result selections by 40% and driving a 20% increase in weekly active search users (WAU) through rapid A/B testing and continuous optimization.
- Built reusable UI components (filter chips, advanced filter sheets) and architected robust modules using TCA, SwiftUI, and Combine.

#### 📰 **Feed Experience Redesign**
- Lead developer for feed experience modernization.
- Introduced Following Feed for team updates and Popular Feed for organization-wide highlights, enhancing content discoverability.
- Enabled users to react to feed items, reply to comments, and perform quick actions (share, watch, copy links) directly from the feed, increasing engagement and collaboration.

**🤖 LLM-Powered Analytics Agent:**
- **Natural Language Analytics Interface:** Designed and implemented an LLM-powered agent that allows users to ask questions about analytics data in plain English (e.g., "How did user engagement change after the last release?"), making it easy for anyone—regardless of technical background—to access insights without learning SQL or analytics tools.
- **Integrated Data Sources:** Integrated the LLM agent with Databricks and Splunk, allowing seamless access to analytics and operational data across platforms.
- **Contextual Issue Investigation:** Enabled first-order investigation of bugs, feedback tickets, and hot issues by allowing the LLM agent to reconstruct user journeys and surface relevant analytics events.
- **Accelerated Experiment Analysis:** Empowered teams to quickly assess the impact of A/B experiments and product changes by asking high-level questions and receiving actionable insights.
- **Stakeholder Empowerment:** Lowered the barrier for non-technical stakeholders to retrieve product data and understand user behavior, fostering a more data-informed culture.

#### 📊 **Analytics & Experimentation Framework**
*Built comprehensive analytics infrastructure and debugging tools*

**🛠️ Analytics Infrastructure & Developer Tools:**
- **Analytics SDK:** Core team member in the Analytics SDK redesign for all Atlassian mobile products, ensuring reliable event persistence and minimizing data loss.
- **Feature Flag Framework:** Built a comprehensive feature flag system integrated with Statsig for robust A/B testing and controlled feature rollouts.
- **Analytics Debugger:** Developed internal debugging tools with real-time event filtering and JSON visualization, streamlining troubleshooting and validation.
- **Experience Tracking:** Implemented detailed experience tracking to monitor app performance and user journeys, enabling data-driven optimizations.
- **Experiment Management:** Designed and built experimentation infrastructure supporting multiple concurrent experiments, allowing rapid iteration and learning.
- **In-app Analytics Debugger:** Delivered an in-app analytics debugger that empowers developers and product managers to instantly validate analytics events and visualize related charts, reducing errors and accelerating feedback cycles.

#### 🔐 **Multi-Account Authentication System**
*Core authentication infrastructure powering all Atlassian mobile products (Confluence, Jira, Trello, etc.)*
*Lead developer for complex multi-account authentication infrastructure*

**Authentication Architecture:**
- **Multi-Account Support:** Led development allowing users to switch between different Atlassian sites seamlessly.
- **Authentication Flow Redesign:** Rebuilt authentication flows for improved user experience and security.
- **Account Management:** Implemented account switching, logout flows, and session management.
- **Deep Link Handling:** Built sophisticated deep link handling for multi-account scenarios.
- **Force Logout & Recovery:** Implemented force logout handling with automatic account recovery.
- **Observability:** Implemented observability metrics to monitor login state health and trigger alerts for authentication anomalies.

#### 🛜 **GraphQL API Migration & Caching Infrastructure**
- Lead developer for GraphQL API migration and caching systems.
- Architected and led the migration from REST to GraphQL APIs, enabling flexible, type-safe requests and reducing redundant network calls.
- Partnered with backend teams to deliver 10+ new mobile-optimized GraphQL APIs and migrated ~30 APIs in 6 months, with observability and performance monitoring.
- Developed components for efficient paginated data retrieval, powering core features like feed and search.
- Designed a normalized cache to store the graph of objects retrieved via GraphQL APIs, acting as a single source of truth and keeping data in sync across features and screens.
- Supported node-level cache invalidation and data expiration, enabling targeted removal of stale content and efficient storage for paginated data.
- Built on CoreData observation APIs to track updates and fetch only changed data, ensuring high performance and seamless offline experiences.

#### ⚙️ **Infrastructure, Build Systems & Performance Optimization**
*Comprehensive modernization of infrastructure, build systems, and performance monitoring across all projects*

- **Dependency Management:** Led upgrades of critical dependencies including MobileKit (15+ version upgrades), Apollo GraphQL, and TCA, ensuring stability and compatibility across the codebase.
- **Build Performance & CI/CD:** Optimized build configurations, resolved framework linking issues, and improved Bamboo CI/CD pipelines for faster, more reliable deployments. Implemented build failure notifications and quality monitoring to maintain high release standards.
- **Release & Deployment Management:** Managed version bumps, release coordination, and deployment processes across multiple app versions, streamlining release cycles.
- **Modular Architecture:** Transitioned to Swift Package Manager for improved modularity and build performance, enabling faster development and easier maintenance.
- **Networking Layer Modernization:** Upgraded HTTP service architecture with enhanced error handling and authentication, supporting robust and secure data flows for all features.
- **Cache Architecture:** Built sophisticated multi-level caching with site-scoped and user-scoped data management, supporting features like feed, search, and widgets.
- **Widget Infrastructure:** Developed shared infrastructure for iOS widgets, including authentication and data management, to support new product initiatives.
- **Performance Metrics & Monitoring:** Implemented intelligent error categorization and reporting, reducing noise in monitoring systems. Built tracking for app startup time, memory usage, user interaction performance, and cache hit rates. Monitored and optimized API response times and data transfer efficiency to ensure a seamless user experience.

*Related points for build, infrastructure, and performance have been integrated into the above project sections where relevant (e.g., GraphQL API Migration, Analytics & Experimentation Framework, Feed Experience Redesign).*

### Senior Software Engineer - Personagraph
*Founding Engineer and Lead Developer*

**September 2012 - May 2016**

- **Data Platform & AdTech SDK Development:** Led the development of a data platform and AdTech SDK for iOS and Android, installed on over 1.5 billion devices, enabling brands and ad agencies to reach their mobile audiences at scale.
- **SDK Architecture:** Built SDK with a focus on a concise API interface, easy adoption, and crash-free performance.
- **Quality Assurance:** Implemented best practices for continuous integration and testing, profiled the SDK for memory leaks, and ensured high-frequency updates without compromising quality.
- **Team Leadership:** Managed a distributed team of 5-8 engineers across Brazil and India, setting best practices for delivering quality code, consistently meeting project delivery deadlines, and embracing automation to keep quality in check.

### Software Engineer - Integral
**February 2012 - August 2012**

- **Data Visualization:** Developed HTML charts using d3.js for the internal backend development team.
- **iOS Development:** Developed an iOS prototype to download foreign exchange rates in real-time.

### Lead Developer - Sourcebits
**February 2009 - January 2012**

Led teams in architecting, developing, and delivering various successful applications:

**Mobile Applications:**
- **AccountEdge (iPad/iPhone):** A companion app for small business accounting.
- **SPOT Connect (iPhone/Android):** A satellite messenger app.
- **Chevia FoodStream (iPhone):** A location-based food and restaurant search app.
- **Charitra (iPhone):** An event planning and coordination tool for SAP.
- **Condor (iOS):** A mobile sales tool interfacing with SAP.
- **Tweet Globe (iPhone):** A Twitter client displaying tweets on a 3D globe.
- **NightStand HD:** A popular alarm clock application with over 10 million downloads, featuring gorgeous clock faces and animations.

**Technical Achievements:**
- Created reusable iOS libraries including network modules, database modules, slideshow controllers, multi-column table views for iPad, object-pool libraries, image cache modules, and data sync modules using Bonjour and Bluetooth.

### **Software Engineer — Robosoft**
*June 2006 – January 2009*

- **Quick Smart Movie Creator:** Developed a rapid movie creation tool enabling search for matching clips across all system movie files.
- **Camcorder Integration:** Implemented camcorder interfacing with Macintosh, extracting video clips and splitting them at points of noticeable frame changes.
- **Search Optimization:** Replaced Spotlight search with an optimized SQLite-based search in Frameline v2.2, reducing search time by 50%.
- **Game Development:**
    - **Aqua Jigsaw:** Created a dynamic jigsaw puzzle game for iOS utilizing an algorithm to generate uniquely shaped pieces with Bezier curves, enhancing the traditional puzzle experience.
    - **Zhiing:** Developed a location-based messaging app allowing users to send messages and obtain routes between sender and receiver by encapsulating GPS coordinates in replies.

## 🎓 Education

**Visvesvaraya Technological University** - Bachelor of Engineering, Computer Science - 2006

## 🛠️ Technical Skills

- **Programming Languages:** Swift, Objective-C
- **iOS Development:** UIKit, CoreAnimation, SwiftUI, CoreData, SQLite
- **Architecture Patterns:** MVVM, TCA (The Composable Architecture), Redux, Unidirectional flow
- **Networking & APIs:** GraphQL, REST APIs, Apollo GraphQL, HTTP services
- **Performance & Testing:** Memory profiling, performance optimization, continuous integration, automated testing
- **Development Tools:** Swift Package Manager, Xcode, Git, CI/CD pipelines
- **Cross-Platform:** iOS, macOS, Android development experience, React Native
- **Data & Analytics:** Analytics frameworks, A/B testing, feature flags, data-driven development
- **Additional Technologies:** GraphQL API development, Android reusable libraries
