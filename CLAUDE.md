# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a marketing prompt library repository containing HubSpot's Loop Marketing prompts organized into a structured framework. The repository is primarily a collection of markdown files containing specialized marketing prompts rather than traditional code.

## Architecture

The repository follows a four-stage marketing framework architecture:

### 1. Express (`prompt_lib/1__Express/`)
Brand and messaging foundation prompts including:
- Brand differentiation and positioning
- Customer profiling and journey mapping
- Content strategy and voice development
- Competitive analysis and market positioning

### 2. Tailor (`prompt_lib/2__Tailor/`)
Personalization and targeting prompts including:
- Customer data enrichment strategies
- Behavioral segmentation and intent signals
- Personalization engines and dynamic content
- Account-based and lifecycle personalization

### 3. Amplify (`prompt_lib/3__Amplify/`)
Channel expansion and distribution prompts including:
- Channel diversification strategies
- Creator and community partnerships
- Content amplification and viral strategies
- Cross-platform and omnichannel approaches

### 4. Evolve (`prompt_lib/4__Evolve/`)
Optimization and analytics prompts including:
- Campaign performance analysis
- Testing and experimentation frameworks
- ROI optimization and attribution
- Predictive modeling and forecasting

## File Structure

- `prompt_lib/index.md` - Master index of all prompts organized by framework stage
- `prompt_lib/[1-4]__[Stage]/[Prompt Name].md` - Individual prompt files (99 total prompts)
- `dev/` - Development resources and analysis
  - `marketing-prompts-data-analysis.md` - Comprehensive data structure analysis
  - `templates/` - Input data collection templates for prompt usage
- Each prompt file contains structured templates with:
  - ROLE definition
  - CONTEXT explanation
  - TASK description
  - Business context variables
  - Implementation frameworks

## Common Development Tasks

Since this is a documentation/prompt repository, common tasks involve:

- Adding new prompts to the appropriate framework stage directory
- Updating the `prompt_lib/index.md` file when adding new prompts
- Following the established naming convention: `[Number]__[Stage]/[Descriptive Name].md`
- Maintaining consistent prompt structure with ROLE, CONTEXT, TASK, and business context sections
- Using data collection templates in `dev/templates/` to gather input data for prompts
- Updating templates with current business data and performance metrics

## Prompt Structure Standards

All prompts follow a consistent structure:
- **ROLE**: Defines the AI assistant's role and expertise
- **CONTEXT**: Explains the business situation
- **TASK**: Specific task to accomplish
- **Business Context**: Variables for customization
- Implementation sections with specific frameworks and methodologies

## Data Collection Templates

The `dev/templates/` directory contains structured templates for collecting input data required by the marketing prompts:

### Core Data Templates
1. **01-customer-market-data.md** - Customer demographics, behavior, and market intelligence
2. **02-business-context.md** - Company information, strategy, and organizational context
3. **03-performance-data.md** - Campaign metrics, ROI, and performance analytics
4. **04-technology-capabilities.md** - Marketing technology stack and capabilities assessment

### Framework Stage Templates
5. **05-express-stage-data.md** - Brand foundation, messaging, and positioning data
6. **06-tailor-stage-data.md** - Personalization data and customer intelligence
7. **07-amplify-stage-data.md** - Channel expansion and distribution strategies
8. **08-evolve-stage-data.md** - Optimization, testing, and analytics data

### Template Usage
- Start with core templates (01-04) for foundational data needed across all stages
- Complete stage-specific templates (05-08) based on marketing priorities
- Keep templates updated with current performance data and customer insights
- Use completed template sections as structured input when working with marketing prompts

## Analysis Resources

- **dev/marketing-prompts-data-analysis.md** - Comprehensive analysis of data structure patterns across all 99 prompts, including required input categories, collection methods, and implementation dependencies

This repository serves as a comprehensive marketing strategy prompt library following HubSpot's Loop Marketing methodology, with supporting data collection infrastructure for systematic implementation.