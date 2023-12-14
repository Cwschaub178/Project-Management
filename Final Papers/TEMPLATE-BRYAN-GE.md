## Finance Accountability Platform
Bryan Ge, Fall 2023

### Introduction
In this paper, I will be describing an idea for an open-source finance accountability app where people and their friends can share financial activity to keep each other accountable for their budgeting goals. Along with that, I will also be discussing the purpose and impact of this app and a general overview of managing this project. The goal of this paper is to apply my learnings from the IS 340 Project Management course through a discussion of a hypothetical open-source project.

### Purpose
The purpose of the application is to solve the problem of staying financially accountable for your goals. Today, many apps connect with your bank accounts and transaction history to help you visualize your spending and savings through graphs and numbers. However, these applications are all narrowly designed for you to keep track of your finances on your own. By expanding the view of your spending to a group of close friends or family, you may be able to find yourself held more accountable and in a fun and supportive environment.

Regarding the development of the application, here are important features and factors to take into account for the best possible user experience. An imperative consideration for any successful mobile app is an interface that marries functionality with simplicity. A visually appealing and intuitive design ensures that users can effortlessly input and access their financial data, creating an engaging and accessible user experience. The heart of the app lies in its ability to seamlessly track expenses. Users can either manually input expenditures or opt for automated tracking by linking the app to their bank accounts through a service such as Plaid. Categorizing expenses provides users with a granular understanding of their spending patterns, empowering them to make informed financial decisions. To encourage collaborative financial planning, the app could allow users to create shared budgets with friends. Implementing spending limits across various categories ensures users adhere to predefined financial boundaries, promoting conscientious spending habits within the group. Keeping users aware of their financial activities in real time is essential. Push notifications can be utilized to alert users when they approach or exceed spending limits, instigating a proactive approach to financial management. Incorporating social features within the app fosters a sense of community among users. Connecting with friends and sharing financial insights through social media-like capabilities creates a collaborative environment centered around responsible financial habits. Streamlining the process of tracking shared expenses for group activities or events is pivotal. The app can facilitate the division of expenses among friends, maintaining a transparent record of who owes what, and simplifying the settlement of financial matters within the group. Motivating users and their friends to stick to financial goals can be achieved through challenges or goal-setting systems. Reminders and notifications serve as friendly nudges, encouraging users to stay on track and discouraging detrimental overspending. Comprehensive reports and analytics offer users valuable insights into their financial behaviors. Visual representations such as graphs or charts provide a quick and easy overview, equipping users with the information needed to make sound financial decisions. Ensuring the security of sensitive financial data is paramount. Robust security measures and customizable privacy settings empower users to control the extent of financial information shared with friends, fostering a secure and trusted platform.

### Audience
This app is meticulously crafted to address the multifaceted needs of a broad demographic, with an emphasis on young adults navigating the complexities of budgeting and financial management during their college and post-graduate years. In recognizing the distinct challenges faced by this dynamic group, the app's design and development take into account several key considerations. The user interface is intuitively structured to ensure accessibility, catering to individuals who may be at various stages of financial literacy.

A pivotal aspect of the app is its collaborative feature, allowing users to seamlessly share financial activities with friends, fostering a sense of communal accountability. Striking a balance between simplicity and functionality, the app integrates tools for tracking expenses, setting budgeting goals, and offering personalized insights.

Privacy and security are paramount, with robust measures implemented to safeguard sensitive financial data. Moreover, the app serves as a learning platform, providing educational resources and tips to empower users to make informed financial decisions. By creating a community-driven space, the app not only facilitates responsible financial habits but also encourages an open dialogue surrounding financial challenges and successes. This thoughtful combination of design elements ensures that the app becomes an invaluable companion for young adults embarking on their journey to financial independence, laying the groundwork for a secure and informed financial future.

### Architecture
Building an open-source finance accountability app involves a commitment to transparency, collaboration, and community-driven development. The foundation of the app will be built upon open-source technologies and frameworks, ensuring that the codebase is accessible and modifiable by a wider community of developers. By embracing an open-source approach, the project encourages collaboration, allowing contributors to enhance features, identify and rectify issues, and suggest improvements.

The development process will begin by selecting a suitable open-source framework that aligns with the app's objectives. This framework will provide the essential structure and tools necessary for the creation of a secure and scalable financial accountability platform. Leveraging established open-source libraries and APIs for functionalities such as user authentication, data encryption, and financial calculations will enhance the efficiency of development while adhering to best practices.

To foster community involvement, the app's source code will be hosted on a public repository platform - GitHub. This facilitates transparency, allowing developers and users alike to examine the code, report bugs, and propose enhancements. An issue-tracking system will be implemented to manage and prioritize tasks, ensuring an organized and collaborative development process.

Regular community engagement will be encouraged through forums, discussion boards, and dedicated communication channels. Users can provide feedback, share their experiences, and contribute ideas, creating a vibrant ecosystem around the app. The development team will actively solicit input on features and improvements, ensuring that the app evolves in response to the actual needs of its user base.

A comprehensive documentation system will accompany the app, guiding both developers and users. This documentation will include setup instructions, API reference guides, and contribution guidelines, making it easier for new developers to join the project and for users to understand and utilize the app effectively.

By adopting an open-source ethos, this finance accountability app will not only provide a valuable tool for users but will also contribute to the broader landscape of financial technology by fostering collaboration, innovation, and shared responsibility within the community.

#### Tech Stack

To ensure widespread accessibility, the app will be built using a cross-platform framework, such as React Native or Flutter. These frameworks allow for the development of a single codebase deployable on both iOS and Android, ensuring a consistent user experience across diverse devices. This choice not only minimizes development efforts but also contributes to a seamless and unified user interface, irrespective of the mobile operating system.

The app's backend, the engine powering seamless functionality, will be constructed using a robust and scalable framework, such as Django or Express.js. These frameworks provide the necessary tools for user authentication, data encryption, and financial calculations. Adopting a RESTful API architecture facilitates smooth communication between the frontend and backend components, ensuring a responsive and efficient user experience.

Efficient data storage and retrieval are paramount in a finance accountability app dealing with sensitive financial information. Therefore, a relational database management system (RDBMS), such as PostgreSQL, will be employed. RDBMS guarantees data consistency and reliability, and best practices like proper indexing and data normalization will be implemented to optimize database performance.

Automated tracking of financial transactions is a key feature, and this will be achieved through integration with the Plaid API. Plaid securely links users' bank accounts, providing real-time access to transaction data. This integration enhances the app's ability to accurately track expenses, adding a layer of convenience to the user experience.

The app will implement robust security measures, encompassing secure coding practices, data encryption, and regular security audits. Customizable privacy settings will empower users to control the extent of financial information shared with friends, ensuring a secure and trusted platform for financial interactions.

The carefully curated tech stack outlined above forms the bedrock of an open-source finance accountability app. This stack not only prioritizes transparency, collaboration, and security but also lays the groundwork for a user-friendly, accessible, and community-driven platform. Through this fusion of technology and financial accountability, the app aims not only to provide a valuable tool for users but also to contribute to the broader landscape of financial technology by fostering collaboration, innovation, and shared responsibility within the community.

#### User Experience

Beyond the technological infrastructure, the success of this app hinges on its user experience. The design and research priorities play a pivotal role in ensuring that the app not only meets the functional needs of users but also delivers an engaging, intuitive, and inclusive platform.

A diverse user base, with varying degrees of financial literacy, necessitates a user-centric design approach. The interface must be intuitively structured to accommodate individuals at different stages of financial understanding. Clear and concise language, coupled with informative tooltips and in-app guidance, can bridge the gap, making the app accessible to both financial novices and experts.

The app's design must be accessible to users with varying abilities and needs. This includes considerations for color contrast, font size, and screen reader compatibility. Adhering to accessibility standards ensures that the app is inclusive, catering to a wide audience and fostering an environment where everyone, regardless of physical ability, can actively participate in financial discussions and accountability.

Financial management can be complex, and user onboarding is crucial in simplifying this complexity. A seamless onboarding process with step-by-step tutorials or an interactive guide will help users set up their profiles, connect their accounts, and understand the core functionalities of the app. Providing a positive onboarding experience encourages users to explore the app further and fosters long-term engagement.

The heart of the app lies in its ability to track expenses. Designing an intuitive and user-friendly expense tracking system is paramount. Users should have the option to manually input expenditures or opt for automated tracking by linking their accounts. Visual cues, such as icons and color-coded categories, enhance the user experience, making it easy for individuals to understand and manage their spending patterns.

Enabling users to create shared budgets with friends necessitates a balance between simplicity and functionality. The collaborative budgeting feature should be seamlessly integrated into the app, allowing users to set spending limits across various categories. The interface should provide a clear overview of shared budgets, encouraging conscientious spending habits within the group while maintaining simplicity in budget management.

Keeping users aware of their financial activities in real time is essential for fostering accountability. Push notifications can be employed to alert users when they approach or exceed spending limits, serving as proactive nudges to encourage responsible financial management. Customizable notification settings allow users to tailor their app experience, striking a balance between staying informed and avoiding notification overload.

Incorporating social features within the app goes beyond functionality—it creates a sense of community. Connecting with friends, sharing financial insights, and engaging in financial challenges through social media-like capabilities foster a collaborative environment centered around responsible financial habits. User research can uncover the most engaging and motivating social features that resonate with the target audience.

Motivating users and their friends to stick to financial goals can be achieved through gamification and goal-setting systems. Challenges, achievements, and progress trackers add an element of fun and competition, transforming financial accountability into an engaging experience. User research can uncover the most effective motivational elements that resonate with the target audience, ensuring sustained user engagement.

Comprehensive reports and analytics offer users valuable insights into their financial behaviors. Visual representations such as graphs or charts provide a quick and easy overview, equipping users with the information needed to make sound financial decisions. The design of these reports should prioritize clarity and actionable insights, empowering users to adjust their financial strategies based on real-time data.

Ensuring the security of sensitive financial data is a top priority in UX design. The app should implement robust security measures and customizable privacy settings. Transparent communication about how user data is handled and protected builds trust among users, fostering a secure and trusted platform for financial interactions.

User testing is an ongoing process that ensures the app aligns with user expectations and needs. Conducting usability tests, gathering feedback through surveys, and implementing feedback loops enable iterative design refinement. This user-centric approach ensures that the app evolves in response to user experiences, enhancing usability and addressing pain points effectively.

In the creation of an open-source finance accountability app, the synergy between technology and user experience is paramount. The UX design and research considerations outlined above serve as a compass, guiding the development process towards creating a platform that not only meets functional requirements but also resonates with users on a personal and engaging level. By prioritizing accessibility, simplicity, and collaboration, the app aims to empower individuals and their friends on their financial journey, fostering a community-driven space for responsible financial habits.

### Conclusion
In conclusion, the proposed open-source finance accountability app represents a holistic approach to addressing the challenges of personal financial management, emphasizing transparency, collaboration, and user-centric design. The purpose of the app is clear: to provide a solution to the common problem of staying financially accountable by expanding the view of spending to a group of friends or family. The detailed features, from intuitive expense tracking to collaborative budgeting and gamified goal-setting, are meticulously designed to create an engaging and supportive environment for users.

The envisioned audience, primarily young adults navigating the complexities of budgeting, is considered in both the app's design and development. The emphasis on simplicity and functionality caters to users at various stages of financial literacy, ensuring accessibility for a broad demographic. Privacy and security measures are paramount, reflecting a commitment to safeguarding sensitive financial data and building trust within the user community.

The open-source architecture and tech stack underscore the project's commitment to transparency and collaboration. By leveraging popular frameworks, APIs, and an RDBMS, the app ensures efficiency, scalability, and security. The choice of a cross-platform framework enhances accessibility, providing a consistent user experience across different devices and operating systems.

The user experience design, characterized by a user-centric approach, focuses on inclusivity, simplicity, and engagement. Accessibility considerations make the app usable for individuals with varying abilities, while a seamless onboarding process and intuitive expense tracking contribute to a positive user experience. Social features, gamification, and comprehensive analytics further enrich the app's capabilities, creating a space where responsible financial habits are fostered through community-driven interactions.

In embracing an open-source ethos, the app not only aims to provide a valuable tool for users but also seeks to contribute to the broader landscape of financial technology. The collaboration of technology and user experience design, guided by the principles of accessibility and community engagement, positions this finance accountability app as a catalyst for innovation and shared responsibility in the realm of personal finance. As a beacon of financial empowerment, the app sets the stage for a secure, informed, and community-driven financial future.

### References
Fontinelle, Amy. “The Biggest Financial Hurdles Young People Face.” Investopedia, Investopedia, 15 Mar. 2023, www.investopedia.com/financial-edge/0712/the-biggest-financial-hurdles-young-people-face.aspx#:~:text=Some%20common%20financial%20mistakes%20that,not%20planning%20for%20the%20future. 

Pino, Ivana. “The 10 Best Budgeting Apps for May 2023.” Fortune Recommends, 13 Dec. 2023, fortune.com/recommends/banking/best-budgeting-apps/.