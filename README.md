# Cursor Ruby on Rails Rules

A collection of opinionated rules and configurations for the [Cursor AI Code Editor](https://www.cursor.com) to enhance the development experience of Ruby on Rails developers.

## Overview

This project provides a curated set of rules and configurations for the Cursor IDE specifically tailored for Ruby on Rails development. These rules are designed to improve development speed, maintain code quality, and provide a more efficient workflow for Rails developers.

## Benefits

- Increased development speed
- Streamlined workflow for common Rails tasks
- I18n support

## Getting Started

To use these Cursor rules in your Ruby on Rails project:

### Option 1: Clone the Repository

```bash
# Navigate to your Rails project directory
cd your-rails-project

# Clone the rules repository
git clone https://github.com/wintermeyer/cursor-rails-rules.git

# Copy the configuration files to your project
cp -r cursor-rails-rules/.cursor/* .cursor/

# Optional: Remove the cloned repository if you don't need it anymore
rm -rf cursor-rails-rules
```

### Option 2: Manual Download

1. Download this repository as a ZIP file
2. Extract the ZIP file
3. Copy the `.cursor` directory from the extracted files into your Rails project root

### File Locations

The configuration files should be placed in the following locations within your Rails project:

```
your-rails-project/
├── .cursor/           # Cursor configuration directory
│   ├── settings.json  # Main settings file
│   └── rules/         # Custom rules directory
└── ... rest of your Rails project
```

Restart Cursor to be on the safe side.

## Contributing

This is a community project, and we believe that the best rules and configurations come from real-world experience. Whether you're a seasoned Rails developer or just getting started, your input is valuable!

Here's how you can contribute:
- Suggest improvements to existing rules
- Add new rules that have helped your team
- Report bugs or issues you encounter
- Improve documentation
- Share your success stories

The goal is to create a collection of best practices that benefit the entire Rails community. No contribution is too small - even fixing a typo helps!

To contribute code changes:
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

Not familiar with forking repositories? No problem! You can still contribute by creating a GitHub issue:
1. Click on the "Issues" tab at the top of this repository
2. Click the green "New issue" button
3. Choose between:
   - Bug report: If you've found something that's not working correctly
   - Feature request: If you have an idea for a new rule or improvement
4. Fill out the template with as much detail as possible
5. Submit the issue

Your feedback and ideas are valuable to the community, whether they come through code contributions or issues! Let's make Rails development in Cursor even better together! 🚀

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Stefan Wintermeyer <sw@wintermeyer-consulting.de>
https://wintermeyer-consulting.de

---

⭐️ If you find this project helpful, please consider giving it a star! 