# Cursor Rules for Rails 8 Project

This directory contains the rules and guidelines for our Rails 8 project. The rules are organized into categories for better maintainability and clarity.

## Directory Structure

```
.cursor/rules/
├── README.md                    # This file
├── base/                        # Base configuration rules
│   ├── rails8.mdc               # Rails 8 specific settings
│   ├── ruby.mdc                 # Ruby language settings
│   └── tailwind.mdc             # TailwindCSS configuration
├── conventions/                 # Coding conventions
│   ├── controllers.mdc          # Controller standards
│   ├── database.mdc             # Database conventions
│   ├── models.mdc               # Model standards
│   ├── views.mdc                # View standards
│   └── bin_rails.mdc            # bin/rails usage
├── i18n/                        # Internationalization rules
│   ├── base.mdc                 # Base I18n configuration
│   ├── languages/               # Language-specific rules
│   │   └── german.mdc           # German translation specifics
│   └── patterns.mdc             # Common translation patterns
└── testing/                     # Testing guidelines
    ├── base.mdc                 # Base testing configuration
    ├── factory_bot.mdc          # Factory Bot standards
    ├── faker.mdc                # Faker data standards
    ├── language.mdc             # Language testing standards
    ├── page_availability.mdc    # Page testing standards
    ├── quality.mdc              # Code quality standards
    ├── system.mdc               # System testing standards
    └── unit.mdc                 # Unit testing standards
```

## Rule Format

Each rule file follows this format:

```markdown
# Rule Title

Standards for [topic] in Rails 8.
Applies to: [glob pattern]
Optional: [conditions if rule is optional]

## Section

1. Subsection
[Content in Markdown format]
```

## Usage

1. Rules are automatically applied to files matching their glob patterns
2. Multiple rules can apply to the same file
3. Rules are enforced in order of specificity (base -> conventions -> specific)
4. Optional rules only apply when their conditions are met

## Maintenance

- Keep rules DRY (Don't Repeat Yourself)
- Use references to avoid duplication
- Keep rules focused and specific
- Document changes in this README
- Test rules for conflicts before committing 