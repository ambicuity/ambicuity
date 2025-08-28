# Ritesh Rana Profile Configuration

This configuration file allows easy customization of the GitHub profile README.

## Profile Settings

### Personal Information
- **Name**: Ritesh Rana
- **Tagline**: Full-Stack Developer | Open Source Enthusiast | Problem Solver
- **Bio**: Passionate developer focused on creating innovative solutions and contributing to the open-source community.
- **Quote**: "Turning complex ideas into elegant solutions"

### Contact Information
- **Portfolio**: https://riteshrana.engineer
- **LinkedIn**: https://www.linkedin.com/in/riteshengineer
- **Email**: riteshrana36@gmail.com

### Theme Settings
- **Color Scheme**: Tokyo Night (dark blue theme)
- **Badge Style**: flat-square
- **Stats Theme**: tokyonight
- **Background Color**: 0d1117

### Features Enabled
- Dynamic repository showcase
- GitHub stats and analytics
- Activity graph
- Social links and contact info
- Skills and technology badges
- Automatic updates via GitHub Actions
- Community involvement section
- GitHub Breakout game integration

### Auto-Update Schedule
- **Repository Stats**: Every 12 hours
- **General Updates**: Every 6 hours
- **Breakout Game**: Daily
- **Manual Trigger**: Available via workflow_dispatch

### Security & Privacy
- Only public information displayed
- No sensitive data included
- External services used are reputable and safe
- All API calls are read-only

### Performance Optimizations
- Optimized image sizes and formats
- Lightweight external dependencies
- Fast-loading badges and stats
- Mobile-responsive design

### Accessibility Features
- Screen reader friendly
- High contrast elements
- Descriptive alt text
- Meaningful link text

## Customization Guide

To customize this profile:

1. **Update Personal Info**: Edit the contact links and bio in README.md
2. **Change Theme**: Modify the theme parameter in stats URLs
3. **Add/Remove Skills**: Update the technology badges section
4. **Modify Automation**: Edit the GitHub Actions workflows in `.github/workflows/`
5. **Update Schedule**: Change the cron expressions in workflow files

## Files Structure

```
├── README.md                        # Main profile README
├── .github/
│   └── workflows/
│       ├── update-readme.yml       # Main update workflow
│       ├── update-stats.yml        # Repository stats workflow
│       └── update-breakout.yml     # GitHub Breakout game workflow
├── images/
│   ├── breakout-light.svg          # Light theme breakout game
│   └── breakout-dark.svg           # Dark theme breakout game
├── .gitignore                      # Git ignore rules
└── PROFILE_CONFIG.md              # This configuration file
```

## Maintenance

The profile is designed to be self-maintaining through GitHub Actions. Manual updates are only needed for:

- Personal information changes
- Adding new skills or technologies
- Modifying the design or layout
- Updating contact information

## Dependencies

External services used:
- **shields.io**: For badges and dynamic stats
- **github-readme-stats.vercel.app**: For GitHub statistics
- **github-readme-streak-stats.herokuapp.com**: For streak statistics
- **github-readme-activity-graph.vercel.app**: For activity graphs
- **komarev.com/ghpvc**: For profile view counter
- **cyprieng/github-breakout**: For interactive breakout game generation

All services are lightweight and performance-optimized.