# HireReady AI – Your Personalized Career Copilot 🚀

HireReady AI is an intelligent career assistant meticulously crafted to empower professionals and job seekers with a suite of tools designed to forge compelling resumes, conquer interviews, and navigate their career journeys with unwavering confidence. Whether you're embarking on a career change, stepping into the professional world for the first time, or aiming for that next significant promotion, HireReady AI dynamically adapts to your unique aspirations and communicates in a way that resonates with your specific needs.

---

## Note

**Note:** Please convert your system theme to a "Dark Theme" for better Experience.

---

## 🎬 Demo Video

[Watch Demo](https://vimeo.com/1077008172/4f5aefab6c?share=copy)

Get a quick visual overview of HireReady AI's key features and how it can help you in your career journey. **Click the image above to watch the demo.**

## 📝 Presentation Slides

[Presentation](https://docs.google.com/presentation/d/11oDZNHIF10rqvdhz4WP7o3rDnzwm166rabogOJHpFy8/edit?usp=sharing)

Explore our detailed presentation to understand the vision, features, and technology behind HireReady AI.

---

## ✨ Key Features

### 📄 Smart Resume Builder
Unleash the power of a meticulously crafted, personalized resume that speaks directly to your target industry. HireReady AI intelligently analyzes your provided information and elevates your content with quantifiable achievements, impactful action verbs, and critical industry-specific keywords that recruiters actively seek.

- **Intelligent Upserts:** Seamlessly update and save your resume iterations, ensuring your progress is never lost.
- **AI-Powered Enhancement:** Benefit from intelligent suggestions driven by Gemini (with flexibility for other LLM integrations), providing insightful recommendations to strengthen your resume's impact.
- **Secure User Authentication:** Built with Clerk for robust and reliable user authentication, safeguarding your personal information.

### 🧠 Real-time Industry Insights
Gain a competitive edge with up-to-the-minute, AI-driven insights directly relevant to your chosen domain. Stay informed about:

- **Essential Skills:** Discover the core competencies and abilities that are highly valued in your industry.
- **Latest Trends:** Keep abreast of the evolving landscape and emerging shifts shaping your field.
- **Cutting-Edge Tools & Technologies:** Identify and understand the key technologies and tools that are gaining traction.
- **Role-Specific Guidance:** Access tailored advice and recommendations specific to the roles you're targeting.

These dynamic insights are seamlessly integrated across the HireReady AI platform, ensuring that all suggestions and improvements are contextually relevant and highly personalized.

### 🧪 Comprehensive Interview Prep
Sharpen your interview skills and boost your confidence with realistic, role-specific, and scenario-based quiz rounds designed to simulate real-world interview experiences.

- **Technical and Behavioral Readiness:** Prepare for both the technical intricacies and the behavioral nuances of your target roles.
- **Personalized Feedback and Scoring:** Receive detailed feedback on your performance, highlighting areas of strength and opportunities for improvement.

### 📨 Intelligent Cover Letter Creator
Generate compelling and personalized cover letters that perfectly complement your resume and align seamlessly with the specific requirements of each job description.

- **AI-Generated Tailored Content:** Leverage the power of AI to craft content that directly addresses the job requirements and highlights your most relevant experience.
- **Clear Formatting and Concise Language:** Ensure your cover letters are professionally formatted and articulate your qualifications with clarity and impact.
- **Fully Editable and Easily Downloadable Output:** Retain complete control over your cover letters with easy editing capabilities and convenient download options.

---

## 🛠️ Core Technologies

- **Frontend Framework**: Next.js (leveraging the modern App Router for enhanced performance and structure) + elegant styling with Tailwind CSS  
- **Backend Infrastructure**: Robust data management with Prisma ORM interacting with a reliable PostgreSQL database  
- **Secure Authentication**: Seamless and secure user management powered by Clerk  
- **Intelligent AI Model**: Cutting-edge language processing powered by Google Gemini  
- **Deployment Platform**: Scalable and reliable hosting on Vercel

---

### Configuration: Setting up your `.env` file

Before running HireReady AI, ensure you create a `.env` file in the root of your project directory and populate it with the following essential environment variables:

```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

```

---

**Note:** Make sure to replace the placeholder values (e.g., `YOUR_POSTGRESQL_CONNECTION_STRING`) with your actual credentials and API keys.

---

# Getting Started: Installation Guide

Follow these straightforward steps to get HireReady AI up and running on your local machine:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Vasanth2310/Hireready-ai.git
    ```

2.  **Navigate to the Project Directory:**
    ```bash
    cd hireready-ai
    ```

3.  **Install Dependencies:**
    ```bash
    npm install
    ```

4.  **Start the Development Server:**
    ```bash
    npm run dev
    ```

Once the development server is running, you can access HireReady AI in your web browser, typically at `http://localhost:3000`.

## 🛡️ Our Commitment to Security & Privacy

Your security and privacy are at the core of HireReady AI's design philosophy. We leverage the industry-leading authentication service, Clerk, to ensure the robust protection of your account and personal information. You can be confident that all user data is securely stored and will never be shared with any external third parties. Your professional journey is yours, and we are committed to keeping your data private.

## 🤝 Join Our Community: Contributing to HireReady AI

We believe in the power of collaboration and enthusiastically welcome contributions from the developer community! If you are passionate about empowering career growth and have ideas or improvements to share, we encourage you to get involved. Here's how you can contribute:

1.  **Fork the Repository:** Begin by creating your own copy of the HireReady AI repository on GitHub.
2.  **Create a Feature Branch:** Branch off the `main` branch to isolate your changes and keep the main codebase clean. Choose a descriptive name for your branch (e.g., `feature/new-interview-module`).
3.  **Implement Your Enhancements:** Develop your features, fix bugs, or implement improvements. Ensure your code adheres to best practices and includes relevant tests.
4.  **Test Thoroughly:** Verify that your changes function as expected and do not introduce any regressions.
5.  **Submit a Pull Request:** Once you're confident in your contributions, submit a pull request to the `main` branch of the original HireReady AI repository. Provide a clear and concise description of your changes and their purpose.

We deeply appreciate your dedication to making HireReady AI an even more valuable resource for professionals worldwide!

## 📄 Licensing Information

HireReady AI is open-source software licensed under the **MIT License**. This permissive license grants you the freedom to use, modify, and distribute the software, even for commercial purposes, as long as you retain the original copyright and license notice. For complete details, please refer to the `LICENSE` file included in the project repository.
