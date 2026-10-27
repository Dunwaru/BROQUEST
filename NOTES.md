# [BroQuest]

## Summary
2 to 4 player co-op [genre], 3D, Windows first, Steam later.

## Stack
Godot 4.x, GDScript only. Built with AI assistance (Claude + Copilot).

## Structure
- scenes/ (one folder per feature)
- scripts/
- autoload/ (game_manager.gd, network_manager.gd)
- assets/

## Conventions
- snake_case for vars/functions, PascalCase for classes/nodes
- Use type hints
- Signals for events, avoid hard node paths
- Small scripts, one job each
