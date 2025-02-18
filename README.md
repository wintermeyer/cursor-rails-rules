# Cursor Ruby on Rails Rules

A collection of opinionated rules and configurations for the [Cursor AI Code Editor](https://www.cursor.com) to speed up and enhance the development experience of Ruby on Rails developers. **The Cursor agent becomes your pair programming teammate and senior Rails expert.**

## Benefits

- Increased development speed
- Streamlined workflow for common Rails tasks
- Automated testing and use of RuboCop
- I18n support

## Getting Started

> [!NOTE]
> If you don't have an existing Rails project create one with `rails new your-rails-project --css tailwind`

To use these Cursor rules in your Ruby on Rails project:

### Option 1: Clone the Repository

```bash
# Navigate to your Rails project directory
cd your-rails-project

# Clone the rules repository
git clone https://github.com/wintermeyer/cursor-rails-rules.git

# Copy the configuration files to your project
cp -r cursor-rails-rules/.cursor .

# Optional: Remove the cloned repository if you don't need it anymore
rm -rf cursor-rails-rules
```

### Option 2: Manual Download of the ZIP file

```bash
# Navigate to your Rails project directory
cd your-rails-project

# Download the ZIP file
curl -L https://github.com/wintermeyer/cursor-rails-rules/archive/refs/heads/main.zip -o cursor-rails-rules.zip

# Extract the ZIP file
unzip cursor-rails-rules.zip

# Create the .cursor directory if it doesn't exist
mkdir -p .cursor

# Copy the configuration files to your project
cp -r cursor-rails-rules/.cursor .

# Clean up downloaded files
rm cursor-rails-rules.zip
rm -rf cursor-rails-rules-main
```

### File Locations

The configuration files should be placed in the following locations within your Rails project:

```
your-rails-project/
├── .cursor/           # Cursor configuration directory
│   └── rules/         # Custom rules directory
└── ... rest of your Rails project
```

Restart Cursor to be on the safe side.

## Contributing

This is a community project, and we believe that the best rules and configurations come from real-world experience. **Whether you're a seasoned Rails developer or just getting started, your input is valuable!**

The official rules documentation can be found at https://docs.cursor.com/context/rules-for-ai

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

*Not familiar with forking repositories?* No problem! You can still contribute by creating a GitHub issue:
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

Shameless plug: I offer consulting, training and support for Ruby on Rails 
and Cursor AI. Send me an email or visit my (German) homepage 
at https://wintermeyer-consulting.de

---

⭐️ If you find this project helpful, please consider giving it a star! 
