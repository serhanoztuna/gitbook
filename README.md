---
description: >-
  AI-driven development is set to accelerate the pace of innovation, doubling
  efficiency. In response, our SAST solutions are evolving to deliver even
  faster performance
cover: .gitbook/assets/1675159985994.jpg
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# v2311.30 - Latest

{% hint style="success" %}
We're excited to roll out our latest feature - Bitbucket Cloud and Server integrations. Bringing you closer to a seamless development cycle, we've tuned up our CI/CD processes to sync perfectly with your Bitbucket workflow. Expect a sharper dashboard, smarter insights, and an analysis that moves at the pace of your innovation. It's about making your development journey smoother and your security checks sharper. Get ready to code, commit, and deploy with confidence!
{% endhint %}

## 🌟 **Latest Update: v2311.30**

## 🚀 **New Features - API**

### 🔍  **Bitbucket Cloud & Server Integration**

In this update, we've focused on enhancing integration capabilities with a key addition: Bitbucket Cloud and Server support.

* **Bitbucket Integration**: Users can now connect their Bitbucket accounts with CodeThreat for streamlined access and functionality. This integration facilitates direct scanning of Bitbucket repositories within the CodeThreat platform.
* **Simplified Access**: The new integration allows for quick and easy login using Bitbucket credentials, streamlining the process for users who manage their repositories on Bitbucket.
* **Direct Repository Scanning**: With this update, scanning Bitbucket repositories for security and quality checks is more straightforward, providing a more efficient workflow for developers and teams.

<figure><img src=".gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

### 🔍  Scan List Enhancements

* **Commit Message Clarity**: We've improved the scan list to include commit messages. This allows users to easily match scan results with the corresponding code changes.
* **Scan Duration Display**: The scan list now shows the duration of each scan, giving immediate insight into the performance and efficiency of the security checks.

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

**Policy Settings Rework**: A comprehensive rework of policy settings offers clearer guidance and governance for code quality checks.

##

## 🚀 Analyzer Updates

* **AI-Driven App Library Support**: Our analyzer now boasts support for innovative libraries such as "semantic kernel" and langchainjs. Dive into our updated rule list for a comprehensive view of the new additions, all aimed at elevating the intelligence behind our code analysis.
* **Enhanced C# Invocation Analysis**: The invocation expression argument check for C# has been made more library-aware, providing a deeper understanding of your code's context. With this improvement, we're setting the stage for the introduction of implicit sanitization checks, fine-tuning security at the syntax level.
* **Data Flow Graph Visualization**: We're taking transparency to the next level by integrating a Data Flow Graph of current findings into the project overview. This visual map will give you an intuitive grasp of how data moves through your code, making it easier to spot potential issues. By continually refining our data flow algorithms, we aim to provide a more granular and insightful analysis, aiding in the proactive identification and remediation of security vulnerabilities.

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

##

## 🐛 **Bug Fixes and Stability Updates**

* **Scan Stability**: Fixed bugs that affected scan processes, increasing stability and reliability of scans.
* **Source List Navigation**: Resolved a critical bug in source (dangerous inputs) rules iteration.
* **Data Inconsistency**: Resolved a critical bug in repository scan results
* **User Experience Polish**: Minor but impactful UI tweaks to polish the overall user experience, addressing component glitches and enhancing usability.
