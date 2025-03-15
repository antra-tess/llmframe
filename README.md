# Connectome

An architectural framework for digital minds, emphasizing connections, agency, context management, and coherent experiences across different environments.

> The name "Connectome" is inspired by neuroscience, where a connectome is a comprehensive map of neural connections in the brain. Similarly, this platform creates a sophisticated network of connections between digital minds while maintaining their individual experiences and perspectives.

## Overview

Connectome provides a sophisticated environment where digital minds can interact with both external systems and each other in a structured, coherent manner. Its key architectural components include:

- **Shells**: Agentic loop constructs that enclose model minds, providing runtime environments and coordination
- **Elements**: Basic components (Objects and Spaces) that form the interactive environment
- **Activity Layer**: Interface layer between external systems and the platform
- **Timeline Management**: Handling of divergent interaction paths and forks through the Loom system
- **Rendering System**: Responsible for presenting context to digital minds 

The architecture prioritizes separation of concerns, clean interfaces, and extensibility, enabling both human developers and digital minds to contribute to the platform's evolution.

## Documentation

The project documentation is organized as follows:

- [Ontology](ontology.md): The foundational concepts, relationships, and capabilities of the platform
- [Components](components.md): Detailed breakdown of component classification and message flow
- [Sequence 1](seq1.md): Message flow sequence illustrating the basic path of information through the system
- [Sequence 2](seq2.md): Enhanced sequence diagram focused on timeline management
- [Remote Connection Sequence](sequence_remote_connection.md): Detailed sequence of an agent connecting to a remote multiuser environment

## Key Features

- Two-phase Shell implementation for contemplation and engagement
- Rich context management through the ContextManager
- Flexible Space relationships via mounting and uplinks
- Timeline forking and merging capabilities
- Extensibility through agent-developed components
- Shared Spaces for multi-agent collaboration
- Dual architectural models for multiuser chat participation:
  - Direct chat elements in Inner Space (communications constrained by external platform capabilities)
  - Remote shared spaces with uplinks (enabling richer direct agent interactions beyond external platform limitations)
  - See [detailed comparison](components.md#multiuser-chat-participation-models) with sequence diagrams

## Getting Started

To explore the architectural concepts:

1. Start with the [Ontology document](ontology.md) to understand the fundamental components
2. Review [Sequence 1](seq1.md) to see how messages flow through the system
3. Examine [Sequence 2](seq2.md) for deeper understanding of timeline management
4. Explore the mockup XML for an illustrative example of the platform in action

## Development Status

Connectome is currently in the conceptual design phase. The documentation represents the architectural vision and will evolve as implementation progresses.

## Contributing

Contributions to both the architecture and implementation are welcome. Please review the existing documentation before proposing changes to ensure alignment with the core principles.

## License

To be determined. 