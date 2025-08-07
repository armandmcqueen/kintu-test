# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Python project called "kintu-test" for testing the kintu library. The project uses `uv` as its package manager.

## Development Commands

### Package Management
- **Install dependencies**: `uv sync`
- **Add a dependency**: `uv add <package>`
- **Remove a dependency**: `uv remove <package>`
- **Run Python scripts**: `uv run python <script.py>`

### Python Environment
- The project requires Python >=3.10
- Use `uv` for all package management operations

## Project Structure

This is a minimal Python project with:
- `pyproject.toml`: Project configuration and dependencies
- `uv.lock`: Lock file for reproducible dependency installation