# Cursor Rules for Rails 8 Project

This directory contains the rules and guidelines for our Rails 8 project. The rules are organized into categories for better maintainability and clarity.

## Directory Structure

```
.cursor/rules/
├── README.md                        # This file
├── base-rails8.mdc                  # Rails 8 specific settings
├── base-ruby.mdc                    # Ruby language settings
├── base-tailwind.mdc                # TailwindCSS configuration
├── conventions-bin_rails.mdc        # bin/rails usage
├── conventions-database.mdc         # Database conventions
├── conventions-views.mdc            # View standards
├── i18n-base.mdc                    # Base I18n configuration
├── i18n-german.mdc                  # German translation specifics
├── i18n-patterns.mdc                # Common translation patterns
├── system.mdc                       # System testing standards
├── testing-base.mdc                 # Base testing configuration
├── testing-factory_bot.mdc          # Factory Bot standards
├── testing-faker.mdc                # Faker data standards
├── testing-language.mdc             # Language testing standards
├── testing-page_availability.mdc    # Page testing standards
├── testing-quality.mdc              # Code quality standards
└── testing-unit.mdc                 # Unit testing standards
```

## Categories

The rules are organized into the following categories:

1. **Base Rules** (`base-*.mdc`)
   - Project configuration
   - Language settings
   - Framework standards

2. **Conventions** (`conventions-*.mdc`)
   - Coding standards
   - Database practices
   - View guidelines

3. **Internationalization** (`i18n-*.mdc`)
   - Translation standards
   - Language-specific rules
   - Common patterns

4. **Testing** (`testing-*.mdc`)
   - Testing standards
   - Quality assurance
   - Test data management

## Rule Format

Each rule file follows this format:

```markdown
# Rule Title

## Overview

Brief description of what this rule enforces and why it's important.

## Rule Details

Specific requirements and guidelines that must be followed.

## Examples

### Good Examples
Examples of correct implementation.

### Bad Examples
Examples of what to avoid.

## Configuration

Any necessary configuration details.

## When to Use

Specific scenarios where this rule applies.

## Benefits

List of benefits from following this rule.

## Implementation Guide

Step-by-step guide for implementing the rule.

## Common Issues and Solutions

Solutions for frequently encountered problems.

## Related Rules

Links to related rules.

## References

Links to relevant documentation.
```

## Usage

1. Rules are automatically applied to files matching their patterns
2. Multiple rules can apply to the same file
3. Rules are enforced in order of specificity:
   - Base rules (general project configuration)
   - Convention rules (coding standards)
   - Specific rules (feature-specific requirements)
4. Each rule is documented with examples and implementation guides

## Maintenance

- Keep rules focused and specific
- Include practical examples
- Document changes in commit messages
- Test rules before committing
- Update related rules when making changes
- Keep documentation up to date 