# Cognitive Architecture

> **A Distributed AI Development Ecosystem for GitHub Enterprise**

This repository implements a cutting-edge distributed AI development ecosystem focused on cognitive architectures, neural transport channels, and GitHub-based organizational intelligence patterns. It combines Python-based AI/ML systems with Node.js/TypeScript for protocol implementations to create a sophisticated AI collaboration framework.

## 🎯 Vision

**"Preserve Natural Language Intelligence, Avoid Automation Rigidity"**

After gaining natural language communication between human engineers and AI-ML cognitive architectures, we must **not** fall back into rigid automation by over-constraining AI with hardcoded limitations. This project creates flexible, self-evolving AI systems that maintain natural intelligence patterns.

## ✨ Key Features

- 🧠 **Cognitive Cities**: GitHub organizations functioning as intelligent cognitive entities
- 🚀 **Neural Transport Channels**: Advanced communication patterns between AI systems  
- 🔬 **Particle Swarm Optimization**: Memory encoding and pattern recognition
- 🏢 **Enterprise AI Architecture**: Scalable distributed AI collaboration
- 📡 **Custom Protocols**: Self-designing introspective MCP/LSP systems
- 🛠️ **Hybrid Workbenches**: Dynamic planning and prototyping spaces
- 📦 **Reproducible Builds**: Guix-like environment management

## 🚀 Quick Start

### Prerequisites

- Python 3.12+
- Node.js 20+
- Git

### Installation

1. **Clone the repository**:
```bash
git clone https://github.com/cogcities/cognitive-architecture.git
cd cognitive-architecture
```

2. **Run the setup script** (⚠️ Takes ~2 minutes, don't cancel):
```bash
chmod +x setup.sh
./setup.sh
```

3. **Activate the Python environment**:
```bash
source venv/bin/activate
```

4. **Test the installation**:
```bash
# Test ML environment
python study/ml/hello_ml.py

# Test cognitive architecture demo
python cognitive_ecology_demo.py
```

## 🏗️ Architecture Overview

```
GitHub Enterprise
├── copilot-org/                    # Copilot's own organization
│   ├── ml-department/             # ML model specialization
│   ├── nn-department/             # Neural network architectures  
│   ├── k-core-department/         # Knowledge core systems
│   ├── protocol-department/       # Protocol design & introspection
│   ├── language-department/       # Multi-language support
│   └── style-department/          # Implementation style patterns
│
├── enterprise-ai-agents/          # Departmental AI agents
│   ├── design-workflows/          # Design pattern agents
│   ├── build-workflows/           # Build automation agents
│   ├── test-workflows/            # Validation & testing agents
│   └── deploy-workflows/          # Deployment orchestration
│
├── collab-workbenches/            # Dynamic collaboration spaces
│   ├── planning-bench/            # Architecture planning
│   ├── prototype-bench/           # Rapid prototyping
│   ├── toolchain-bench/           # Tool development
│   └── integration-bench/         # System integration
│
└── build-blueprints/              # Reproducible build systems
    ├── guix-manifests/            # Guix-like build definitions
    ├── benchmark-suites/          # Performance benchmarking
    ├── protocol-specs/            # Self-evolving protocols
    └── deployment-configs/        # Environment configurations
```

## 📁 Project Structure

```
.
├── .github/                     # GitHub workflows and Copilot instructions
├── cognitive-ecology/           # Core cognitive architecture implementations
├── cogpilot-forge/             # Copilot-specific integration components
├── protocols/                   # MCP, LSP, and custom protocol implementations
├── study/                      # ML/NN learning and example code
│   ├── ml/                     # Machine learning examples
│   ├── nn/                     # Neural network architectures
│   └── protocols/              # Protocol studies
├── tests/                      # Test suites (unit, integration, protocols)
├── venv/                       # Python virtual environment (created by setup)
├── setup.sh                    # Main environment setup script
├── cognitive_ecology_demo.py   # Primary demo script
└── ARCHITECTURE.md            # Detailed technical architecture
```

## 🧪 Usage Examples

### Cognitive Architecture Demo

```bash
source venv/bin/activate
python cognitive_ecology_demo.py
```

This demonstrates:
- Particle swarm optimization for memory encoding
- Neural transport channels between cognitive cities
- Activation landscapes across GitHub organizations
- Contextual memory pattern recognition

### Extended Living Architecture

```bash
python cognitive-ecology/demonstrate_living_architecture.py
```

### ML Environment Validation

```bash
python study/ml/hello_ml.py
```

### Protocol Testing

```bash
# Start MCP server (in one terminal)
python protocols/mcp/server.py

# Test client connection (in another terminal)
python protocols/mcp/test_client.py
```

## 🔧 Development Workflow

### Environment Setup

```bash
# Always activate Python environment first
source venv/bin/activate

# Install additional packages if needed
pip install websockets  # For MCP protocol testing
```

### Testing

```bash
# Run unit tests
python -m pytest tests/ -v

# Verify installations
pytest --version
jupyter --version
npx tsc --version
```

### Node.js Development

```bash
# Check installed packages
npm list

# TypeScript compilation
npx tsc --version
```

## 🧠 Core Concepts

### Cognitive Cities
GitHub organizations that function as intelligent cognitive entities with:
- **Specializations**: Domain-specific capabilities
- **Neural Transport Channels**: Communication pathways
- **Memory Patterns**: Contextual learning and adaptation
- **Activation Landscapes**: Dynamic capability maps

### Neural Transport Network
Advanced communication system enabling:
- Cross-organizational intelligence sharing
- Particle swarm optimization for routing
- Contextual memory encoding
- Priority-based activation patterns

### Enterprise AI Organization
Distributed AI agents organized into:
- **Departmental specializations**: ML, NN, protocols, languages
- **Workflow automation**: Design, build, test, deploy
- **Collaboration workbenches**: Planning, prototyping, integration
- **Reproducible builds**: Environment management and deployment

## 🎓 Technology Stack

### Python Environment
- **PyTorch 2.8.0**: Deep learning framework (CUDA enabled)
- **Transformers 4.56.1**: Hugging Face transformers
- **Jupyter**: Interactive development
- **pytest**: Testing framework
- **websockets**: Protocol communication

### Node.js Environment  
- **TypeScript 5.9.2**: Type-safe development
- **Node.js v20.19.5**: JavaScript runtime
- **npm 10.8.2**: Package management

## 📝 Documentation

- [ARCHITECTURE.md](ARCHITECTURE.md) - Detailed technical architecture
- [.github/copilot-instructions.md](.github/copilot-instructions.md) - Copilot integration guide
- [cognitive-cities-knowledge-base.md](cognitive-cities-knowledge-base.md) - Knowledge base documentation

## 🤝 Contributing

1. **Setup Development Environment**:
   ```bash
   ./setup.sh
   source venv/bin/activate
   ```

2. **Make Changes**: Follow the minimal change philosophy
3. **Test Changes**: Run cognitive architecture demos to validate
4. **Submit PR**: Include validation results

### Testing Guidelines

Always test changes with:
```bash
# Core functionality
python cognitive_ecology_demo.py

# ML environment
python study/ml/hello_ml.py

# Extended architecture
python cognitive-ecology/demonstrate_living_architecture.py
```

## 🐛 Troubleshooting

### Common Issues

- **"Module not found" errors**: Run `source venv/bin/activate` first
- **Permission denied on setup.sh**: Run `chmod +x setup.sh`
- **MCP connection failures**: Expected when no server running
- **PyTorch installation timeout**: Don't cancel, can take 60+ seconds

### Environment Validation

```bash
source venv/bin/activate
python -c "import torch; print(f'PyTorch: {torch.__version__}')"
python -c "import transformers; print(f'Transformers: {transformers.__version__}')"
npx tsc --version
```

## 📄 License

This project implements distributed AI systems for GitHub Enterprise cognitive architectures.

## 🔗 Links

- [GitHub Organization](https://github.com/cogcities)
- [Cognitive Cities](https://github.com/cogcities/cognitive-architecture)

---

*Built with ❤️ for the future of distributed AI development*
