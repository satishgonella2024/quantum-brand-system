# QuantumLayer Brand System Guide

## Overview

This comprehensive brand guide documents the visual system for the QuantumLayer ecosystem and its sub-brands. The QuantumLayer brand architecture is built around a cohesive family of products, each with a unique purpose but sharing a common visual language.

## Brand Architecture

QuantumLayer uses a branded house strategy, with the parent brand (QuantumLayer) setting the foundation and each sub-brand extending the visual language with its own color palette and application-specific elements.

### Parent Brand

**QuantumLayer**
Core platform for AI agent infrastructure

### Sub-brands

| Sub-brand | Primary Color | Accent Color | Purpose |
|-----------|---------------|--------------|----------|
| **QuantumHub** | #8A63D2 (Purple) | #F0EFFF (Light Purple) | Registry UI, pull/push agent hub |
| **QuantumDesk** | #00BFA6 (Teal) | #E6FCF5 (Light Teal) | Electron/Desktop client for agent management |
| **QuantumCLI** | #F29E4C (Orange) | #FFF5E5 (Light Orange) | Command-line interface for developers |
| **QuantumD** | #4C6EF5 (Blue) | #EAF2FF (Light Blue) | Server backend services (gRPC, REST) |
| **QuantumSDK** | #D6336C (Pink) | #FFF0F6 (Light Pink) | SDK for embedding and automation |

## Core Brand Elements

### Logo

All QuantumLayer brands share a common logo architecture:

1. **Layered Stack**: Blue gradient rectangular layers with rounded corners
2. **Orbital Element**: Orange particle with orbital path
3. **Wordmark**: Two-part name with "Quantum" in white/black and the suffix in the brand's primary color

### Color System

#### Core Palette

- **Layer Gradients**:
  - Top Layer: #4CD4FF → #2E8BFF
  - Middle Layer: #3A92FF → #5A6AFF
  - Bottom Layer: #3A52FF → #7747FF

- **Accent Color**: #FF9040 (Orange)
- **Background**: #0A0E1A (Dark Blue)
- **UI Surface**: #13172A (Lighter Blue)
- **Primary Text**: #FFFFFF (White) 

#### Sub-brand Palette Guidelines

Each sub-brand has its own primary and accent colors while sharing the core palette. The primary color is used for the suffix portion of the wordmark and interactive elements. The accent color (a lighter version of the primary) is used for highlighting areas, backgrounds in light mode, and subtle emphasis.

### Typography

- **Primary Font**: Inter (Sans-serif)
  - Headings: Inter Bold
  - UI Elements: Inter Medium
  - Body Text: Inter Regular

- **Monospace Font**: Fira Code
  - Used for code examples, CLI output, and technical content

### UI Components

All QuantumLayer products follow these UI guidelines:

- **Dark Mode (Default)**:
  - Dark blue background (#0A0E1A)
  - Lighter blue UI surfaces (#13172A)
  - White text on dark backgrounds
  - Sub-brand primary color for interactive elements

- **Light Mode (Alternative)**:
  - White background (#FFFFFF)
  - Sub-brand accent color for section backgrounds
  - Dark text on light backgrounds
  - Sub-brand primary color for interactive elements

- **Buttons**: 
  - Rounded rectangular buttons (border-radius: 15px)
  - Filled buttons use sub-brand primary color
  - Ghost buttons use white stroke with transparent background

- **Cards and Panels**:
  - Slightly rounded corners (border-radius: 5px)
  - Subtle separation using lighter background shades

## Sub-brand Applications

### QuantumHub

**Purpose**: Registry interface for managing agent repositories

**Color Application**:
- Primary: #8A63D2 (Purple)
- Accent: #F0EFFF (Light Purple)

**UI Patterns**:
- Registry explorer with repository cards
- Search functionality for finding agents
- Version history visualization
- Metrics and activity dashboards with purple highlights

### QuantumDesk

**Purpose**: Desktop application for agent management

**Color Application**:
- Primary: #00BFA6 (Teal)
- Accent: #E6FCF5 (Light Teal)

**UI Patterns**:
- Workflow visualization and management
- Agent monitoring dashboards
- Configuration interfaces with teal highlights
- Activity feeds and reports

### QuantumCLI

**Purpose**: Command-line interface for developers

**Color Application**:
- Primary: #F29E4C (Orange)
- Accent: #FFF5E5 (Light Orange)

**Terminal Theme**:
- Command prefix in orange
- Success messages in teal (#00BFA6)
- Error messages in pink (#D6336C)
- Warning messages in orange (#F29E4C)

### QuantumD

**Purpose**: Server backend services

**Color Application**:
- Primary: #4C6EF5 (Blue)
- Accent: #EAF2FF (Light Blue)

**UI Patterns**:
- API documentation with blue highlights
- Method-specific color coding (GET, POST, PUT, DELETE)
- Server status dashboards
- Performance monitoring interfaces

### QuantumSDK

**Purpose**: Development kit for embedding and automation

**Color Application**:
- Primary: #D6336C (Pink)
- Accent: #FFF0F6 (Light Pink)

**UI Patterns**:
- Code examples with syntax highlighting
- Interactive documentation
- API exploration tools
- Integration guides with pink accents

## Application Examples

The `/examples` directory contains mockups demonstrating the practical application of these guidelines for each sub-brand:

- `quantum-hub-ui.svg`: Registry interface example
- `quantum-desk-ui.svg`: Desktop application layout
- `quantum-cli-mockup.svg`: Terminal interface example
- `quantum-d-ui.svg`: API documentation interface
- `quantum-sdk-ui.svg`: Developer documentation example

## Logo Files

Vector logo files for all brands can be found in the `/logos` directory:

- `quantum-layer-logo.svg`: Parent brand
- `quantum-hub-logo.svg`: Registry interface
- `quantum-desk-logo.svg`: Desktop application
- `quantum-cli-logo.svg`: Command-line interface
- `quantum-d-logo.svg`: Server backend services
- `quantum-sdk-logo.svg`: Development kit

## Usage Guidelines

1. **Consistent Spacing**: Maintain adequate clear space around logos (minimum: height of 'q')
2. **Color Accuracy**: Use exact color values specified in this guide
3. **Typography**: Stick to the Inter font family for all text elements
4. **Dark Mode Priority**: Design for dark mode first, then adapt for light mode
5. **Sub-brand Focus**: When promoting a specific product, emphasize its unique color
6. **Family Consistency**: Maintain the core visual elements across all applications

## Accessibility

All color combinations must meet WCAG AA standards for contrast:
- Text on backgrounds: minimum contrast ratio of 4.5:1
- Large text (18pt+): minimum contrast ratio of 3:1 
- Interactive elements: minimum contrast ratio of 3:1 against adjacent colors

## Contact

For questions about the QuantumLayer brand system or to request additional assets, please contact the design team at design@quantumlayer.com