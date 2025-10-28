# Changelog

All notable changes to the restaurant_resources package will be documented in this file.

## [v0.1.0] - 2025-01-28

### Added
- **domain3.dom**: New domain with enhanced multi-agent support
  - Implemented `?@executor` variable system for flexible agent assignment
  - Actions now dynamically reference the executing agent
  - Support for agent capabilities and role-based preconditions
- **restaurant_tasks.dom**: Task definitions for restaurant scenario
- **config_mementar.yaml**: Configuration file for mementar integration
- **launch/mementar/**: Launch files for mementar memory node

### Modified
- **domain2.dom**: Updates to domain definitions
- **robot_action.dom**: Enhancements to robot action specifications
- **procedural_memory_node.launch**: Updated launch configuration for procedural memory

### Features
- Multi-agent system with dynamic executor assignment
- Role and capability-based action execution
- Enhanced memory management integration
