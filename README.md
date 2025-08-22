# Table of Contents

1. [Why This Tutorial Exists?](#1-why-this-tutorial-exists)
2. [What You'll Need Before Starting?](#2-what-youll-need-before-starting)
    - [2.1 Essential Information](#21-essential-information)
    - [2.2 Content to Prepare](#22-content-to-prepare)
        - [2.2.1 Announcement Page Content](#221-announcement-page-content)
        - [2.2.2 Registration Details](#222-registration-details)
        - [2.2.3 Agenda Items](#223-agenda-items)
        - [2.2.4 Additional Resources](#224-additional-resources)
        - [2.2.5 Organizers](#225-organizers)
3. [Step-by-Step Setup Guide](#3-step-by-step-setup-guide)
    - [3.1 Choose Your Event Name](#31-choose-your-event-name)
    - [3.2 Fork the Template Repository](#32-fork-the-template-repository)
    - [3.3 Access Your New Repository](#33-access-your-new-repository)
    - [3.4 Configure Your Website Settings](#34-configure-your-website-settings)
    - [3.5 Update Your Event Logo](#35-update-your-event-logo)
    - [3.6 Customize Your Website Content](#36-customize-your-website-content)
        - [3.6.1 index.md - Homepage](#361-indexmd---homepage)
        - [3.6.2 registration.md - Registration Page](#362-registrationmd---registration-page)
        - [3.6.3 agenda.md - Event Schedule](#363-agendamd---event-schedule)
        - [3.6.4 video-slides.md - Resources Page](#364-video-slidesmd---resources-page)
    - [3.7 Enable GitHub Pages](#37-enable-github-pages)
4. [Advanced Customization](#4-advanced-customization)
    - [4.1 Styling Changes](#41-styling-changes)
5. [Troubleshooting Common Issues](#5-troubleshooting-common-issues)
6. [Conclusion](#6-conclusion)
7. [Reach out for help or suggestions!](#7-reach-out-for-help-or-suggestions)

# 1. Why This Tutorial Exists?

Planning an event and need a website? Setting up a professional-looking website traditionally requires frontend and backend development skills, plus the cost of hosting and domain registration. Paid solutions like WordPress or Wix make this easier but come with monthly fees.

**What if you could create a professional event website at absolutely zero cost?**

Thanks to GitHub Pages, open-source templates, and AI tools like ChatGPT, you can now create and host a beautiful event website. This tutorial will show you exactly how to do it.

# 2. What You'll Need Before Starting?

Before diving into the technical setup, gather the following information and materials for your event website:

## 2.1 Essential Information
- **Event name** (this will become your website URL)
- **Event logo** (PNG format recommended)
- **Event date and time**
- **Venue/location details**

## 2.2 Content to Prepare

### 2.2.1 Announcement Page Content
- Participant information
- Event schedule
- Links to communication channels (Slack, Discord, etc.)
- Sponsor information
- Frequently Asked Questions (FAQ)

### 2.2.2 Registration Details
- Registration deadlines
- Link to registration form
- Participant requirements

### 2.2.3 Agenda Items
- Event schedule and activities
- Speaker information
- Session descriptions

### 2.2.4 Additional Resources
- Tutorial videos
- Presentation slides
- Resource links

### 2.2.5 Organizers
- People who are part of organizing team

> 💡 **Pro tip**: You can use ChatGPT or other AI tools to help generate compelling content for these sections.

# 3. Step-by-Step Setup Guide

Helpful to watch below video and follow the steps:

[![Tutorial Video](https://img.youtube.com/vi/GVDz35HganY/0.jpg)](https://www.youtube.com/watch?v=GVDz35HganY)

## 3.1 Choose Your Event Name
Select a clear, memorable name for your event. This will become part of your website URL.

📝 **Example**: 
- Event name: `workshop_2025`
- Resulting URL: `https://kaliningroup.github.io/workshop_2025/`

## 3.2 Fork the Template Repository
1. Navigate to the template repository: [KalininGroup/dummy_website](https://github.com/KalininGroup/dummy_website)
2. Click the **Fork** button in the top-right corner
3. Name your fork with your event name (e.g., `workshop_2025`)
4. Ensure you're forking under the KalininGroup organization

## 3.3 Access Your New Repository
Your forked repository will be available at:
```
https://github.com/KalininGroup/[your-event-name]
```

## 3.4 Configure Your Website Settings
Navigate to the `_config.yml` file in your repository and update the following lines:

```yaml
# Basic site settings
title: "Your Event Name Here"
nav_title: "Your Event Name"

# Event details
event_date: "March 15-16, 2025"

# Site URL
url: "https://kaliningroup.github.io/your-event-name/"
```

⚠️ **Important**: Make sure to replace `your-event-name` with your actual event name throughout the configuration.

## 3.5 Update Your Event Logo
1. Navigate to the `assets` folder in your repository
2. Replace the existing `logo.png` file with your event logo
3. Ensure your logo is in PNG format for best compatibility

## 3.6 Customize Your Website Content
Edit the following Markdown files to add your event-specific content:

### 3.6.1 `index.md` - Homepage
- Add your event description
- Include key highlights and announcements
- Add participant information

### 3.6.2 `registration.md` - Registration Page
- Include registration deadlines
- Add links to registration forms
- List participant requirements

### 3.6.3 `agenda.md` - Event Schedule
- Detail your event timeline
- Include speaker information
- Add session descriptions

### 3.6.4 `video-slides.md` - Resources Page
- Upload tutorial videos
- Share presentation slides
- Add helpful links and resources

## 3.7 Enable GitHub Pages
1. Go to your repository settings
2. Navigate to the "Pages" section
3. Select "Deploy from a branch" under Source
4. Choose the main branch
5. Click "Save"

🎉 Your website will be live at `https://kaliningroup.github.io/your-event-name/` within a few minutes!

# 4. Advanced Customization

## 4.1 Styling Changes
For more advanced visual customization, you can modify the `main.scss` file located in the `assets` directory. This allows you to:
- Change color schemes
- Modify fonts and typography
- Adjust layout spacing
- Customize responsive design elements

# 5. Troubleshooting Common Issues

| Issue | Solution |
|-------|----------|
| Website not loading | Check that GitHub Pages is enabled in your repository settings |
| Images not displaying | Ensure image files are in the `assets` folder and properly referenced |
| Formatting issues | Verify your Markdown syntax is correct |
| URL problems | Double-check that your `_config.yml` URL matches your repository name |

# 6. Conclusion
You now have a professional event website running at zero cost! If you need any help, feel free to open an issue in the template repository.

# 7. Reach out for help or suggestions!
- [utkarshp1161@gmail.com](utkarshp1161@gmail.com)