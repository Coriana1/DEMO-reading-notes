## 5 steps to RBAC
1. What is Role Based Access Control (RBAC) and why do we care?
  - RBAC provides a systematic approach to access control, improving security, reducing complexity, and facilitating efficient management of user access within a system.
2. Describe a Role/Permission heirarchy that you might implement using RBAC.
  - **Superadmin:**
      Permissions: This role has full control and unrestricted access to all system functionalities and resources.
      Responsibilities: Managing and overseeing the entire system, including user management, content management, system configuration, and administrative tasks.
    **Admin:**
      Permissions: This role has administrative privileges with access to critical system functionalities.
      Responsibilities: Managing user accounts, content moderation, system settings, and administrative tasks. They can perform actions such as creating and managing user roles, approving or blocking user-generated content, and managing system configurations.
    **Editor:**
      Permissions: This role has permissions related to content management and editing.
      Responsibilities: Creating, editing, and publishing content. They can manage blog posts, drafts, and other content-related tasks. They have the authority to review and approve content before it gets published.
    **Author:**
      Permissions: This role has permissions to create and manage their own content.
      Responsibilities: Creating, editing, and publishing their own blog posts or articles. They have control over their own content and can manage drafts, updates, and publishing.
    **Contributor:**
      Permissions: This role has limited permissions to create and submit content for review.
      Responsibilities: Creating and submitting blog posts or articles for review by editors or administrators. They can draft and submit their work but require approval from higher-level roles before publishing.
    **Subscriber:**
    Permissions: This role has minimal permissions with limited access to public content.
    Responsibilities: Accessing and reading published content, subscribing to newsletters, and interacting with the community through comments and likes.
3. What approach might you take to implement RBAC?
  - Identify Roles and Permissions, Map Roles to Permissions, Assign Roles to Users/Entities, Implement Access Control Mechanisms, Manage and Maintain RBAC, Audit and Monitor Access

## wiki - RBAC
1. If Authentication is “you are who you say you are,” what is Authorization?
  - The process of determining what actions or resources an authenticated user is allowed to access or perform within a system
2. Name three primary rules defined for RBAC.
  - Role Assignment, Role Permissions, Role Authorization
3. Describe RBAC to a non-technical friend.
  - Provides a structured approach to controlling access within a system, similar to how a security system controls access to different areas of a building based on people's roles and responsibilities

## RBAC tutorial
1. What Are access rights Associated with? The User? or The Role? Explain.
  - Associated with the role, not the individual user. RBAC focuses on managing access based on predefined roles rather than assigning permissions directly to individual users.
2. Access Rights, or Authorization, is activated after a user successfully does what?
  - Access rights or authorization are activated after a user successfully authenticates their identity. Authentication establishes "you are who you say you are," and authorization determines "what are you allowed to do" once your identity is confirmed.
3. Explain how RBAC might benefit a business.
  - RBAC provides a robust framework for access control, offering businesses improved security, streamlined access management, compliance adherence, scalability, and productivity gains. It helps organizations mitigate risks, protect sensitive data, and ensure that the right people have access to the right resources at the right time

## Reflection
1. What are your learning goals after reading and reviewing the class README?
  -