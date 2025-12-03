# ExpertSys Builder

![Expert System Interface](https://via.placeholder.com/800x400?text=ExpertSys+Builder+Screenshot)

## Overview

ExpertSys Builder is a comprehensive Single Page Application (SPA) for developing expert systems with integrated artificial intelligence capabilities. This tool enables knowledge engineers and domain experts to create, edit, and deploy rule-based expert systems with optional neural network integration.

## Key Features

### 🧠 Knowledge Base Management
- **Ontology Editor**: Define classes with customizable attributes
- **Rule Builder**: Create IF-THEN rules with confidence factors
- **Fact Management**: Manage instances with class-based attributes
- **Hybrid Knowledge Representation**: Support for both simple facts and object-oriented knowledge

### ⚙️ Inference Engine
- **Forward Chaining**: Automated reasoning based on defined rules
- **Ontology-Aware Reasoning**: Context-aware inference using class hierarchies
- **Confidence Propagation**: Calculations based on rule certainty factors
- **Visual Reasoning Trace**: Step-by-step display of the inference process

### 🤖 Neural Network Integration
- **Brain.js Implementation**: Client-side neural network capabilities
- **Knowledge Base Conversion**: Automatically convert rules to training data
- **Hybrid Reasoning**: Combine traditional rule-based inference with neural network predictions
- **Multiple Network Management**: Save, load, and compare different neural network models

### 📤 Data Management
- **Import/Export**: Multiple formats including JSON, CSV, and CLIPS
- **Local Storage**: Automatic saving to browser storage
- **Backup System**: Create and restore from backups
- **Template Library**: Pre-built examples for medical, IT, and legal domains

## Technology Stack

- **Frontend Framework**: Alpine.js for reactive UI components
- **UI Library**: Bootstrap 5 for responsive design
- **Neural Networks**: Brain.js for machine learning capabilities
- **Storage**: LocalStorage API for persistent data storage
- **Icons**: Bootstrap Icons library

## Installation & Usage

1. Simply download the HTML file and open it in a modern web browser
2. No server setup or additional dependencies required
3. All data is stored in your browser's LocalStorage

## How to Use

### Getting Started
1. Open the application in your browser
2. Navigate between modules using the top navigation tabs
3. Begin by defining your ontology (classes and attributes) in the Editor tab

### Creating an Expert System
1. **Define Classes**: Create domain classes with relevant attributes
2. **Add Facts**: Populate your knowledge base with instances
3. **Create Rules**: Build inference rules connecting facts to conclusions
4. **Test Reasoning**: Use the Inference module to test your system
5. **Enhance with AI**: Train neural networks using your rule base for hybrid reasoning

### Data Management
- Use the Import/Export tab to save your work or load existing systems
- Create backups before making major changes
- Load example templates to jumpstart development in specific domains

## Example Domains

The application includes template systems for:
- **Medical Diagnosis**: Symptom to condition inference
- **IT Support**: Hardware and software troubleshooting
- **Legal Consultation**: Case classification and recommendation

## Browser Compatibility

ExpertSys Builder is compatible with all modern browsers that support:
- ES6 JavaScript
- LocalStorage API
- Canvas API (for neural network visualization)

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests for:
- New features
- Bug fixes
- Documentation improvements
- Additional example templates

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: All user data is stored locally in your browser and is never transmitted to any server. For data security, regularly export your knowledge bases using the Import/Export functionality.
