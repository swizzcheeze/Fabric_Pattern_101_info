# Fabric Patterns Documentation

A comprehensive guide to Daniel Miessler's Fabric patterns, their functionality, and usage examples.

## What is Fabric?

Fabric is an AI-based tool created by Daniel Miessler that provides a library of "patterns" - specialized templates for processing different types of information using AI models. Each pattern is designed for a specific task, from summarizing content to creating visualizations or writing essays.

## Pattern Categories

Fabric includes over 200 patterns organized into the following categories:

- [Analysis Patterns](#analysis-patterns)
- [Summarization Patterns](#summarization-patterns)
- [Writing Patterns](#writing-patterns)
- [Extraction Patterns](#extraction-patterns)
- [Creation Patterns](#creation-patterns)
- [Improvement Patterns](#improvement-patterns)
- [Visualization Patterns](#visualization-patterns)
- [Code Patterns](#code-patterns)
- [Technical Patterns](#technical-patterns)
- [Specialized Patterns](#specialized-patterns)

---

## Writing Patterns

Patterns designed specifically for content creation and writing tasks.

### write_essay

**Purpose**: Writes concise, clear essays in the style of Paul Graham.

**Description**: This pattern generates essays focused on simplicity, clarity, and illumination of the provided topic. It mimics Paul Graham's distinctive writing style, known for clarity of thought and expression.

**Example Input**:
```
The impact of AI on knowledge work jobs
```

**Example Output**:
```markdown
# The Impact of AI on Knowledge Work Jobs

Knowledge work jobs are being transformed by AI in ways we couldn't have imagined just five years ago. 

Unlike previous technological revolutions that primarily affected manual labor, AI directly impacts jobs that require thinking for a living. Accountants, lawyers, programmers, and analysts - professionals who spent years acquiring specialized knowledge - now face a tool that can replicate aspects of their expertise instantly.

What makes this shift different isn't just the speed of change, but its nature. Previous technologies automated physical tasks; AI automates thought itself...
```

### write_micro_essay

**Purpose**: Writes concise, clear, and illuminating essays on a given topic.

**Description**: Similar to write_essay but produces shorter, more focused pieces while maintaining the Paul Graham inspired style.

### create_formal_email

**Purpose**: Crafts professional, clear, and respectful emails.

**Description**: This pattern analyzes context, tone, and purpose to create well-structured formal emails appropriate for business or academic settings.

**Example Input**:
```
Request meeting with Professor Smith about thesis project delay due to family emergency
```

**Example Output**:
```
Subject: Request for Meeting Regarding Thesis Project Timeline

Dear Professor Smith,

I hope this email finds you well. I am writing to request a meeting to discuss a necessary adjustment to my thesis project timeline due to an unexpected family emergency that has recently arisen.

The situation has temporarily affected my ability to maintain my original schedule, and I would greatly appreciate the opportunity to discuss possible accommodations and establish a revised timeline that would allow me to complete my project to the highest standard.

I am available at your convenience during your office hours on Tuesdays and Thursdays, or at any other time that would suit your schedule this week or next.

Thank you for your understanding and consideration. I look forward to your response.

Sincerely,
[Your Name]
```

### create_academic_paper

**Purpose**: Generates a high-quality academic paper in LaTeX format.

**Description**: This pattern creates structured academic content with clear concepts and professional layout compatible with academic publishing standards.

---

## Analysis Patterns

Patterns designed to examine, evaluate, and interpret content.

### analyze_paper

**Purpose**: Analyzes research papers by summarizing findings, evaluating rigor, and assessing quality.

**Description**: This pattern provides comprehensive insights for documentation and review of academic literature, breaking down complex papers into understandable components.

### analyze_prose

**Purpose**: Evaluates writing for novelty, clarity, and prose quality.

**Description**: This pattern provides ratings, improvement recommendations, and an overall score for written content, helping authors improve their writing.

---

## Extraction Patterns

Patterns designed to identify and extract specific types of information from content.

### extract_wisdom

**Purpose**: Extracts surprising, insightful, and interesting information from text.

**Description**: This pattern focuses on topics like human flourishing, AI, learning, and more, organizing extracted insights into categories.

### extract_main_idea

**Purpose**: Extracts the main idea and key recommendation from input.

**Description**: This pattern summarizes central concepts in concise 15-word sentences, distilling complex content to its essence.

---

## How to Contribute

This documentation is a community effort. To contribute:

1. Fork this repository
2. Add or improve pattern documentation
3. Submit a pull request with your changes

Please follow the established format for consistency.

## Resources

- [Official Fabric Repository](https://github.com/danielmiessler/fabric)
- [Daniel Miessler's Website](https://danielmiessler.com/)
- [Fabric Installation Guide](https://github.com/danielmiessler/fabric#installation)

## License

This documentation is available under the MIT License.
